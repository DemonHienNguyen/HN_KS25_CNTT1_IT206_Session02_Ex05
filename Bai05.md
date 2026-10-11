
## Phần 1: Kiến trúc mô hình

1. Phạm vi và nguyên tắc thiết kế

Phần mềm đang áp dụng 1 khung vận hành  Agile chung cho cả 3 đội nhưng cho phép lựa chọn cách thực hiện phù hợp với đặc thù công việc. Đội đặt xe và đội thanh toán sử dụng Scrum để thích nghi nhanh với nhu cầu thị trường; đội đối soát vẫn có thể tham gia khugn quản trị chung nhưng vẫn có thể vận hành thanh Waterfall có thể kiểm soát thay đổi

Mô hình được xây dụng dựa trên bốn giá trị Agilem ba trụ cột Scrum, ba vai trò, ba tạo tác và năm sự kiện Scrum, bảo đẩm không biến Aglie thành việc tổ chức họp theo hình thức

2. Các Module quy trình và trách nhiệm

| Module                              | Nội dung vận hành                                                                                                           | Người chịu trách nhiệm chính                                           |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| Quản lý nhu cầu                  | Thu thập phản hồi người dùng, xác định vấn đề                                                                     | Product Owner                                                                |
| Lập kế hoạch và cam kết Sprint | Chọn mục tiêu Sprint, xác định hạng mục có thể hoàn thành và lập kế hoạch thực hiện                          | PO và Developers                                                            |
| Phát triển và kiểm thử         | Thiết kế, lập trình, kiểm thử, tích hợp vafbaor đảm chất lượng theo DoD                                           | Developers                                                                   |
| Kiểm soát và tuần thủ          | Kiểm tra yêu cầu thuế, Quản lý tài liệu, truy vết thay đổi và xác nhận tính chính xác trước khi phát hành | Người phụ trách nghiệp vụ tuân thủ và nhám thực hiện đối soát |
| Cải tiến quy trình               | Phân tích điểm nghẽn, sai sót và cách phối hợp; thống nhất hành động cải tiến có thể kiểm chứng           | Scrum Master và các thành viên đội                                     |
| Quản lý phát hành và rủi ro   | Kiểm soát điều kiện phát hành, xử lý thay đổi khuẩn cáo và theo dõi rủi ro vận hành                          | Product Owner                                                                |

Các trách nhiệm trên được phân biệt rõ:

PO chịu trách nhiệm tối đa hóa giá trị và quản lý thứ tự ưu tiên; Scrum Master chịu trách nhiệm hỗ trợ Scrum được hiểu và thực hiện đúng.

Developers tự tổ chức công việc để tạo ra sản phẩm đạt chất lượng

Người phụ trách tuân thủ có quyền xác nhận các điều kiện nghiệp vụ bắt buộc theo quy định, nhung không thay thế trách nhiệm của PO hay Developers

3. Bốn giá trị Agile và ba trụ cột Scrum

Bốn giá trị Agile được áp dụng trong vận hành:

	+ Cá nhân và sự tương tác hơn quy trình và công cụ: Thành  viên chủ động trao đổi để giải quyết vấn đề, không chỉ àm theo thủ tục

	+ Phần mềm chạy tốt hơn tài liệu đầy đủ: Ưu tiên sản phẩm hoạt động và được kiểm chứng, đồng thời vẫn duy trì tài liệu bắt buộc đối với hóa đơn điện tử

	+ Cộng tác với khách hàng hơn đàm phán hợp đồng: PO và đợi phát triển thường xuyên xác nhận nhu cầu, đặc biệt với tính năng Đặt xe và Thanh toán

	+ Đpá ứng thay đổi hơn bám sát kế hoạch: Điều chỉnh ưu tiên khi thị trường hoặc luật thuế thay đổi, nhưng không bỏ qua kiểm soát tuân thủ

Ba trụ cột Scrum:

	+ Minh bạch: Coogn khai trạng thái công việc, tiêu chí hoàn thành, chất lượng và rủi ro

	+ Thanh tra: Kiểm tra sản phẩm và tiến độ thường xuyên để phát hiện được sai lệch

	+  Thích nghi: Điều chỉnh kế hoạch hoặc quy định ngay khi phát hiện vấn d dề, thay vì chờ đến cuối dự án

