
# Cấu trúc cơ bản
- !DOCTYPE html>: khai báo rằng trang web được hiển thị bằng html, phải được khai báo
- Thẻ html>: cho trình duyệt biết đây là tài liệu HTML, là nơi chứa tất cả các thành phần khác ngoại trừ <!DOCTYPE html>:
- head>: chứa tất cả các phần ban đầu, như là title, style, link, meta, script, ...
- meta />: cung cấp thông tin dữ liệu về văn bản HTML, thông tin dữ liệu sẽ không được hiển thị trên trình duyệt, hường được sử dụng để xác định mô tả trang, từ khóa , tác giả của văn bản, sửa đổi lần cuối, và thông tin dữ liệu khác.
- title>: tiêu đề cho trang web.
- /head>: kết thúc phần head>
- body>: Phần thân của tài liệu chứa tất cả văn bản, liên kết,…
# Thẻ heading
- Định nghĩa tiêu đề của một trang web
- Trong đó h1> là thể hiện tiêu đề chính. Tiếp theo là các tiêu đề h2 h3 h4 h5 h6 giảm giần về sự quan trọng hơn so với tiêu đề phía trước nó
# Thẻ paragraph
- Thẻ p là thể hiện là một đoạn
# Thẻ link
- Link dùng để liên kết với tài nguyên và file bên ngoài
- Href chỉ định vị trí được liên kết giá trị là các url
- Title là hiển thị thông tin tiêu đê liên kết, thường được sử dụng dạng văn bản text
- Target xác định nơi mà tài liệu được load: _blank, _self, _top, _parent, frame_name
# Thẻ image
- Image thẻ hình ảnh
- Src thuộc tính xác định URL (địa chỉ web) của hình ảnh
- Các alt thuộc tính cung cấp một văn bản thay thế cho hình ảnh, nếu người sử dụng đối với một số lý do không thể xem nó.
- widthvà height: kích thước của ảnh.
# Thẻ list
- ul xác định danh sách không có thứ tự 
- ol xác định danh sách theo thứ tự
- dl xác định danh sách (có đề mục và phần mô tả đề mục)., có thể có nhiều thẻ đ cho 1 dt
- Lồng danh sách Để làm việc đó bạn chỉ cần chèn thêm 1 danh sách nữa vào giữa cặp thẻ li /li là được.
# Thẻ table
- th là tiêu đề, hay tên của cột
- td là giá trị của 1 ô đó
- Rowspan nối ô trên dưới
- Vì row này 1 ô đã được nối với ô ở trên nhờ thuộc tính Rowspan
- Vì row này vừa có thuộc tính Rowspan và colspan
- Colspan là nối 2 ô liên tiếp theo hàng
# Thẻ form và input
- Action chỉ định nơi gửi dữ liệu
- Method chỉ định phương thức khi gửi dữ liệu
- Các type có thể có: text, password, hidden, checkbox, radio, button, button reset, button submit, image, file upload
- Value giá trị đầu tiên cho trường nhập dữ liệu
- Name chỉ định tên
- Label for yêu cầu giá trị này giống với giá trị ở đâu đó
- Checker là thuộc tính Boolean kiểm tra 
- Button, button reset, button submit
- Rows cols chiều dài và rộng của thẻ textarea
- Selected tùy chọn mặc định, sẽ hiển thị cái selected
# Thẻ trung tính
- Thẻ span là thẻ  được thêm vào đoạn văn nhưng không làm thay đổi thuộc tính cũng như hiển thị của đoạn văn đó
- Div được sử dụng để định nghĩa một khu vực trong trang web của bạn. 
- Thẻ span  thẻ Span thường dùng để định dạng cho một chữ hoặc mội chuỗi chữ muốn định dạng, thẻ span không xuống hàng, mà thẻ Div sẽ bị xuống hàng.
# Style
- Inline CSS được sử dụng cho một thẻ HTML xác định. Cách viết này sẽ rất khó để quản lí trang web cũng như sửa.
- External thêm Style CSS vào website là liên kết với một file .css ở bên ngoài., sẽ được đặt link trong mục head của trang

# Thẻ script 
- Scrip inline là sử dụng viết code ngay trong script trong file html
- Script load là sẽ sử dụng đường link đến file .js trong thẻ script
