# AI_LOG - Nhật ký sử dụng AI

## Phạm vi

Nhật ký này ghi lại việc dùng AI để chuẩn bị tài liệu bàn giao trong phiên ngày 2026-10-30; không đại diện cho toàn bộ quá trình phát triển website.

## Hiện tượng và dữ kiện ban đầu

- Yêu cầu ban đầu là tạo/cập nhật `README.md`, `AI_LOG.md` và `RELEASE_NOTES.md` để người khác có thể mở, kiểm tra sản phẩm và bàn giao bản v7.
- Repo có `index.html`, `ket-qua.html`, `css/style.css` và một README ngắn. Không thấy manifest package/build.
- HTML mô tả portfolio của Đàm Quang Linh, có các mục giới thiệu, kỹ năng, dự án, học tập và liên hệ. Form gửi GET tới `ket-qua.html`.
- Repo không có thư mục `assets/`, dù HTML tham chiếu ảnh từ thư mục đó.
- Trang Pages tại `https://linhdam208-hash.github.io/K20_Portfolio_CNTT20_04-/` trả nội dung portfolio khi được mở trong quá trình chuẩn bị.
- Commit mã nguồn hiện tại là `95664e6626e443c4dfbb512c1d915c21b4d6971f`, với thông điệp nhắc đến portfolio version 5; chưa xác minh được commit mã nguồn v7.

## Nhận định trước khi dùng AI

Người dùng chưa cung cấp nội dung riêng về suy nghĩ ban đầu của sinh viên, nên nhật ký không gán một nhận định cá nhân chưa được xác nhận. Nhận định kỹ thuật có thể rút ra từ repo là đây là website portfolio tĩnh; hướng dẫn phải mô tả đúng hành vi form và không được khẳng định ảnh hoặc mã nguồn v7 tồn tại khi chưa có bằng chứng. Tác giả cần bổ sung/chỉnh nhận định cá nhân nếu thực tế khác.

## Công cụ, yêu cầu và gợi ý

- **Công cụ:** Copilot SDK trong VS Code.
- **Yêu cầu đã gửi:** Tạo ba tài liệu bàn giao tiếng Việt; README cần nêu sản phẩm, repo/Pages, cấu trúc, chạy local và cách kiểm tra; AI log cần minh bạch quá trình dùng AI; release notes cần mô tả bản v7 và dẫn đúng bản mã.
- **Gợi ý/ phản hồi AI trong phiên:** Đọc mã nguồn và lịch sử repo trước khi viết; dùng lệnh server tĩnh cho website không có bước build; ghi rõ form chỉ chuyển trang, không gửi/lưu dữ liệu; chỉ nêu URL Pages đã kiểm tra; phân biệt nhãn bàn giao v7 với commit mã nguồn hiện tại; công khai thư mục ảnh còn thiếu và sự khác nhau giữa hai tài khoản GitHub xuất hiện trong repo/trang.

## Quyết định và lý do

Trong phạm vi phiên này, chọn cập nhật README hiện có và thêm hai tài liệu còn thiếu. Không sửa HTML/CSS vì yêu cầu tập trung vào tài liệu; không ghi rằng form gửi email, ảnh đã có, hay mã nguồn đã được nâng lên v7. Ghi rõ các điểm chưa khớp để người bàn giao có thể xác minh thay vì biến chúng thành kết quả đã hoàn thành.

## Phần đã sửa

- `README.md`: thay nội dung ngắn bằng hướng dẫn theo cấu trúc, chức năng và trạng thái thực tế của repo.
- `AI_LOG.md`: ghi rõ dữ kiện, phạm vi AI, quyết định và những gì chưa được kiểm tra.
- `RELEASE_NOTES.md`: ghi nhãn bàn giao v7 nhưng liên kết tới commit mã nguồn đã xác minh, không tự nhận commit đó là v7.

## Thử lại và kết quả

- **Đã kiểm tra:** đọc các tệp HTML/CSS, danh sách tệp trong repo, commit hiện tại và mở URL Pages. Trang Pages trả nội dung; repo thiếu ảnh được HTML tham chiếu; form đặt `action="ket-qua.html"` và `method="get"`.
- **Chưa thực hiện:** chưa chạy website qua server local, chưa gửi thử form trong trình duyệt và chưa kiểm tra ảnh bằng trình duyệt. Do đó đây là hướng dẫn kiểm tra đề xuất, không phải kết quả thử nghiệm đã hoàn tất.
- **Cách thử tiếp:** chạy `py -m http.server 8000` ở thư mục repo, mở `http://localhost:8000`, thử các mục điều hướng và gửi form với dữ liệu sai/hợp lệ theo các giới hạn trong README. So sánh kết quả local với Pages; bổ sung ảnh hoặc cập nhật đường dẫn sau khi có các tệp ảnh thực tế.
