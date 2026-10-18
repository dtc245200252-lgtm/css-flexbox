# Tạo bố cục responsive bằng CSS Flexbox

## Mục tiêu
Luyện tập sử dụng CSS Flexbox để tạo một bố cục trang web responsive, hiển thị tốt trên cả desktop và mobile.

## Mô tả cấu trúc
1. **Header**: Hiển thị tiêu đề trang (`.header`)
2. **Navigation**: Chứa menu điều hướng (`.nav`, sử dụng Flexbox sắp xếp menu)
3. **Main Content**: Khu vực hiển thị nội dung chính (`.content` với `flex: 3`)
4. **Sidebar**: Chứa nội dung phụ (`.sidebar` với `flex: 1`)
5. **Footer**: Hiển thị thông tin cuối trang (`.footer`)

## Responsive trên thiết bị di động
- **Desktop**: Header, navigation, main-container (gồm content và sidebar nằm ngang theo tỷ lệ 3:1), và footer.
- **Mobile** (`max-width: 768px`): `.main-container` chuyển sang `flex-direction: column` để các phần tử xếp chồng theo chiều dọc giúp hiển thị gọn gàng hơn.
