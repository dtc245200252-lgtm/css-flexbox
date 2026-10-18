# Xây dựng bố cục trang web với CSS Flexbox

## Mục đích
Luyện tập sử dụng CSS Flexbox để xây dựng một bố cục trang web responsive, giúp hiển thị tốt trên cả desktop và mobile.

## Cấu trúc bố cục
- **Header**: Tiêu đề trang (`.header`)
- **Navigation**: Menu điều hướng (`.nav`)
- **Main Container**: Khu vực chứa nội dung chính và sidebar (`.main-container`)
  - **Main Content**: Khu vực hiển thị nội dung chính (`.content` với `flex: 3`)
  - **Sidebar**: Chứa nội dung phụ (`.sidebar` với `flex: 1`)
- **Footer**: Thông tin cuối trang (`.footer`)

## Responsive Design
- Khi màn hình nhỏ hơn hoặc bằng `768px`, thuộc tính `flex-direction: column` được áp dụng cho `.main-container` để `sidebar` tự động chuyển xuống dưới `content`.
