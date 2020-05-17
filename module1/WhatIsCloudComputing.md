# Cloud computing là gì?

[Link gốc](https://docs.microsoft.com/en-us/learn/modules/principles-cloud-computing/2-what-is-cloud-computing)

Cloud computing (điện toán đám mây) là thuê tài nguyên như không gian lưu trữ hay chu kỳ CPU (Central Processing Unit - bộ xử lý), trên máy tính của công ty khác. Bạn chỉ trả cho cái bạn dùng. Công ty cung cấp những dịch vụ này được gọi là cloud provider (nhà cung cấp đám mây). Ví dụ một vài nhà cung cấp là Microsoft, Amazon, Google.

Nhà cung cấp đám mây chịu trách nhiệm cho phần cứng hiện hữu cần thiết để thực hiện công việc của bạn, va để giữ cho nó được cập nhật. Dịch vụ đám mây tùy thuộc vào nhà cung cấp. Tuy nhiên, thương thì chúng gồm:
* Computing power (công suất tính toán) - như Linux servers (máy chủ) hay ứng dụng web
* Storage (lưu trữ) - như files (tập tin) và databases (cơ sở dữ liệu)
* Network (mạng) - như kết nối an toàn giữa nhà cung cấp đám mây và công ty của bạn
* Analytics (phân tích) - như trực quan telemetry (dữ liệu đo lường từ xa) và performance (hiệu năng)

## Các dịch vụ đám mây

Mục đích của cloud computing là làm việc kinh doanh dễ dàng và hiệu quả hơn, cho dù đó là công ty khởi nghiệp nhỏ hay doanh nghiệp lớn. Mỗi cơ sở kinh doanh có nhu cầu riêng biệt và khác nhau. Để đáp ứng những nhu cầu đấy, nhà cung cấp điện toán đám mây đưa ra phạm vi dịch vụ rộng lớn.

Bạn cần phải có kiến thức cơ bản về một vài dịch vụ được cung cấp. Hãy cùng nhanh chóng thảo luận 2 dịch vụ mà tất cả nhà cung cấp đám mây thương đưa ra nhất. 

## Computing power - Công suất tính toán

Khi bạn gủi email, làm một đơn đặt hàng trên Internet, trả hóa đơn online, hay thậm chí học module Microsoft Learn này thì bạn đang giao tiếp với các máy chủ; chúng đang xử lý mỗi request (yêu cầu) và trả lại từng response (lời đáp). Là khách hàng, chúng ta đều phụ thuộc vào dịch vụ đám mây cung cấp bởi nhiều nhà cung cấp đám mây hình thành nên Internet.

Khi bạn xây dựng giải pháp cloud computing, bạn có thể chọn cách bạn muốn làm việc dựa trên tài nguyên và nhu cầu của bạn, Ví dụ, nếu bạn muốn có thêm quyền quản lý và trách nhiệm với bảo trì, bạn có thể tạo virtual machine (VM - máy ảo). VM là emulator (trình giả lập) của một chiếc máy tính - giống như cái máy bàn hay laptop bạn đang dùng bây giò. Mỗi VM bao gồm một hệ điều hành và phần cứng xuất hiện trước người dùng giống như một máy tính hiện hữu chạy trên Windows hay Linux. Bạn có thể cài đặt bất cứ phần mềm nào bạn cần để thực hiện công việc bạn muốn chạy trên đám mây.

Sự khác biệt là bạn không phải mua bất kỳ phần cứng nào hay cài đặt OS (Operating system - hệ điều hành). Nhà cung cấp dịch vụ chạy virtual machine trên máy chủ hiện hữu trong 1 datacenter (trung tâm dữ liệu) của họ - thường chia sẻ máy chủ đó với những VMs khác (được tách biệt và bảo mật). Với đám mây, bạn có thể có 1 VM sẵn sàng làm việc trong vài phút ở chi phí thấp hơn 1 máy tính vật lý.

VMs không chỉ là lựa chọn duy nhất cho điện toán - có 1 khả năng được ưa thích khác: containers và serverless computing 

### Containers là gì?

Containers cung cấp 1 môi trường thi hành độc lập cho ứng dụng. Chúng giống VMs chỉ trừ việc chúng không yêu cầu guest operating system (hệ điều hành khách). Thay vào đó, ứng dụng và tất cả dependencies (những phụ thuộc) của chúng được đóng gói thành một "container" và rồi một môi trường vận hành tiêu chuẩn được dùng để thi hành ứng dụng đó. Điều này cho phép container khởi động chỉ trong vài giây, vì chả có OS mà boot (khởi động) và khởi tạo (initialize). Bạn chỉ cần chạy ứng dụng.

### Serverless computing là gì?

Serverless computing cho bạn chạy mã ứng dụng mà không tạo ra, điểu chỉnh cấu hình, hay bảo trì máy chủ. Điểu này lý tưởng cho automated tasks (các công việc tự động) - ví như bạn có thể xây dựng một serverless process tự động gửi email xác nhận sau khi khách hàng mua online. 

Serverless model khác với VMs và containers ở chỗ bạn chỉ trả tiền cho thời gian xử lý để thi hành mỗi hàm. VMs và containers thì bị tính tiền khi chúng đang chạy dù cho ưng dụng của bạn bên trong đó đang idle (rảnh rỗi).  Kiến trúc này không phù hợp cho tất cả ứng dụng, nhưng khi app logic có thể được tách thành những đơn vị độc lập, bạn có thể kiểm tra, cập nhật chúng riêng biệt, và khởi động trong và microseconds ($10^{-6}$ giây) - thế nên phương thức này là lựa chọn nhanh nhất cho deployment (việc triển khai).

Đây là biểu đồ so sánh giữa 3 phương pháp điện toán chúng ta đã đề cập.
![VM vs Containers vs Serverless](https://docs.microsoft.com/en-us/learn/modules/principles-cloud-computing/media/2-vm-vs-container-vs-serverless.png)

## Storage - Lưu trữ

Đa số thiết bị và ứng dụng đọc và/hoặc viết dữ liệu. Đây là một vài ví dụ:
* Mua vé xem phim online
* Tra cứu giá đồ vật online
* Chụp hình
* Gửi email
* Để lại voicemail (thư thoại)
  
Trong tất cả những trường hợp trên, dữ liệu hoặc được đọc (tìm giá) hay viết (chụp hình). Loại dữ liệu và cách chúng được lưu trữ có thể khác biệt tùy từng trường hợp.

Nhà cung cấp đám mây thường chỉ đưa ra dịch vụ có thể xử lý toàn bộ mọi loại dữ liệu này. Ví dụ, nếu bạn muốn lưu văn bản hay một đoạn phim, bạn có thể sử dụng file trên ổ đĩa. Nếu bạn đã có một tập hợp các mối quan hệ như sổ địa chỉ, bạn có thể dùng phương thức có cấu trúc hơn như database.

Lơi thế khi lưu trữ dữ liệu trên đám mây là bạn có thể tăng cấp độ theo nhu cầu. Nếu bạn nhận thấy mình cần nhiều dung lượng hơn cho các đoạn phim, bạn có thể trả thêm một chút và tăng dung lượng bạn có. Trong 1 số trường hợp, dung lượng lưu trữ có thể tự động mở rộng hay thu nhỏ, nên bạn chỉ trả tiền đúng cái bạn cần ở bất cứ thời điểm nào.

# Tóm tắt

Mỗi thương vụ có nhu cầu và yêu cầu khác nhau. Cloud computing thì **linh hoạt** và **tiết kiệm chi phí**, có thể có lợi cho mọi loại hình kinh doanh dù là công ty khởi nghiệp nhỏ hay doanh nghiệp lớn. 

[**Bài tiếp theo: Lợi ích của cloud computing**](BenefitsOfCloudComputing.md)