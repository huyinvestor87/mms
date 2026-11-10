# MMS từ số 0 — MM1, MM7 và lab mini-mmsc

Tài liệu học MMS bằng tiếng Việt cho software engineer: khái niệm, luồng MO/MT, đọc từng byte MM1 (WSP),
MM7 (SOAP 1.1 + MIME), playground JavaScript chạy offline và một lab Java 21 + Maven
(MM1 `M-Send.req` → MMSC → MM7 `DeliverReq` → VASP).

- Đọc online: https://huyinvestor87.github.io/mms/
- Hoặc tải [`mms-explained.html`](mms-explained.html) và mở trực tiếp bằng trình duyệt (`file://`), không cần Internet.

Toàn bộ mã nguồn lab được nhúng trong file HTML: mở mục **7. Lab Java → Full project** để xem, copy,
tải từng file hoặc tải ZIP. Lab cần JDK 21 và Maven; lần build đầu Maven cần Internet để tải plugin.

Mọi số điện thoại trong tài liệu (`+840000001xx`, `+84000000001`) là số giả có chủ ý.
Lab chỉ chạy trên `127.0.0.1`, không gửi gì ra mạng di động thật.

Tham chiếu chính: OMA-MMS-ENC-V1_2-20050301-A, WAP-230-WSP-20010705-a, 3GPP TS 23.140 V6.16.0,
XSD MM7 `REL-6-MM7-1-4`. Mục 8 trong tài liệu ghi kết quả kiểm thử và phần chưa kiểm chứng được.

## Giấy phép

[MIT](LICENSE) — bạn được dùng, sửa và phân phối lại (kể cả thương mại), chỉ cần giữ thông báo bản quyền và giấy phép.
Các đoạn trích ngắn từ đặc tả 3GPP/OMA/WAP và tên chuẩn thuộc về chủ sở hữu tương ứng.
