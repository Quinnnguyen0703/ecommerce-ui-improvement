# ecommerce-ui-improvement
ecommerce-ui-improvement
# E-commerce UI Improvement - Hasaki.vn

## 1. Giới thiệu
Dự án khảo sát trải nghiệm người dùng trên website thương mại điện tử Hasaki.vn và xây dựng giao diện cải tiến cho khu vực danh sách & thẻ sản phẩm (Product Card) bằng HTML5 và CSS3 thuần.

## 2. Website tham khảo
- **Tên website:** Hasaki.vn
- **URL:** https://hasaki.vn/
- **Khu vực đã khảo sát:** Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng.

## 3. Chức năng
- Hiển thị danh sách sản phẩm mỹ phẩm theo dạng lưới trực quan.
- Hiển thị rõ tên thương hiệu, tên sản phẩm, đánh giá, giá gốc, giá khuyến mãi và huy hiệu phần trăm giảm giá.
- Nút thao tác "Thêm vào giỏ" rõ ràng, dễ bấm.
- Bố cục Responsive tự động điều chỉnh trên máy tính (4 cột), máy tính bảng (2 cột) và điện thoại (1 cột).

## 4. Công nghệ
- HTML5
- CSS3 (CSS Grid, Flexbox, Media Queries)

## 5. Cách chạy
Mở trực tiếp file `index.html` bằng trình duyệt web (Google Chrome, Edge, Safari) hoặc truy cập link GitHub Pages.

## 6. Cải tiến đã thực hiện
- **Vấn đề ban đầu:** Thẻ sản phẩm trên trang gốc chứa nhiều nhãn thông tin chồng chéo, nút mua nhanh chưa hiển thị trực tiếp ở danh sách ngoài, gây rối mắt khi xem trên thiết bị di động.
- **Thay đổi đã thực hiện:** Tăng khoảng cách giữa các thẻ, giới hạn tên sản phẩm tối đa 2 dòng (`-webkit-line-clamp: 2`) giúp các thẻ thẳng hàng nhau, làm nổi bật cụm giá khuyến mãi màu cam và bổ sung nút "Thêm vào giỏ" ở đáy mỗi thẻ.

## 7. Hỗ trợ từ AI
- AI hỗ trợ phân tích khung khảo sát 5 khu vực và gợi ý cấu trúc bố cục CSS Grid/Flexbox.
- Bản thân đã trực tiếp đối chiếu lại giao diện thực tế của Hasaki.vn, tự chỉnh sửa bảng màu nhận diện thương hiệu (`#2f6e51` và `#ff6600`), điều chỉnh breakpoint responsive và kiểm tra hiển thị trên Chrome DevTools.