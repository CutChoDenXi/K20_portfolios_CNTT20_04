# Portfolio cá nhân | K20_portfolios_CNTT20_04

**Tác giả:** Bùi Đức Duy ([hồ sơ GitHub](https://github.com/CutChoDenXi)). Tên được dùng trong nội dung portfolio mẫu là “An”.

Portfolio thực hành Lab 5 cho học phần Thiết kế Web và Triển khai Hệ thống Phần mềm, xây dựng bằng HTML5 và CSS3 thuần. Trang giới thiệu kỹ năng, dự án và lộ trình học tập; phần liên hệ là form mô phỏng, không có máy chủ xử lý.

## Liên kết

- **Sản phẩm:** [GitHub Pages](https://cutchodenxi.github.io/K20_portfolios_CNTT20_04/)
- **Mã nguồn:** [GitHub repository](https://github.com/CutChoDenXi/K20_portfolios_CNTT20_04)
- **Hồ sơ tác giả:** [CutChoDenXi](https://github.com/CutChoDenXi)
- **Kiểm tra và minh chứng:** [kiem-tra-lab5.txt](kiem-tra-lab5.txt) là mẫu ghi kết quả hiện chưa điền; [AI_LOG.md](AI_LOG.md) ghi lại trạng thái nhật ký AI.

## Cấu trúc thư mục

```text
K20_portfolios_CNTT20_04/
├── index.html          # Portfolio và form liên hệ mô phỏng
├── ket-qua.html        # Trang kết quả mô phỏng sau khi gửi form
├── css/
│   └── style.css       # Giao diện, responsive và trạng thái tương tác
├── kiem-tra-lab5.txt   # Mẫu ghi ca kiểm tra và minh chứng
├── AI_LOG.md           # Nhật ký AI
└── README.md
```

## Chạy local

Không cần cài thư viện hoặc chạy bước build. Mở `index.html` trực tiếp trong trình duyệt, hoặc từ thư mục dự án chạy máy chủ tĩnh:

```powershell
py -m http.server 8000
```

Mở http://localhost:8000 để xem trang.

## Nguồn xuất bản

Mã nguồn được lưu trên GitHub và trang tĩnh được xuất bản bằng GitHub Pages từ repository trên. URL Pages ở phần Liên kết đã được kiểm tra và đang hiển thị portfolio.

## Cách kiểm tra

1. Mở trang chính và lần lượt chọn Giới thiệu, Kỹ năng, Dự án, Lộ trình và Liên hệ trên thanh điều hướng.
2. Ở phần Dự án, kiểm tra trạng thái khi rê chuột trên thẻ; dùng phím Tab để xem chỉ báo focus trên liên kết và nút.
3. Ở form Liên hệ, thử gửi để trống, nhập email sai định dạng, tên ngắn hơn 2 ký tự hoặc nội dung ngắn hơn 10 ký tự. Trình duyệt sẽ áp dụng các ràng buộc `required`, `type="email"` và `minlength`.
4. Nhập dữ liệu giả hợp lệ (tên từ 2 ký tự, email đúng định dạng, nội dung 10–500 ký tự) rồi gửi. Form dùng GET và chuyển đến `ket-qua.html`; dữ liệu sẽ nằm trong URL. Không nhập dữ liệu cá nhân thật.
5. Tại trang kết quả, xác nhận thông báo rằng form không gửi email hoặc lưu dữ liệu, rồi dùng liên kết quay lại phần Liên hệ.
6. Thay đổi kích thước cửa sổ hoặc mở trên thiết bị di động để xem bố cục responsive.

Đây là hướng dẫn để người nhận tự kiểm tra, không phải xác nhận các ca trên đã được thực hiện. Hãy ghi kết quả thực tế và bổ sung minh chứng vào [kiem-tra-lab5.txt](kiem-tra-lab5.txt) trước khi bàn giao.
