
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luyện tập bài 16 Tin học 12</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            background: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        h1 {
            font-size: 24px;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        p {
            font-size: 16px;
            margin-bottom: 15px;
        }

        .highlight {
            font-weight: bold;
            color: red;
        }

        code {
            background: #f3f3f3;
            padding: 2px 4px;
            border-radius: 4px;
            font-size: 14px;
        }

        .important {
            background-color: yellow;
            font-weight: bold;
        }

        .normal {
            background-color: lightblue;
            font-style: italic;
        }

        .custom-border {
            border: 2px solid black;
            border-top: 5px solid red;
            border-bottom: 3px solid blue;
            border-left: 4px dashed green;
            border-right: 2px dotted purple;
            padding: 10px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Luyện tập bài 16 Tin học 12</h1>

    <p><span class="highlight">Luyện tập 1 trang 95 Tin học 12:</span> <strong>Phần tử HTML có thể ẩn đi trên trang web được không? Nếu có thì dùng lệnh CSS gì?</strong></p>
    <p>- Phần tử HTML có thể được ẩn đi trên trang web.</p>
    <p>- Để ẩn các phần tử HTML trên trang web, cần thiết lập CSS với thuộc tính <code>display</code> có giá trị <code>none</code>.</p>

    <p><span class="highlight">Luyện tập 2 trang 95 Tin học 12:</span> <strong>Hãy giải thích ý nghĩa định dạng sau:
<img src="IMG_4913.jpeg">
</strong></p>
    <p>Ý nghĩa:</p>
    <ul>
        <li><code>test.test_more</code>: Đây là một bộ chọn đồng thời (class selector) áp dụng cho các phần tử có cả hai lớp tên là "test" và "test_more". Điều này có nghĩa là chỉ các phần tử có cả hai lớp tên này sẽ được áp dụng định dạng.</li>
        <li><code>background-color: red;</code>: Đây là thuộc tính CSS được sử dụng để đặt màu nền (background-color) của các phần tử được chọn. Trong trường hợp này, màu nền của các phần tử có lớp tên "test
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luyện tập Tin học 12</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            background: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        h1 {
            font-size: 24px;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        p {
            font-size: 16px;
            margin-bottom: 15px;
        }

        .highlight {
            font-weight: bold;
            color: #e74c3c;
        }

        em {
            font-style: italic;
            border: 1px solid blue;
            padding: 2px 4px;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }

        ul li {
            margin-bottom: 10px;
        }

        code {
            background: #f3f3f3;
            padding: 2px 4px;
            border-radius: 4px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1> Giải bài tập Tin học 12 bài 17 </h1>

    <p><span class="highlight">Luyện tập 1 trang 101 Tin học 12:</span> <strong>Giải thích sự khác nhau giữa hai định dạng sau:</strong></p>
    <p>• <code>#p123 + p {color: red;}</code>: áp dụng cho phần tử <code>p</code> với điều kiện phần tử <code>p</code> nằm ngay sau phần tử bất kì có mã định danh <code>#p123</code>.</p>
    <p>• <code>h2#p123 + p {color: red;}</code>: áp dụng cho phần tử <code>p</code> với điều kiện phần tử <code>p</code> nằm ngay sau phần tử <code>h2</code> có mã định danh <code>#p123</code>.</p>

    <p><span class="highlight">Luyện tập 2 trang 101 Tin học 12:</span> <strong>Trong phần Thực hành, các tên riêng (tên người, tên tổ chức) cần được bổ sung định dạng đóng khung và in nghiêng. Em sẽ thực hiện các yêu cầu này như thế nào?</strong></p>
    <p>• Đưa các tên riêng vào thẻ <code>&lt;em&gt;</code>.....<code>&lt;/em&gt;</code>.</p>
    <p>• Tạo mẫu định dạng CSS cho phần tử <code>&lt;em&gt;</code>: <code>em {font-style: italic; border: 1px solid blue;}</code>.</p>

    <p><span class="highlight">Vận dụng 1 trang 101 Tin học 12:</span> <strong>Tìm hiểu thêm các dạng pseudo-class khác, nêu ý nghĩa và tìm ví dụ ứng dụng thực tế cho các kiểu bộ chọn này:</strong></p>
    <ul>
        <li><strong>:hover</strong> - Dạng pseudo-class này được kích hoạt khi người dùng di chuột qua một phần tử. Nó cho phép em áp dụng các định dạng CSS khi phần tử đang được hover.</li>
        <li><strong>:active</strong> - Dạng pseudo-class này được kích hoạt khi phần tử đang được nhấn (khi người dùng giữ chuột trái). Em có thể sử dụng nó để áp dụng các định dạng CSS khi phần tử đang ở trạng thái active.</li>
        <li><strong>:focus</strong> - Dạng pseudo-class này được kích hoạt khi phần tử đang trong trạng thái focus (thường xảy ra khi người dùng click hoặc sử dụng phím tab để di chuyển đến phần tử). Em có thể sử dụng nó để áp dụng các định dạng CSS khi phần tử đang trong trạng thái focus.</li>
        <li><strong>:nth-child()</strong> - Dạng pseudo-class này cho phép em chọn các phần tử con trong một phần tử cha dựa trên vị trí của chúng. Em có thể sử dụng nó để áp dụng các định dạng CSS cho phần tử con cụ thể.</li>
    </ul>

    <p><span class="highlight">Vận dụng 2 trang 101 Tin học 12:</span> <strong>Tìm hiểu thêm các dạng pseudo-element khác, nêu ý nghĩa và tìm ví dụ ứng dụng thực tế cho các kiểu bộ chọn này:</strong></p>
    <ul>
        <li><strong>::before</strong> - Dạng pseudo-element này cho phép em chèn nội dung vào phần tử trước nội dung chính của nó. Em có thể sử dụng nó để thêm các biểu tượng, ký hiệu hoặc phần tử trang trí trước một phần tử.</li>
        <li><strong>::after</strong> - Dạng pseudo-element này cho phép em chèn nội dung vào phần tử sau nội dung chính của nó. Em có thể sử dụng nó để thêm các phần tử trang trí hoặc hiệu ứng sau một phần tử.</li>
        <li><strong>::first-line</strong> - Dạng pseudo-element này cho phép em áp dụng các định dạng CSS cho dòng đầu tiên của một phần tử chứa nội dung văn bản. Em có thể sử dụng nó để thay đổi kiểu chữ, khoảng cách dòng hoặc các thuộc tính khác cho dòng đầu tiên.</li>
    </ul>
</div>

</body>
</html>     
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luyện tập Tin học 12</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.8;
            margin: 0;
            padding: 0;
            background: #f9f9f9;
            color: #333;
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 24px;
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        p {
            font-size: 16px;
            margin-bottom: 15px;
        }

        p strong {
            color: #e74c3c;
        }

        .highlight {
            font-weight: bold;
            color: #3498db;
        }

        /* Hover effect */
        .hover-effect {
            transition: all 0.3s ease-in-out;
            cursor: pointer;
        }

        .hover-effect:hover {
            color: #e74c3c;
            font-weight: bold;
            background-color: #f2f2f2;
            padding: 5px;
            border-radius: 5px;
        }

        footer {
            margin-top: 30px;
            font-size: 14px;
            text-align: center;
            color: #7f8c8d;
        }

        footer a {
            color: #3498db;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<div class="container">
    <h1> Giải bài tập Tin học 12 bài 18 </h1>

    <p><span class="highlight">Luyện tập 1 trang 105 Tin học 12:</span> <strong>Tạo trang dang_ki.html chứa biểu mẫu đăng kí câu lạc bộ và bổ sung liên kết tới trang dang_ki trong phần cuối trang của tất cả các trang.</strong></p>
    <p>Để tạo trang "dang_ki.html" chứa biểu mẫu đăng kí câu lạc bộ và bổ sung liên kết tới trang "dang_ki" trong phần cuối trang của tất cả các trang, em có thể làm như sau:</p>
    <ul>
        <li>Tạo tệp tin HTML mới và đặt tên là "dang_ki.html".</li>
        <li>Trong tệp tin "dang_ki.html", tạo biểu mẫu đăng kí câu lạc bộ bằng cách sử dụng các phần tử HTML như <code>&lt;form&gt;</code>, <code>&lt;input&gt;</code>, và <code>&lt;button&gt;</code>. Thiết kế biểu mẫu theo yêu cầu của em, bao gồm các trường nhập thông tin và nút gửi đăng kí.</li>
        <li>Sau khi hoàn thành biểu mẫu, em có thể thêm CSS để định dạng giao diện biểu mẫu theo ý muốn. Sử dụng các lớp CSS để tạo kiểu cho các phần tử trong biểu mẫu.</li>
        <li>Sau khi tạo xong trang "dang_ki.html", em cần bổ sung liên kết tới trang "dang_ki" trong phần cuối trang của tất cả các trang khác trong website.</li>
    </ul>

    <p><span class="highlight">Luyện tập 2 trang 105 Tin học 12:</span> <strong>Thay đổi định dạng và màu sắc của phông chữ trong các vùng khi di chuyển chuột qua.</strong></p>
    <p>Để thay đổi định dạng và màu sắc của phông chữ trong các vùng khi di chuyển chuột qua, em có thể sử dụng hiệu ứng hover trong CSS.</p>
    <p class="hover-effect">Ví dụ: Khi di chuột qua đoạn văn này, phông chữ sẽ thay đổi màu sắc và kiểu định dạng.</p>

    <p><span class="highlight">Vận dụng trang 105 Tin học 12:</span> <strong>Hãy đưa ra một thiết kế khác cho website đã tạo ở phần Thực hành. Viết định dạng theo thiết kế mới và chuyển toàn bộ website sang định dạng mới.</strong></p>
    <p>Để áp dụng thiết kế mới cho trang web đã tạo trong phần Thực hành, em cần thực hiện các bước sau:</p>
    <ul>
        <li>Tạo một tệp CSS mới và đặt tên là "style.css" (hoặc tên tùy chọn khác).</li>
        <li>Trong tệp CSS, thêm mã CSS để định dạng các phần tử theo thiết kế mới.</li>
        <li>Cập nhật tất cả các trang web trong dự án để sử dụng tệp CSS mới bằng cách thêm liên kết tới tệp CSS trong thẻ <code>&lt;head&gt;</code>.</li>
    </ul>
</div>

<footer>
    <p>© 2025 Tin học 12 | <a href="dang_ki.html">Trang Đăng Kí</a></p>
