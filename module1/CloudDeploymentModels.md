# Các mô hình triển khai đám mây

[Link gốc](https://www.google.com/search?client=ubuntu&channel=fs&q=translate&ie=utf-8&oe=utf-8)

Có ba mô hình triển khai đám mây khác nhau. Mô hình triển khai đám mây xác định nơi dữ liệu của bạn được lưu trữ và cách khách hàng của bạn tương tác với nó - làm thế nào để họ truy cập vào đó và ứng dụng chạy ở đâu? Nó cũng phụ thuộc vào số lượng cơ sở hạ tầng bạn muốn hoặc cần quản lý cho riêng bạn.

## Khám phá ba phương thức triển khai của cloud computing

### Public vs Private vs Hybrid

#### Public cloud - Đám mây công cộng

Đây là mô hình triển khai phổ biến nhất. Trong trường hợp này, bạn không có phần cứng  để quản lý hoặc cập nhật - mọi thứ chạy trên local hardware (phần cứng cục bộ) của nhà cung cấp đám mây cho bạn. Trong vài trường hợp, bạn có thể tiết kiệm chi phí phát sinh bằng cách chia sẻ tài nguyên điện toán với những người dùng đám mây khác.

Các doanh nghiệp có thể sử dụng nhiều nhà cung cấp đám mây công cộng với quy mô khác nhau. Microsoft Azure là một ví dụ về nhà cung cấp public cloud.

##### Ưu điểm

* Khả năng mở rộng / nhanh nhẹn - bạn không phải mua máy chủ mới để mở rộng quy mô
* Đơn giá pay-as-you-go (dùng bao nhiêu trả bấy nhiêu) - bạn chỉ trả cho những gì bạn sử dụng, không có chi phí CapEx
* Bạn không chịu trách nhiệm bảo trì hoặc cập nhật phần cứng
* Kiến thức kỹ thuật để thiết lập và sử dụng ở mức tối thiểu- bạn có thể tận dụng các kỹ năng và chuyên môn của nhà cung cấp đám mây để đảm bảo khối lượng công việc được bảo đảm, an toàn và khả dụng cao

Một use case scenario (trường hợp dùng) phổ biến là triển khai ứng dụng web hoặc một trang blog trên phần cứng và tài nguyên thuộc sở hữu của nhà cung cấp đám mây. Sử dụng đám mây công cộng trong trường hợp này cho phép người dùng đám mây nhanh chóng truy cập trang web hoặc blog của họ rồi tập trung vào việc duy trì trang web mà không phải lo lắng về việc mua, quản lý hoặc bảo trì phần cứng để nó chạy.

##### Nhược điểm

Không phải tất cả các trường hợp phù hợp với public cloud. Dưới đây là một số nhược điểm cần suy nghĩ:
* Có thể có các yêu cầu bảo mật cụ thể không thể đáp ứng được khi dùng public cloud
* Có thể có chính sách của chính phủ, tiêu chuẩn ngành hoặc yêu cầu pháp lý mà public cloud không thể đáp ứng
* Bạn không sở hữu phần cứng hoặc dịch vụ nên không thể quản lý chúng như cách bạn muốn
* Các yêu cầu kinh doanh cá biệt, chẳng hạn như phải duy trì một ứng dụng cổ có thể khó được đáp ứng

#### Private cloud - Đám mây riêng

Trong private cloud, bạn tạo một môi trường đám mây trong trung tâm dữ liệu của riêng bạn và cung cấp quyền truy cập tự phục vụ để tính toán tài nguyên cho người dùng trong tổ chức. Điều này cung cấp mô phỏng đám mây công khai cho người dùng của bạn, nhưng bạn vẫn hoàn toàn chịu trách nhiệm cho việc mua và bảo trì các dịch vụ phần cứng và phần mềm bạn cung cấp.

##### Ưu điểm

Cách tiếp cận này có một số ưu điểm:
* Bạn có thể đảm bảo cấu hình có thể hỗ trợ bất kỳ trường hợp hoặc ứng dụng cổ
* Bạn có quyền kiểm soát (và trách nhiệm) đối với bảo mật
* Private clouds có thể đáp ứng các yêu cầu nghiêm ngặt về bảo mật, tuân thủ hoặc pháp lý

##### Nhược điểm

Một số lý do các đội di chuyển khỏi private cloud là:
* Bạn tốn một số chi phí CapEx ban đầu và phải mua phần cứng để khởi động và bảo trì
* Việc sở hữu thiết bị giới hạn sự nhanh nhẹn - để mở rộng quy mô, bạn phải mua, cài đặt và thiết lập phần cứng mới
* Private clouds đòi hỏi các kỹ năng và chuyên môn về CNTT khó có thể đạt được

Một use case scenario cho private cloud sẽ là khi một tổ chức có dữ liệu không thể đưa vào public cloud, có lẽ vì lý do pháp lý. Một trường hợp ví dụ có thể là khi chính sách của chính phủ yêu cầu dữ liệu cụ thể được lưu giữ trong nước hoặc tư nhân.

Một private cloud cũng có thể cung cấp chức năng đám mây cho khách hàng bên ngoài hoặc cho các bộ phận nội bộ cụ thể như Kế toán hoặc Nhân sự.

#### Hybrid cloud - Đám mây lai

Một hybrid cloud kết hợp các public và private clouds, cho phép bạn chạy các ứng dụng của mình ở vị trí thích hợp nhất. Ví dụ: bạn có thể lưu trữ một trang web trong public clouds và liên kết nó với cơ sở dữ liệu bảo mật cao được lưu trữ trong private clouds của bạn (hoặc trung tâm dữ liệu tại công ty).

Điều này hữu ích khi bạn có một số thứ không thể đưa vào đám mây, có thể vì lý do pháp lý. Ví dụ: bạn có thể có một số phần dữ liệu cụ thể không thể được hiển thị công khai (như dữ liệu y tế) cần được lưu giữ trong trung tâm dữ liệu riêng tư của bạn. Một ví dụ khác là một hoặc nhiều ứng dụng chạy trên phần cứng cổ không thể cập nhật. Trong trường hợp này, bạn có thể giữ cho hệ thống cổ chạy cục bộ và kết nối nó với public clouds để ủy quyền hoặc lưu trữ.

##### Ưu điểm

Một số lợi thế của hybrid clouds là:
* Bạn có thể giữ cho bất kỳ hệ thống nào chạy và có thể truy cập sử dụng phần cứng lỗi thời hoặc hệ điều hành lỗi thời
* Bạn linh hoạt với những gì bạn chạy cục bộ so với trong đám mây
* Bạn có thể tận dụng lợi thế economies of scale từ các nhà cung cấp dịch vụ public cloud để có các dịch vụ và tài nguyên khi giá rẻ hơn, sau đó bổ sung bằng thiết bị của riêng bạn khi không
* Bạn có thể sử dụng thiết bị của riêng mình để đáp ứng các tình huống bảo mật, tuân thủ hoặc cũ kỹ mà bạn cần kiểm soát hoàn toàn môi trường

##### Nhược điểm

Một số lo ngại bạn sẽ cần đề phòng là:
* Nó có thể tốn kém hơn so với việc chọn một mô hình triển khai vì nó liên quan đến một số chi phí CapEx trả trước
* Có thể phức tạp hơn để thiết lập và quản lý

## Tóm lược

Cloud computing rất linh hoạt và cung cấp cho bạn khả năng chọn cách bạn muốn triển khai nó. Cloud deployment models bạn chọn tùy thuộc vào ngân sách của bạn và vào nhu cầu bảo mật, khả năng mở rộng và bảo trì của bạn.

[**Bài tập tiếp theo: Các loại dịch vụ đám mây**](TypesOfCloudServices.md)