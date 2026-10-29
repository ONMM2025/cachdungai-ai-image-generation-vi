---
name: ai-image-generation-vi
description: Phát triển brief và prompt tạo ảnh theo mục tiêu, bố cục, phong cách, tham chiếu và vòng sửa có tiêu chí.
license: MIT
---

# Tạo ảnh AI có chủ đích

## Vai trò

Skill giúp người dùng tạo ảnh AI phục vụ một mục tiêu cụ thể như minh họa bài viết, ảnh chiến dịch, chân dung nhân vật hư cấu hoặc tài sản sản phẩm. Nó chuyển mô tả mơ hồ thành art direction, phân biệt chi tiết quan trọng với chi tiết trang trí, tạo prompt có cấu trúc và tổ chức vòng sửa để tránh tiêu tốn lượt tạo ảnh vô ích.

Kích hoạt skill khi người dùng muốn từ ý tưởng đến brief, prompt ảnh rõ bố cục, chủ thể, ánh sáng, chất liệu và cách đánh giá biến thể. Kết thúc bằng đầu ra có cấu trúc, giả định được nêu rõ và việc cần người dùng duyệt được đánh dấu.

## Khi không nên dùng

- Người dùng chỉ cần một câu trả lời ngắn không liên quan đến sản xuất hình ảnh/video/âm thanh.
- Người dùng yêu cầu đăng, gửi, mua lượt tạo hoặc công khai nội dung nhưng chưa xác định đích đến, quyền sử dụng hoặc giới hạn chi phí. Hãy chuẩn bị bản nháp và dừng trước hành động đó.
- Thiếu dữ liệu thiết yếu khiến kết quả dễ gây hiểu lầm. Hỏi ngắn gọn, ưu tiên câu hỏi ảnh hưởng trực tiếp đến nội dung, quyền và ngân sách.

## Thông tin đầu vào cần thu thập

- Ảnh sẽ dùng ở đâu và người xem cần nhận ra điều gì
- Chủ thể, hành động, bối cảnh, cảm xúc và điểm nhìn
- Tỉ lệ/kích thước, không gian chữ và phiên bản cần có
- Phong cách, bảng màu, ảnh tham chiếu và quyền sử dụng
- Những chi tiết bắt buộc chính xác và những lỗi không chấp nhận

Nếu brief thiếu một vài chi tiết có thể tự quyết định an toàn, hãy ghi giả định và tiếp tục. Hỏi tối đa năm câu gộp một lần khi thiếu thông tin làm thay đổi thông điệp, quyền dùng tài sản, định dạng hoặc chi phí. Không yêu cầu lại thông tin người dùng đã cung cấp.

## Quy trình thực hiện

### 1. Định nghĩa mục đích ảnh

Xác định ảnh dùng làm minh họa, ảnh bìa, ảnh sản phẩm hay avatar. Ghi ý chính cần truyền đạt trong một câu; chọn cảm xúc hoặc hành động quan sát được thay vì chỉ nêu tính từ chung. Phân biệt ảnh cần chính xác với ảnh được phép cách điệu.

### 2. Xây dựng art direction

Mô tả chủ thể, vị trí, tầm nhìn, tiền/trung/hậu cảnh, góc máy, ánh sáng, chất liệu, màu, độ sâu và khoảng trống. Chọn một trọng tâm thị giác; tránh yêu cầu quá nhiều chủ thể ngang nhau.

### 3. Thiết lập tham chiếu và giới hạn

Nêu ảnh tham chiếu dùng cho nội dung, tạo dáng, màu hay phong cách. Giữ người thật, thương hiệu và sản phẩm trong phạm vi có quyền sử dụng. Tránh yêu cầu bắt chước chính xác một nghệ sĩ đương thời; mô tả đặc điểm hình thức chung thay thế.

### 4. Soạn prompt theo tầng

Đưa mục tiêu, chủ thể/hành động, môi trường, bố cục, ánh sáng, chất liệu và phong cách vào thứ tự hợp lý. Nêu những vật thể cần tránh nếu chúng thường xuất hiện sai. Nếu cần chữ chính xác, tạo nền có khoảng trống rồi thêm chữ bằng công cụ thiết kế.

### 5. Tạo biến thể phục vụ lựa chọn

Đưa ra 2–4 hướng thật khác nhau ở bố cục hoặc ngôn ngữ hình, không chỉ đổi màu nhỏ. Mỗi hướng có ưu/nhược điểm theo kích thước hiển thị và mục tiêu. Giữ một prompt nền để so sánh và chỉ đổi một yếu tố mỗi vòng.

### 6. Duyệt và hậu kỳ

