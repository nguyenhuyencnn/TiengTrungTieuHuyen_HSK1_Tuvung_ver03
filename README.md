# Từ vựng HSK1 – Tiếng Trung Tiểu Huyền

Website học 500 từ vựng HSK1 (chuẩn HSK 3.0): 20 bài học (mỗi bài 25 từ) gồm thẻ từ, luyện tập 5 dạng bài, ghép từ và kiểm tra cuối bài; 1011 câu ví dụ có pinyin và bản dịch; phát âm; hoạt ảnh thứ tự nét; lọc theo từ loại; theo dõi tiến độ từng học sinh và bảng tổng hợp cho giáo viên.

Toàn bộ trang nằm trong một file `index.html` (đã nhúng sẵn âm thanh, dữ liệu nét và thư viện hoạt ảnh).

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub (ví dụ `hsk1-tu-vung`), chọn **Public**.
2. Bấm **Add file → Upload files**, kéo thả toàn bộ nội dung thư mục này (gồm `index.html`, `README.md`, `.nojekyll`, thư mục `data`), rồi bấm **Commit changes**.
3. Vào **Settings → Pages**, mục *Build and deployment* chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, bấm **Save**.
4. Sau 1–2 phút, trang có địa chỉ dạng `https://<tên-tài-khoản>.github.io/hsk1-tu-vung/`.

Lưu ý: file `.nojekyll` bắt đầu bằng dấu chấm nên có thể bị ẩn trên máy; trang vẫn chạy được nếu thiếu file này.

## Phụ thuộc bên ngoài

- Phông chữ tải từ Google Fonts; khi không có mạng, trang dùng phông hệ thống.
- Nút “giọng máy” dùng giọng đọc tổng hợp có sẵn trên thiết bị (cần giọng tiếng Trung).
- Âm thanh người thật, dữ liệu nét và thư viện Hanzi Writer đã nhúng trong `index.html`.
- Website không có máy chủ: tên học sinh và kết quả học lưu trên trình duyệt của từng thiết bị.

## Luyện nói (micro)

- Mỗi bài có bước **5. Luyện nói**; mỗi thẻ từ có nút **Luyện nói**. Học sinh bấm micro, đọc từ, máy chấm điểm 0–100 và vẽ đường cao độ giọng em so với giọng mẫu.
- Cách chấm: so đường cao độ (thanh điệu) với bản ghi người bản ngữ; nếu trình duyệt có nhận dạng giọng nói tiếng Trung (thường Chrome/Edge) thì kiểm tra thêm đọc đúng từ (điểm = 50% thanh điệu + 50% đúng từ). Điểm chỉ để tham khảo.
- Cần mở trang qua https (GitHub Pages) và cho phép micro. Chỉ áp dụng cho các từ có bản ghi người thật.

## Theo dõi tiến độ học sinh

1. Học sinh mở trang, nhập **họ tên, lớp** (và mã học viên nếu có) để vào học.
2. Kết quả luyện tập, ghép từ, kiểm tra được lưu trên máy của học sinh, xem ở mục **Tiến độ**.
3. Để giáo viên xem: học sinh bấm **Tạo tệp kết quả** (tệp `.json`) và gửi cho giáo viên qua Zalo/email.
4. Giáo viên mở mục **Giáo viên**, chọn **Chọn tệp .json** (chọn nhiều tệp một lúc) để xem bảng cả lớp, lọc theo lớp, xem chi tiết từng học sinh, từ cả lớp hay sai, và **xuất CSV**.

Giới hạn: dữ liệu không tự đồng bộ giữa các thiết bị, có thể mất nếu xóa dữ liệu trình duyệt; mục Giáo viên không có mật khẩu. Muốn đồng bộ tự động cần thêm máy chủ/cơ sở dữ liệu (ví dụ Google Sheets, Firebase).

## Giấy phép tài nguyên bên thứ ba

- Âm thanh người thật: Shtooka – giọng Yue Tan, giấy phép CC BY-SA (cần giữ dòng ghi công này khi đăng công khai).
- Dữ liệu nét chữ: Make Me a Hanzi – Arphic Public License (`data/LICENSE-stroke-data-ARPHICPL.txt`).
- Thư viện hoạt ảnh: Hanzi Writer – MIT (`data/LICENSE-hanzi-writer.txt`).

© Tiếng Trung Tiểu Huyền.