4. Ba vai trò, ba tạo tác và 5 sự kiện Scrum

Ba vai trò

| Vai trò      | Trách nhiệm                                                                                             |
| ------------- | --------------------------------------------------------------------------------------------------------- |
| Product Owner | Chịu trách nhiệm tối đa hóa giá trị  sản phẩm và quản lý thứ tự ưu tiên Product Backlog |
| Scrum Master  | Hướng dẫn Scrum, hỗ trợ loại bỏ trở ngại và thúc đẩy cải tiến                              |
| Developers    | Tổ chúc phát triển, kiểm thử và tạo ra Incremnent đáp ứng được DoD                          |

Ba tạo tác

+ Product Backlog: Danh sách nhu cầu, tính năng, lỗi và thay đổi cần thực hiện
+ Sprint Backlog: Mục tiêu Sprint, các hạng mục đã chọn và kế hoạch thực hiện
+ Increment: Phân sản phẩm đã hoàn thành, tích hợp và đáp ứng được DoD

Năm sự kiện Scrum:

| Sự kiện            | Mục đích                                                                                           |
| -------------------- | ----------------------------------------------------------------------------------------------------- |
| Sprint               | Chu kỳ tối đa một tháng, trong mô hình này là 2 tuần, để tạo Increment có giá trị     |
| Sprint Planning      | Xác ddingj vì sao Sprint có giá trị, sẽ làm gì và thực hiện như thê snaof                |
| Daily Scrum          | Developers kiểm tra tiến độ hướng tới Sprint Goal và điều chỉnh kế hoạch hằng ngày     |
| Sprint Review        | Kiể tra keests quả với các bên liên quan, thảo luận thay đổi và cập nhật Product Backlog |
| Sprint Retrospective | Đánh giá cách làm việc và thống nhất cải tiến cho Sprint tiếp theo                        |

5. Luồng giá trị từ nhu cầu đến cải tiến

được vẽ trong hay.drawio

## Phần 2: Xử lý tình huống ngoài dự kiến

Tình huống 1: Đến Sprint Review nhưng không có hạng mục nào đạt DoD

| Tiêu chí           | Nội dung                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Phát hiện ở đâu | Tại Sprint Review, kiểm tra Increment và đối chiếu từng hạng mục với DoD                                                                                                                                                                                                                                                                                                 |
| Ai xử lý           | Developers giải thích trạng thái và nguyên nhân; PO đánh giá tác động đến giá trị và cập nhật Product Backlog ; Scrum Master hỗ trợ xử lý trở ngại và bảo đảm sự kiện được thực hiện đúng tinh thần Scrum                                                                                                                                 |
| Xử lý thế nào    | Không công nhận các hạng mục chưa đạt là hoàn thanh , không phát hành chúng như Increment đạt chuẩn và không che giấy kết quả. Những hạng mục chưa xong được dadnhs giá lại và đưa về Product Backlog để PO sắp xếp ưu tiên; tại Sprint Retrospective, đội phân tích nguyên nahan và chọn hành động để cải tiến cụ thể |

Tình huống 2: Đội thanh toán muốn kéo dài Sprint thêm một tuần

| Tiêu chí           | Nội dung                                                                                                                                                                                                                                                                                                                   |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Phát hiện ở đâu | Tại Sprint Planning và trong quá trình theo dõi Sprint, đội đã thống nhát lịch kết thúc cố định; đề nghị kéo dài được xử lý như một rủi ro về phạm vi và khả năng hoàn thành Sprint Goal                                                                                               |
| Ai xử lý           | Developers đánh giá nguyên nhân và phương án kỹ thuật; PO quyết định thứ tự ưu tiên sản phẩm                                                                                                                                                                                                            |
| Xử lý thế nào    | Không kéo dài riêng Sprint đang chạy chỉ để hoàn thành thêm việc, Đội kết thúc Sprint đúng hạn, đánh giá Increment thực tế, đưa phần chưa hoàn thành trở lại Product Backlog để PO sắp xếp lại rồi lập kế hoạch Sprint tiếp theo dựa vào năng lực và bài học vừa rút ra |
