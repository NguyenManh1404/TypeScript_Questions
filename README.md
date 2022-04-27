# Câu hỏi quan trọng cần nhớ:

## Câu 1: Khi nào ta biết nên sử dụng OOP vào dự án?
- Các phương pháp lập trình theo hướng như **OOP** hoặc **thủ tục(POP)** thì đều có những ưu điểm và nhược điểm riêng trong khi xây dựng dự án. Cho nên chúng ta phải lựa chọn cho cho phù hợp với mỗi dự án.
- Các teamLeader hoặc đội ngũ công nghệ sẽ phụ trách phân tích dự án và sẽ lựa chọn phương pháp, sau đó các người lập trình sẽ flow theo phương pháp được chọn để phát triển.

- Tiêu chí lựa chọn  **OOP**:

    + Các dự án có nhiều chức năng, các chức năng đó sẽ được phát triển, cập nhật trong tương lai nhờ tính chất kế thừa cho nên sẽ tái sử dụng code tốt.
    + Có yêu cầu tính bảo mật cao bởi vì có tính xác định truy cập là "public", "private", "protected".
    + Yêu cầu dự án rõ ràng đễ dễ dàng bảo trì sau này.

- Tiêu chí lựa chọn **POP**:
    
    + Các dự án có ít chức năng và quy mô nhỏ. Các chức năng không cần phải update thường xuyên.

    + Không có những thông tin, dữ liệu nhạy cảm của người dùng.

## Câu 2: Ưu điểm của TS so với JS?
- Có hiển thị lỗi trực tiếp khi code với thời gian thực, còn Js thì phải chạy lên mới thấy lỗi.
- Có đề xuất code cho lập trình viên những lập trình viên. Điều đó giúp ít rất nhiều cho việc làm việc nhóm.
- Dễ dàng hơn trong phát triển các dự án lớn, được hỗ trợ bởi các Javascript Framwork lớn.
- Hỗ trợ OOP mạnh mẽ bởi vì hầu hết các cú pháp hướng đối tượng đều được hỗ trợ bởi Typescript

## Câu 3: Khi nào thì nên sử dụng TypeScript, khi nào thì sử dụng Javascript trong dự án?
- Bởi vì TypeScript là một phiên bản nâng cấp của JavaScript với nhiều điểm mạnh hơn, cho nên chúng ta nên sử dụng TypeScript thay vì Javascript:
- Tuy nhiên 2 loại này cũng có những ưu điểm và nhược điểm riêng cho nên chúng ta phải lựa chọn cho phù hợp nhất với dự án.

- Tiêu chí chọn **TS**:

    + Xác định đi theo hướng **OOP** 
    + Các dự án lớn bởi vì dự án lớn thì sẽ có rất nhiều thành viên, việc đề xuất code của **TS** sẽ hỗ trợ rất nhiều.
    + Có thời gian làm dài hạn, có sự cập nhật và bảo trì liên tục.

- Tiêu chí lựa chọn **JS**:

    + Xác định theo hướng thủ tục **POP**
    + Các dự án vừa và nhỏ
    + Không có những thông tin user **nhạy cảm**
    + Có thời gian ngắn.
