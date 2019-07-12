## Template cơ bản
# meta
- Là thẻ đặt ở đầu dưới phần head
- Tác dụng là cho hiển thị tiếng việt hay không cho thu phóng.
# tại sao nên đặt javascript nên đặt ở cuối thẻ
- Cải thiện tốc độ tải giao diện của trang web và tránh một số trường hợp xảy ra lỗi thực thi ngoài mong đợi.
## Grid system
#responsive
- khi thiết kế các web thì phải chú yes đến độ phân dải của tất cả các màn hình, không để cho chúng có bố cục lộn xộn, hình ảnh bài viết không cân đối
# Cách tạo grid trong bootstrap
- Có class container, row, col 
- Có class container hoặc container-fluid bao bọc tất cả các row và col
- Mỗi một row gồm có các cột
- Mỗi cột có thể chứa 12 cột con khác
# Phân biệt các col
- .col- dành cho các thiết bị rất nhỏ(Extra Small), có chiều rộng nhỏ hơn 576px
- .col-sm- Dành cho các thiết bị nhot(small), có chiều rộng lớn hơn hoặc bằng 576px.
- .col-md- Dành cho các thiết bị trung bình(Medium), có chiều rộng lớn hơn hặc bằng 768px
- .col-lg- Dành cho các thiết bị lớn(Large), có chiều rộng lớn hơn hoặc bằng 992px.
- .col-xl- Dành cho các thiết bị rất lớn (Extra Large), có chiều rộng lớn hơn hoặc bằng 1200px.
# Phân biệt container và container-fluid
- container cho một container có chiều rộng đáp ứng.
- container-fluid cho bộ chứa chiều rộng đầy đủ, trải rộng toàn bộ chiều rộng của chế độ xem.
# Cách mix các suffix trong cùng 1 row
- col-md- sẽ có 12 cột, thì trong row tổng các col-md- sẽ là 12
# Sử dụng nhiều prefix
- Khi web đc xem ở màn hình lớn sẽ có thiết kế col-lg nhưng nếu sang màn hình nhỏ thì bố cục sẽ bị rối, vậy ta phải thêm col-xs vào để khi ta truy cập bằng màn hình nhỏ bố cục vẫn sẽ đẹp như ta thiết kế
# Sử dụng sử dụng offset
- Ta có thếr thiết kế bố cục theo offset, vd: class="col-md-6 offset-md-3" ở đây có một cột độ dài là 6 cột đơn vị, và cách lề bên trái độ dài 3 cột đơn vị 
# Lồng các cấu trúc grid
- Ta có thể lồng các row bằng cách thêm các row nhỏ hơn vào bên trong, nhưng với điều kiện các cột tối đa 12 cột đơn vị hoặc ít hơn.