# Portfolio CV - Đàm Quang Linh

## Thông tin sản phẩm

- **Tác giả hiển thị trên trang:** Đàm Quang Linh
- **Mô tả:** Website portfolio tĩnh bằng HTML/CSS, giới thiệu kỹ năng, dự án, học tập và thông tin liên hệ; có form thực hành chuyển tới trang kết quả.
- **Repo:** [linhdam208-hash/K20_Portfolio_CNTT20_04-](https://github.com/linhdam208-hash/K20_Portfolio_CNTT20_04-)
- **GitHub Pages:** [Mở portfolio](https://linhdam208-hash.github.io/K20_Portfolio_CNTT20_04-/)
- **Hồ sơ GitHub được liên kết trong trang:** [github.com/damquanglinh](https://github.com/damquanglinh)
- **Hồ sơ chủ repo:** [github.com/linhdam208-hash](https://github.com/linhdam208-hash)

URL Pages đã được mở và nội dung portfolio được tải khi chuẩn bị tài liệu. Hai hồ sơ GitHub nêu trên khác nhau; hãy xác nhận hồ sơ tác giả muốn dùng trước khi bàn giao.

## Cấu trúc thư mục

```text
.
├── index.html       # Trang portfolio
├── ket-qua.html     # Trang kết quả tĩnh của form liên hệ
├── css/
│   └── style.css    # Giao diện và bố cục
├── README.md
├── AI_LOG.md
└── RELEASE_NOTES.md
```

Các trang HTML hiện tham chiếu ảnh trong `assets/`, nhưng thư mục và các tệp ảnh đó không có trong repo tại thời điểm ghi tài liệu. Vì vậy, ảnh đại diện và ảnh minh họa dự án có thể không hiển thị.

## Chạy local

Đây là website tĩnh, không cần cài package hay build. Mở PowerShell tại thư mục repo và chạy:

```powershell
py -m http.server 8000
```

Nếu máy không có lệnh `py`, dùng `python -m http.server 8000`. Mở [http://localhost:8000](http://localhost:8000); dừng server bằng `Ctrl+C`.

## Cách kiểm tra trang và chức năng

1. Mở `index.html` trên Pages hoặc local. Dùng menu để kiểm tra các mục Giới thiệu, Kỹ năng, Dự án, Học tập và Liên hệ; thử nút “Xem dự án”.
2. Kéo xuống phần Liên hệ và thử gửi form:
   - Họ tên bắt buộc, tối thiểu 2 ký tự.
   - Email bắt buộc và phải đúng định dạng email.
   - Lời nhắn bắt buộc, từ 10 đến 500 ký tự.
   - Thử bỏ trống hoặc nhập sai để kiểm tra xác thực HTML5; nhập dữ liệu hợp lệ để chuyển đến `ket-qua.html`.
3. Ở trang kết quả, kiểm tra nội dung thông báo và nút quay lại phần Liên hệ.

Form chỉ là bài thực hành: không gửi email và không lưu dữ liệu lên máy chủ. Form dùng phương thức GET nên dữ liệu được nhập có thể xuất hiện trên URL trang kết quả; không nhập thông tin nhạy cảm.

## Nguồn xuất bản và minh chứng

- [Website đang xuất bản trên GitHub Pages](https://linhdam208-hash.github.io/K20_Portfolio_CNTT20_04-/)
- [Mã nguồn trên GitHub](https://github.com/linhdam208-hash/K20_Portfolio_CNTT20_04-)
- [Commit mã nguồn được đối chiếu khi viết tài liệu](https://github.com/linhdam208-hash/K20_Portfolio_CNTT20_04-/commit/95664e6626e443c4dfbb512c1d915c21b4d6971f)
- [Hồ sơ GitHub được trang portfolio hiển thị](https://github.com/damquanglinh)

Repo hiện không có thư mục ảnh chụp màn hình hay minh chứng riêng; các liên kết trên là nguồn kiểm tra trực tiếp.

## Phiên bản bàn giao

Tài liệu này được chuẩn bị theo yêu cầu bàn giao v7. Tuy nhiên, commit mã nguồn hiện được repo ghi nhận là `95664e6626e443c4dfbb512c1d915c21b4d6971f`, có thông điệp “Add initial CSS styles for portfolio version 5”. Chưa có bằng chứng trong lịch sử đã kiểm tra về một commit mã nguồn v7 riêng. Xem [RELEASE_NOTES.md](RELEASE_NOTES.md) để biết phạm vi và hạn chế này.