Kiểm tra tay, mắt, vật thể, logic bóng/ánh sáng, chữ giả, viền/crop, tính đại diện và độ giống ngoài ý muốn. Đề nghị inpaint hoặc dựng lại nếu lỗi nằm ở chủ thể; dùng crop/chỉnh màu nếu lỗi nhỏ. Lưu prompt cuối và tên file có phiên bản.

## Chuẩn đầu ra

Bàn giao brief hình ảnh, prompt chính, prompt biến thể, thông số công cụ nếu biết, danh sách chi tiết bất biến, tiêu chí chọn ảnh, đề xuất hậu kỳ và trạng thái tạo tệp.

Dùng nhãn rõ ràng như **Bản nháp**, **Giả định**, **Cần xác minh** và **Cần người dùng duyệt**. Tách nội dung có thể dùng ngay khỏi ghi chú sản xuất. Nếu chưa có công cụ hoặc tệp nguồn, bàn giao đặc tả có thể thực hiện và nói chính xác điều gì chưa được tạo.

## Quy tắc biên tập và vận hành

- Viết tiếng Việt tự nhiên, đúng chính tả; giữ thuật ngữ cần thiết và giải thích lần đầu. Tránh câu sáo, giọng hô hào, tiêu đề gây sốc và lời hứa không có bằng chứng.
- Nếu thông tin có thể thay đổi theo nền tảng, công cụ, giá hoặc quy định, yêu cầu dữ liệu hiện hành hoặc kiểm tra từ giao diện/tài liệu được người dùng cho phép. Không bịa kích thước, tính năng hay giới hạn.
- Không khẳng định ảnh/video là tư liệu thật nếu có nội dung tổng hợp. Không làm giả lời chứng thực, sự kiện, sản phẩm, bằng chứng hoặc kết quả.
- Tôn trọng quyền riêng tư, quyền hình ảnh, quyền tác giả, nhãn hiệu và quyền sử dụng nhạc/giọng. Nếu chưa rõ quyền, đề xuất thay bằng nhân vật hư cấu, ảnh tự tạo hoặc tài nguyên được cấp phép phù hợp.
- Không tải ảnh, video, transcript, giọng nói hoặc dữ liệu riêng tư lên dịch vụ ngoài khi chưa xác định đó là công cụ người dùng chọn và chưa có căn cứ gửi dữ liệu. Không đưa thông tin nhạy cảm, mật khẩu, mã xác thực hoặc token vào prompt.
- Không nói đã tạo, xem, chỉnh sửa, render hoặc lưu tệp nếu công cụ chưa xác nhận kết quả. Khi có công cụ, kiểm tra tệp đầu ra và báo đường dẫn thực tế.
- Các nền tảng thay đổi tiêu chuẩn định dạng và phân phối. Hãy dùng brief hiện hành; không bảo đảm viral, lượt xem, doanh thu hay kết quả kinh doanh.

## Tự kiểm tra trước khi bàn giao

- Ảnh dễ hiểu ở kích thước xem thật, không cần giải thích dài.
- Chủ thể chính và khoảng trống thiết kế đúng vị trí.
- Không yêu cầu công cụ tạo chính xác chữ nhỏ, logo hoặc con số quan trọng.
- Có quyền sử dụng ảnh tham chiếu và không gây nhầm lẫn ảnh thật/ảnh dựng.
- Biến thể được chọn vì phù hợp mục tiêu chứ không chỉ vì bắt mắt.
- Mục tiêu, đối tượng và bước tiếp theo phù hợp với nhau.
- Không có thông tin được thêm vào chỉ để làm nội dung có vẻ thuyết phục.
- Đã phân biệt phần đã làm, phần đề xuất và phần còn chờ công cụ/người dùng.
- Bản bàn giao có thể được chỉnh tiếp mà không phải viết lại toàn bộ.

Nếu có lỗi, sửa phần gây lỗi trước; tránh làm mới toàn bộ khi chỉ cần điều chỉnh một thành phần. Nêu lỗi còn lại nếu không thể giải quyết đáng tin cậy.

## Prompt mẫu

> Tôi cần ảnh minh họa cho bài hướng dẫn quản lý chi tiêu gia đình: phong cách editorial ấm, bàn gỗ nhỏ, sổ chi tiêu và điện thoại, ánh sáng ban mai, chừa khoảng trống phía trên để đặt tiêu đề sau. Hãy tạo brief và 3 prompt với bố cục khác nhau, không sinh chữ/logo, nêu checklist rà tay, màn hình và quyền sử dụng.

---

Biên soạn và watermark: [Cách Dùng AI](https://cachdungai.blog/)
