<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luyện Tập và Vận Dụng Bài 16, 17, 18</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f4f4f9;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .main-title {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            color: #e74c3c;
            margin-bottom: 30px;
        }
        h1 {
            color: #e74c3c;
            text-transform: uppercase;
            margin-bottom: 15px;
        }
        h2 {
            color: #3498db;
            margin-top: 20px;
        }
        p {
            margin: 10px 0;
        }
        ol {
            margin: 10px 0;
            padding-left: 20px;
        }
        li {
            margin: 5px 0;
        }
        code {
            background: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
        .highlight {
            background-color: #fdebd0;
            padding: 10px;
            border-left: 4px solid #e74c3c;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="main-title">LUYỆN TẬP, VẬN DỤNG BÀI 16, 17, 18</div>

        <!-- Bài 16 -->
        <h1>Bài 16</h1>
        <ol>
            <li>LUYỆN TẬP 1: Phần tử HTML có thể ẩn đi trên trang web được không? Nếu có thì dùng lệnh CSS gì?</li>
            <div class="highlight">
                <p><strong>Trả lời:</strong> Có thể ẩn phần tử HTML trên trang web bằng cách sử dụng lệnh CSS:</p>
                <code>visibility: hidden;</code>
                <p>hoặc:</p>
                <code>display: none;</code>
            </div>
            <li>LUYỆN TẬP 2: Hãy giải thích ý nghĩa định dạng sau:</li>
            <div class="highlight">
                <code>.test .test_more { background-color: red; }</code>
                <p><strong>Giải thích:</strong> Đây là định dạng CSS quy định rằng bất kỳ phần tử HTML nào có lớp <code>test_more</code> và nằm bên trong phần tử có lớp <code>test</code> sẽ được áp dụng màu nền <code>red</code> (đỏ).</p>
            </div>
            <li>VẬN DỤNG 1: Giả sử nội dung trang web của em có rất nhiều thẻ <code>p</code>, trong đó có ba đoạn mà em thấy quan trọng nhất, ký hiệu các đoạn này là P1, P2, P3. Có cách nào thiết lập định dạng CSS để có thể định dạng P1 khác biệt, P2 và P3 có cùng kiểu và cũng khác biệt không? Tất cả các đoạn còn lại có định dạng giống nhau. Hãy nêu cách giải quyết vấn đề của em.</li>
            <div class="highlight">
                <p><strong>Trả lời:</strong></p>
                <ul>
                    <li>Gắn một lớp tên riêng cho P1, ví dụ: <code>&lt;p class="important"&gt;Đoạn P1&lt;/p&gt;</code>.</li>
                    <li>Gắn cùng một lớp tên cho P2 và P3, ví dụ: <code>&lt;p class="normal"&gt;Đoạn P2&lt;/p&gt;</code>, <code>&lt;p class="normal"&gt;Đoạn P3&lt;/p&gt;</code>.</li>
                    <li>Sử dụng CSS để áp dụng các định dạng khác biệt:</li>
                    <code>
                        .important { color: red; font-weight: bold; }<br>
                        .normal { color: blue; font-style: italic; }
                    </code>
                </ul>
            </div>
            <li>VẬN DỤNG 2: Có thể thiết lập định dạng cho các khung với thông số khung, viền trên, dưới, trái, phải khác nhau được không? Em hãy tìm hiểu và trình bày cách thiết lập định dạng CSS cho các khung, viền như vậy.</li>
            <div class="highlight">
                <p><strong>Trả lời:</strong> Hoàn toàn có thể thiết lập. Sử dụng CSS để định dạng như sau:</p>
                <code>
                    .box { <br>
                        border-top: 3px solid red; <br>
                        border-bottom: 5px dashed blue; <br>
                        border-left: 2px dotted green; <br>
                        border-right: 4px double black; <br>
                    }
                </code>
                <p>Ví dụ minh họa: <code>&lt;div class="box"&gt;Nội dung&lt;/div&gt;</code>.</p>
            </div>
        </ol>

        <!-- Bài 17 -->
        <h1>Bài 17</h1>
        <ol>
            <li>LUYỆN TẬP 1: Giải thích sự khác nhau giữa hai định dạng sau:</li>
            <div class="highlight">
                <code>#p123 + p { color: red; }</code>  
                <code>h2#p123 + p { color: red; }</code>  
                <p><strong>Trả lời:</strong></p>
                <ul>
                    <li><code>#p123 + p</code>: Chọn thẻ <code>p</code> ngay sau phần tử có ID là <code>p123</code>.</li>
                    <li><code>h2#p123 + p</code>: Chọn thẻ <code>p</code> ngay sau một thẻ <code>h2</code> có ID là <code>p123</code>.</li>
                </ul>
            </div>
        </ol>

        <!-- Bài 18 -->
        <h1>Bài 18</h1>
        <ol>
            <li>LUYỆN TẬP:</li>
            <a href="https://mai1210.github.io/LUY-N-T-P-B-I-18/" target="_blank">bài 1, 2</a>. Viết lại cho đúng.
        </ol>
    </div>
</body>
</html>
