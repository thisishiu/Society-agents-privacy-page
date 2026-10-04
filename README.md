# Privacy page

Trang HTML/CSS tĩnh, không cần cài thư viện hoặc chạy build.

## Trước khi công khai

- Điền tất cả nội dung trong dấu `[...]` ở `index.html` theo dữ liệu và hoạt động thực tế của app.
- Kiểm tra email liên hệ `hqhz12345z@gmail.com` và ngày cập nhật.
- Xóa khối `draft-note` sau khi hoàn tất nội dung.

## GitHub Pages

Cách đơn giản: đẩy **nội dung** thư mục này (`index.html`, `styles.css`) vào thư mục gốc của một repository riêng. Trong **Settings → Pages**, chọn **Deploy from a branch**, chọn nhánh chứa các file và thư mục **/(root)** rồi lưu.

Nếu giữ `privacy-page/` trong repository hiện tại, xuất bản thư mục gốc của repository; trang này sẽ nằm tại `https://<username>.github.io/<repository>/privacy-page/`.

Dùng URL công khai của trang cho trường **Privacy policy URL** trong cấu hình app. Liên kết tới phần hướng dẫn yêu cầu xóa dữ liệu là URL trang cộng thêm `#rights`.

Mở `index.html` bằng trình duyệt để xem trước. Trang dùng đường dẫn CSS tương đối nên có thể chạy ở cả thư mục gốc và thư mục con.
