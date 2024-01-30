LẬP TRÌNH: FRONT END 

Nều tảng mà tôi có: 
- Từng học qua lập trình ngôn ngữ C/C++
- Chưa biết gì về HTML5
- Chưa biết gì vè CSS3
- Chưa biết gì về Javascript
- Chưa biết gì về ReactJS
- Chưa biết gì về Ant Designed

Mong muốn sau khóa học này có thể xin được intern Front-end 

<details>
    <summary>
        <h1> Bài 1: Giới thiệu cơ bản về Front end<h1>
    </summary>

## 1.1 Giới thiệu khóa học

### Lập trình front-end là gì?

- Tạo ra giao diện website để người dùng `nhìn thấy được`, `tương tác được`
- Làm việc với team `designed` và `back-end`

- Đội designer sẽ cung cấp bản thiết kế giao diện: trên Figma, Adobe XD hoặc Adobe Photoshop

- Đội front-end sẽ dùng: HTML,CSS, JS, ReactJS,...để code lên giao diện đó

- Cần biết đội `back-end` trả về dữ liệu kiểu gì để ghép vào giao diện tương ứng


### Mục tiêu chính:

- Tự tay lập trình được giao diện web theo bản thiết kế
- Nắm vững kiến thức nền tảng (Để làm các tính năng cơ bản đến nâng cao)
- Đủ khả năng ứng tuyển vào các công ty

### Yêu cầu khóa học

- Không bỏ cuộc, học đúng theo lịch trình
- Xem mỗi bài ít nhất 2 lần (Slide + Code)
- Code mỗi ngày
- Làm hết các bài tập

## 1.2 Lộ trình (+41 bài)

- Phần 1: Giới thiệu lộ trình định hướng, học HTML, HTML5 (3 buổi) - Khung xương 
- Phần 2: Học CSS, CSS3, Project mini (5 buổi) - Màu sắc 
- Phần 3: Học bootstrap 4 (4 buổi) - Khung dựng sẵn HTML CSS rồi - gọi ra là dùng đc
- Phần 4: Học git, Github, Project mini 2 (2 buổi)
- Phần 5: Javascript cơ bản và nâng cao, Project mini 3 (9 buổi) - Làm các hiệu ứng,...
- Phần 6: Packkage Managers, BEM, SASS/SCSS, Project mini 4 (3 buổi) - cài đặt thư viện có sắn,...
- Phần 7: ReactJS, Redux, React Router, project mini 5 (10 buổi) - framework được viết trên JS với tính năng sẵn
- Phần 8: Ant Design và Ant design charts(5 buổi)
- Phần 9: Project cuối khóa 

# 1.3 Công việc Front-end trong thực tế

### Mức lương:

Intern: 2-4 triệu
Fresher/Junior: 6-9 triệu/ 9-16 triệu
Middle: 16 - 24 triệu 
Senior: 28 - 40 triệu
Management ( less 5 exp ): 30 - 50 triệu 
Management ( more 5 exp ): 40 - 55 triệu

### Một số project trong thực tế 

Web 1: Pet shop - 1 trang (Lanning page đơn giản)
Web 2: Cây xanh shop - Nhiều trang (Trang chủ và trang con: sản phẩm, giỏ hàng, tin tức, liên hệ,...) 
Web 3: Trang web du lịch - Nhiều trang (Nhiều chi tiết và khó hơn 2 trang trên)

## 1.4 Giới thiệu UI-UX

Đội design sẽ làm 2 công việc này 

### UI là gì?

- UI design (User Interface design): thiết kế giao diện người dùng.
- Một website đẹp và dễ dùng sẽ khiến người dụng thích thú, tạo thiện cảm và tăng độ tin tưởng

### UX là gì?

- UX design (User experience design): là thiết kế trải nghiệm người dùng
- UX là các thao tác người dùng trải nghiệm được trên website

Ví dụ: 
Người dùng muốn mua hàng thì chỉ cần 1 thao tác là có thể hoàn thành việc mua hàng (thật dễ dàng để thanh toán)
Tìm thông tin liên lạc thì chỉ cần 1 thao tác là sẽ nhận được thông tin để liên lạc (tìm là sẽ thấy ngay)


## 1.5 Cài đặt phần mền

