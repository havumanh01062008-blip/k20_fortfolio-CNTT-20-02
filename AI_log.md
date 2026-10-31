# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Hà Vũ Mạnh ]
- Mã sinh viên – Lớp: [ 20-02 ]
- Ngày thực hiện: [ 3010/2026 ]
- Link repository: [ https://github.com/havumanh01062008-blip/K20-fortfolio_CNTT-20-02 ]
- URL website: [  https://havumanh01062008-blip.github.io/K20-fortfolio_CNTT-20-02/]
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ Trang chủ (index.html) phần tiêu đề và bố cục bị lệch hẳn sang một bên, các thẻ bên dưới hiển thị sai định dạng  ]
- Mong muốn và hiện tượng thực tế: [ Mong muốn trang web hiển thị đúng cấu trúc các khối như đã học. Thực tế là thanh điều khiển bị tràn ra ngoài và chữ không xuống dòng đúng chỗ. ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [  Đã mở file index.html nhưng chưa tìm ra chỗ sai vì mã nguồn khá dài và nhiều thẻ lồng nhau. Không thấy thông báo lỗi đỏ trong Console của trình duyệt. ]
- Tôi nghi nguyên nhân là: [ Có thể viết nhầm hoặc quên đóng thẻ HTML nào đó  ]
- Vì sao tôi nhận định như vậy: [ Tôi vừa mới copy một đoạn code trên mạng dán vào nhưng quên kiểm tra lại các thẻ mở và thẻ đóng  ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ Chat GPT ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [  Xem giúp tôi lỗi ở ảnh này và sửa lại ]

- Gợi ý chính của AI:

  [ ... ]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ làm lại phần của AI gợi ý ]
- Lý do, dựa trên dữ kiện nào: [ dựa vào đúng mình thiếu và sửa theo thử như AI gợi ý và thành công. ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ index.html ]
- Nội dung thay đổi hoặc cách xử lý khác: [ Bổ sung thêm thẻ </div> còn thiếu để đóng khối container. ]
- Commit của bản sửa, nếu có: [ ... ]
- Bản sửa đã deploy: [x] Có  [ ] Chưa  [ ] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [ Không kiểm tra  ] | [ Không kiểm tra ] |
| Giao diện/chức năng trên URL website | [ Giao diện bị vỡ ] | [ Giao diện hiển thị đúng ] |

- Cách thử lại và kết quả thực tế: [ Lưu file, chạy lại Live Server trên máy tính thấy giao ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ Quan sát trực quan trên trình duyệt thấy các khối div đã nằm đúng vị trí cân đối ]

## 5. Kết luận

- [x] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [ Khi viết code HTML, cần chú ý format code và kiểm tra kỹ các thẻ mở/đóng để tránh lỗi vỡ giao diện âm thầm không báo đỏ ở Console. ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
