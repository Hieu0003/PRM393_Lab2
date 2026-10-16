# Persona

## Thông tin chung

- **Tên:** Minh
- **Tuổi:** 20
- **Nghề nghiệp:** Sinh viên năm 2
- **Thiết bị:** Điện thoại Android, thường dùng một tay khi di chuyển giữa các buổi học
- **Thói quen:** Hay mượn sách tham khảo ở thư viện trường, thường tranh thủ tra cứu giữa các tiết học

## Bối cảnh

Minh cần mượn giáo trình và sách tham khảo cho các môn học. Thời gian rảnh của Minh ngắn và rải rác trong ngày, nên bạn thường tra cứu sách trên điện thoại khi đang đi bộ hoặc chờ vào lớp. Hiện nay muốn biết sách còn hay hết, Minh phải đến thư viện hỏi thủ thư.

## Mục tiêu

- Tìm đúng cuốn sách cần mượn một cách nhanh chóng
- Biết ngay sách còn hay đã hết trước khi đến thư viện
- Đặt mượn sách ngay trên điện thoại
- Theo dõi hạn trả và gia hạn khi cần để không bị phạt

## Pain points

1. Không biết sách còn hay đã hết, mất công đến thư viện mới biết.
2. Quên hạn trả sách vì không có nhắc nhở rõ ràng, dẫn đến bị phạt.
3. Không rõ sách có gia hạn được không và còn mấy lượt gia hạn.
4. Phải hỏi trực tiếp thủ thư cho các việc nhỏ như tìm sách hay xem hạn trả.
5. Khi thao tác một tay trên điện thoại, các nút nhỏ hoặc xa tầm ngón cái rất khó bấm.

## Problem statement

Minh là sinh viên cần tìm, đặt mượn và theo dõi hạn trả sách nhanh ngay trên điện thoại, vì hiện tại bạn phải đến thư viện hỏi thủ thư, hay quên hạn trả và không biết sách có gia hạn được hay không.

## Chỉ số thành công (đo được)

Các chỉ số dưới đây là mục tiêu đề xuất, sẽ được kiểm tra khi chạy thử prototype với một vài người dùng. Nhóm điều chỉnh số liệu cho phù hợp.

| Chỉ số | Mục tiêu | Cách đo |
|---|---|---|
| Số bước từ Trang chủ đến khi đặt mượn xong | Tối đa 5 bước | Đếm số lần bấm khi chạy flow Đặt mượn trong prototype |
| Thời gian tìm được một cuốn sách và xem tình trạng | Dưới 30 giây | Bấm giờ khi người thử làm flow Tìm sách |
| Hạn trả sách hiển thị | Thấy ngay ở Trang chủ, không cần mở thêm màn hình | Kiểm tra trực tiếp trên Final UI |
| Tỷ lệ người thử hoàn thành cả 3 flow không cần hướng dẫn | Từ 4/5 người trở lên | Cho 5 bạn chạy thử prototype và ghi lại |
| Gia hạn sách | Biết rõ còn bao nhiêu lượt gia hạn trước khi bấm | Kiểm tra trên màn Gia hạn hoặc trả sách |

## Liên hệ với thiết kế

- Persona dùng một tay nên thanh điều hướng đặt phía dưới màn hình, nút chính nằm trong tầm ngón cái.
- Persona hay quên hạn trả nên thẻ "Sắp đến hạn" hiển thị ngay ở Trang chủ.
- Persona cần biết trạng thái sách trước khi đi nên màn Chi tiết sách hiển thị rõ còn sách hay hết sách.