### Phần mền: Visual Studio Code
### Tiện tích mở rộng (Extensions)

- Auto Remane Tag (Tự động đặt lại tên thẻ) - Installed
- Beautify (Làm đẹp code) - can not install
- Color Highlight (Hiển thị màu sắc theo mã màu) - Installed
- CSS Variables Autocomplete (Gợi ý các biến trong CSS để code nhanh hơn) - Installed
- HTML Snippets (Gợi ý code HTML) - can not install
- Live Server (Khi lưu code thì web tự load lại) - Installed
- Path Intellisense (Gợi ý đường dẫn các file) - Installed
#### CODE GIAO DIỆN 
- Material Icon Theme (Icon cho theme dễ nhìn hơn) - Installed

## HTML

### 1. Khái niệm 

- HTML là Hyper Text Markup Language: Ngôn ngữ đánh đấu siêu văn bản
- Không phải ngôn ngữ lập trình
- HTML có tác dụng `tạo bố cục` & `định dạng` trang web

VD: Tạo bố cục, định đạng, chèn hình ảnh, video, link, 

### Cấu trúc file HTML và ý nghĩa các thẻ

```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Tiêu đề trên tab</title>
    </head>

    <body>
        <h1>Tiêu đề chính</h1>
        <p>Đoạn văn bản</p>
    </body>

</html>
```
 
### DEV tool

#### Kiểm tra trang - Inspect 

Elements: HTML code
Style: CSS của trang web 
Console: code javascript - debug 
Network: làm về API
Application: javascrip,SQL,...


### Một số thẻ meta <meta>

-
-

### Tạo comments, elements, Altributes

Tạo comment(ghi chú): theo cú pháp sau

```HTML
<!-- Nội dung ghi chú- -->
```

Phím tắt: `Ctrl+/` (windows) hoặc `Cmd+/` (Mac)

### Element 

### Thuộc tính Attribute


### 6.6 Tạo Headings, Paragraphs, Formatting

#### Heading là `tiêu đề` hoặc `phụ đề` được hiển thị

Có 6 thẻ heading: 

- `<h1></h1>` : Thẻ tiêu đề quan trọng nhất, Mỗi trang chỉ có 1 thẻ `h1`. Nếu trang có nhiều thẻ `h1` thì web vẫn chạy nhưng không chuẩn `SEO`
- `<h2></h2>`
- ... 
- `<h6> </h6>`

#### Thẻ paragraphs (đoạn văn)

- Luôn bắt đầu trên 1 dòng mới, thường là 1 khối văn bản
- Cú pháp: `<p>Nội dung</p>`

#### Một số thẻ liên quan:

`<hr>` Horizontal rules - qui tắc ngang : dùng để ngắt theo chủ đề, và được hiển thị dưới dạng 1 đưởng kẻ ngang (empty tag- thẻ trống)
`<br>` Break - ngắt : dùng để ngắt dòng 1 đoạn văn bản -  xuống dòng 

### Formatting (định dạng)

- `<b></b>` (bold - in đậm) 
- `<strong></strong>` văn bản in đậm quan trọng
- `<i></i>` (italic - in nghiêng)
- `<em></em>` (emphasized - nhấn mạnh) in nghiêng và quan trọng
- `<small></small>` chữ nhỏ
- `<sub></sub>` (subcripted - chỉ số dưới) văn bản có chỉ số dưới (VD: H<sub>2<sub>O)
- `<sup></sup>` (superscripted - chỉ số trên) văn bản có chỉ số trên (VD: 20<sup>100</sup>)
- `<ins></ins>` i(nserted - chèn văn bản) được chèn, gạch chân văn bản
- `<del></del>` (deleted - xóa) văn bản đã xóa  - gạch ngang văn bản
- `<mark></mark>` (marked - đánh dấu) văn bản được đánh dấu - Highlight màu vàng
</details>

<details>
    <summary><h1>Bài 2: HTML và HTML5</h1></summary>

<h2>Nội dung:</h2>


1. Thẻ `<a>` Chèn link<br>
2. Thẻ `<img>` chèn ảnh<br>
3. Files paths (đường dẫn)<br>
4. Thẻ `<video>` (chèn video)<br>
5. Thẻ `<audio>` (chèn audio) <br>


</details>
