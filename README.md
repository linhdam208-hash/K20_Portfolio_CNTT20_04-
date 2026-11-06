# PORTFOLIO CV – ĐÀM QUANG LINH

## 1. Giới thiệu sản phẩm

Portfolio CV là website cá nhân được xây dựng bằng HTML và CSS nhằm giới thiệu thông tin cá nhân, kỹ năng, dự án học tập, quá trình học tập và thông tin liên hệ.

Website được thiết kế theo dạng trang web tĩnh, có bố cục rõ ràng, menu điều hướng giữa các nội dung và biểu mẫu liên hệ phục vụ mục đích thực hành.

- **Tên sản phẩm:** Portfolio CV – Đàm Quang Linh
- **Tác giả:** Đàm Quang Linh
- **Lớp:** CNTT 20-04
- **Ngành:** Công nghệ thông tin
- **Trường:** Đại học Đại Nam
- **Ngôn ngữ sử dụng:** HTML, CSS
- **Repository:** https://github.com/linhdam208-hash/K20_Portfolio_CNTT20_04-

## 2. Demo website

**Đường dẫn website GitHub Pages:**

https://linhdam208-hash.github.io/K20_Portfolio_CNTT20_04-/

> Lưu ý: Cần mở đường dẫn trên trình duyệt để xác nhận website hoạt động trước khi bàn giao.

## 3. Các chức năng chính

Website hiện có những nội dung và chức năng sau:

- **Giới thiệu:** Trình bày thông tin tổng quan về tác giả.
- **Kỹ năng:** Giới thiệu các kỹ năng cá nhân.
- **Dự án:** Hiển thị thông tin về các dự án học tập.
- **Học tập:** Trình bày quá trình và thông tin học tập.
- **Liên hệ:** Cung cấp biểu mẫu nhập họ tên, email và lời nhắn.
- **Trang kết quả:** Hiển thị thông báo sau khi gửi biểu mẫu liên hệ.
- **Điều hướng:** Sử dụng menu để di chuyển đến các phần nội dung trên website.

## 4. Cách mở và sử dụng website

### 4.1. Mở website trực tuyến

1. Kết nối Internet.
2. Mở trình duyệt Google Chrome hoặc Microsoft Edge.
3. Truy cập đường dẫn GitHub Pages ở phần Demo website.
4. Chờ website tải hoàn tất.
5. Sử dụng menu để truy cập các phần Giới thiệu, Kỹ năng, Dự án, Học tập và Liên hệ.

### 4.2. Chạy website trên máy tính

Website là sản phẩm tĩnh, không yêu cầu cài đặt thư viện hoặc môi trường backend.

Có thể thực hiện theo các bước:

1. Tải repository về máy tính hoặc sử dụng Git để clone mã nguồn.
2. Mở thư mục dự án bằng Visual Studio Code.
3. Mở Terminal tại thư mục dự án.
4. Chạy lệnh:

```bash
python -m http.server 8000
```

5. Mở trình duyệt và truy cập:

```text
http://localhost:8000
```

6. Nhấn `Ctrl + C` trong Terminal để dừng máy chủ.

## 5. Cấu trúc thư mục dự án

```text
K20_Portfolio_CNTT20_04-/
│
├── index.html
├── ket-qua.html
├── css/
│   └── style.css
│
├── README.md
├── CHANGELOG.md
│
└── docs/
    ├── evidence-index.md
    ├── AI_LOG.md
    └── evidence/
```

**Chức năng các thành phần:**

| Tệp / Thư mục | Mô tả |
|---|---|
| `index.html` | Trang portfolio chính |
| `ket-qua.html` | Trang kết quả của biểu mẫu liên hệ |
| `css/style.css` | Định dạng giao diện và bố cục website |
| `README.md` | Tài liệu giới thiệu và hướng dẫn sử dụng |
| `CHANGELOG.md` | Ghi lại lịch sử thay đổi phiên bản |
| `docs/evidence-index.md` | Danh sách minh chứng kiểm thử |
| `docs/AI_LOG.md` | Nhật ký sử dụng công cụ AI |
| `docs/evidence/` | Lưu ảnh minh chứng bàn giao |

## 6. Kiểm thử và xác minh

Các nội dung cần thực hiện kiểm thử trước khi bàn giao:

| STT | Nội dung kiểm thử | Kết quả |
|---|---|---|
| 1 | Mở website bằng đường dẫn GitHub Pages | Chưa kiểm tra |
| 2 | Kiểm tra menu điều hướng giữa các phần | Chưa kiểm tra |
| 3 | Kiểm tra nút xem dự án | Chưa kiểm tra |
| 4 | Kiểm tra biểu mẫu liên hệ với dữ liệu không hợp lệ | Chưa kiểm tra |
| 5 | Kiểm tra biểu mẫu với dữ liệu hợp lệ và trang kết quả | Chưa kiểm tra |
| 6 | Kiểm tra giao diện trên màn hình điện thoại | Chưa kiểm tra |
| 7 | Kiểm tra hình ảnh và CSS khi mở website | Chưa kiểm tra |

Sau khi thực hiện kiểm thử, cập nhật kết quả thực tế vào bảng và bổ sung minh chứng trong thư mục `docs/evidence/`.

## 7. Hạn chế của sản phẩm

- Website hiện là website tĩnh, chưa có hệ thống quản trị nội dung.
- Biểu mẫu liên hệ chỉ phục vụ mục đích thực hành, không gửi email và không lưu dữ liệu lên máy chủ.
- Biểu mẫu sử dụng phương thức GET nên dữ liệu nhập có thể xuất hiện trên URL trang kết quả. Không nhập thông tin nhạy cảm.
- Các đường dẫn hình ảnh được tham chiếu trong mã nguồn nhưng cần kiểm tra sự tồn tại của thư mục `assets/` và các tệp ảnh tương ứng.
- Cần tiếp tục kiểm thử khả năng hiển thị trên các kích thước màn hình khác nhau.

## 8. Tài liệu và minh chứng bàn giao

Các tài liệu bàn giao được tổ chức như sau:

- `README.md`: Giới thiệu sản phẩm và hướng dẫn sử dụng.
- `CHANGELOG.md`: Ghi nhận các thay đổi của phiên bản bàn giao.
- `docs/evidence-index.md`: Danh mục minh chứng kiểm thử.
- `docs/AI_LOG.md`: Nhật ký sử dụng AI.
- `docs/evidence/`: Lưu ảnh chụp màn hình minh chứng.

## 9. Tuyên bố sử dụng AI

AI được sử dụng để hỗ trợ soạn thảo và rà soát tài liệu bàn giao, gợi ý cách trình bày README, CHANGELOG và danh mục kiểm thử.

Các nội dung liên quan đến mã nguồn, chức năng website và kết quả kiểm thử cần được đối chiếu với sản phẩm thực tế trước khi xác nhận hoàn thành.

Chi tiết việc sử dụng AI được ghi trong tệp `docs/AI_LOG.md`.

## 10. Phiên bản bàn giao

- **Phiên bản tài liệu:** V8
- **Repository:** K20_Portfolio_CNTT20_04-
- **Nhánh làm việc:** main
- **Nền tảng lưu trữ mã nguồn:** GitHub
- **Nền tảng xuất bản website:** GitHub Pages

Việc xác nhận tag `v7`, tag `v8` và mã commit tương ứng sẽ được thực hiện sau khi kiểm tra lịch sử Git thực tế.

---

**Đại học Đại Nam – Khoa Công nghệ thông tin**

*Portfolio CV – Đàm Quang Linh*