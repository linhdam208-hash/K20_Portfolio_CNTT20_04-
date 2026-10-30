# Release notes - Bản bàn giao v7

- **Sản phẩm:** Portfolio CV - Đàm Quang Linh
- **Mã phiên bản bàn giao:** v7 (nhãn theo yêu cầu bàn giao)
- **Ngày cập nhật tài liệu:** 2026-10-30
- **Repo:** [linhdam208-hash/K20_Portfolio_CNTT20_04-](https://github.com/linhdam208-hash/K20_Portfolio_CNTT20_04-)
- **GitHub Pages:** [Mở sản phẩm](https://linhdam208-hash.github.io/K20_Portfolio_CNTT20_04-/)

## Thay đổi chính

- Bổ sung README mô tả sản phẩm, cấu trúc thực tế, cách chạy local và cách kiểm tra các trang/chức năng.
- Ghi lại quá trình AI hỗ trợ soạn tài liệu trong [AI_LOG.md](AI_LOG.md).
- Nêu rõ phạm vi và bản mã được đối chiếu để phục vụ bàn giao.

Không có thay đổi mã ứng dụng được ghi nhận trong bản cập nhật tài liệu này.

## Lỗi đã sửa

Không ghi nhận sửa lỗi HTML/CSS trong lần cập nhật này. README cũ chỉ có mô tả chung, chưa hướng dẫn chạy hoặc kiểm tra sản phẩm; đã được thay bằng hướng dẫn dựa trên nội dung repo hiện tại.

## Commit và bản mã tham chiếu

Commit mã nguồn hiện tại được đối chiếu: [`95664e6626e443c4dfbb512c1d915c21b4d6971f`](https://github.com/linhdam208-hash/K20_Portfolio_CNTT20_04-/commit/95664e6626e443c4dfbb512c1d915c21b4d6971f) trên nhánh `main`. Thông điệp commit là “Add initial CSS styles for portfolio version 5”.

**Lưu ý phiên bản:** v7 ở đây là nhãn của bộ tài liệu bàn giao theo yêu cầu; chưa có bằng chứng về commit hoặc tag mã nguồn v7. Các thay đổi tài liệu hiện tại cũng chưa được commit. Không nên coi commit tham chiếu ở trên là mã v7 nếu chưa xác nhận và cập nhật lịch sử phát hành.

## Hạn chế còn lại

- HTML tham chiếu ảnh trong `assets/`, nhưng các tệp ảnh không có trong repo; ảnh có thể không hiển thị.
- Form liên hệ chỉ là minh họa: xác thực phía trình duyệt và chuyển dữ liệu bằng GET, không gửi email hoặc lưu máy chủ. Dữ liệu nhập có thể lộ trên URL.
- Hồ sơ GitHub trong trang (`damquanglinh`) khác chủ repo (`linhdam208-hash`); cần xác nhận liên kết tác giả trước khi bàn giao chính thức.
- Chưa có kết quả kiểm thử local trong phiên soạn tài liệu.

## Tiếp tục kiểm tra và bàn giao

1. Làm theo hướng dẫn chạy và kiểm tra ở [README.md](README.md); thực hiện kiểm tra trên cả local và Pages.
2. Xác nhận hồ sơ tác giả và bổ sung đúng các tệp ảnh hoặc chỉnh đường dẫn ảnh.
3. Xác nhận mã nguồn nào thực sự là v7; nếu đã có bản mã khác, cập nhật commit/link này theo đúng revision được nộp.
4. Sau khi xác nhận, commit và push các thay đổi tài liệu cùng nhãn/tag phát hành phù hợp. Không tạo tag v7 cho commit v5 nếu chưa xác nhận nội dung mã.
