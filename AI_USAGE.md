# AI Usage Log

## 1. Công cụ AI
- Tên công cụ: Gemini

## 2. Mục đích sử dụng
- Hỗ trợ lập bảng phân tích 5 khu vực chức năng của website Hasaki.vn.
- Gợi ý bố cục HTML5/CSS3 cho thẻ sản phẩm responsive.

## 3. Prompt đã sử dụng
- **Prompt 1:** Phân tích 5 khu vực (Trang chủ, Danh mục, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng) của website Hasaki.vn (https://hasaki.vn/).
- **Prompt 2:** Đề xuất bố cục giao diện cải tiến thẻ sản phẩm bằng HTML5 và CSS3 cho khách hàng mua sắm tại Việt Nam.

## 4. Kết quả AI đề xuất
- AI đưa ra bảng đánh giá mục đích, ưu/nhược điểm từng khu vực và gợi ý sử dụng CSS Grid kết hợp Flexbox để căn chỉnh thẻ sản phẩm đều nhau.

## 5. Kiểm tra và điều chỉnh
- **Điểm đã đối chiếu & loại bỏ:** Loại bỏ các nhận xét chung chung của AI chưa kiểm chứng thực tế trên Hasaki.vn; bổ sung nhận xét thực tế về bộ lọc chi tiết theo loại da và thanh báo ngưỡng Freeship trong giỏ hàng.
- **Điểm tự chỉnh sửa trong mã nguồn:** Tự điều chỉnh mã màu CSS theo đúng tông xanh lá - cam của Hasaki, bổ sung thuộc tính `aspect-ratio: 1 / 1` cho khung ảnh sản phẩm để tránh méo ảnh, và thêm trạng thái `:hover` cho thẻ sản phẩm.

## 6. Phần tôi hiểu và có thể giải thích
- Cấu trúc thẻ ngữ nghĩa HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- Cách dùng `display: grid` và `@media (max-width: ...)` để chia lại số cột trên màn hình điện thoại.
- Cách dùng `display: flex; flex-direction: column;` kết hợp `margin-top: auto;` ở `.price-box` để đẩy cụm giá và nút mua hàng luôn nằm thẳng hàng ở đáy thẻ dù tên sản phẩm dài hay ngắn.