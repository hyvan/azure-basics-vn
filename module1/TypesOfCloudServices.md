# Các loại dịch vụ đám mây

[Link gốc](https://docs.microsoft.com/en-us/learn/modules/principles-cloud-computing/5-types-of-cloud-services)

Khi nói về cloud computing, có ba loại chính. Điều quan trọng là phải hiểu chúng bởi vì chúng được sử dụng trong các cuộc trò chuyện, tài liệu và đào tạo.

## Khám phá ba loại cloud computing
IaaS so với SaaS so với PaaS

### Infrastructure as a service (IaaS) - Cơ sở hạ tầng như một dịch vụ

Infrastructure as a service là danh mục dịch vụ đám mây linh hoạt nhất. Nó nhằm mục đích cung cấp cho bạn quyền kiểm soát nhiều nhất đối với phần cứng được cung cấp chạy ứng dụng của bạn (máy chủ cơ sở hạ tầng CNTT và máy ảo VM, lưu trữ và hệ điều hành). Thay vì mua phần cứng, với IaaS, bạn thuê nó. Đó là một cơ sở hạ tầng máy tính tức thời, được cung cấp và quản lý qua internet.

**Ghi chú**

*Khi sử dụng IaaS, đảm bảo rằng dịch vụ hoạt động là trách nhiệm chung: nhà cung cấp đám mây chịu trách nhiệm đảm bảo cơ sở hạ tầng đám mây hoạt động chính xác; khách hàng đám mây chịu trách nhiệm đảm bảo dịch vụ họ đang sử dụng được định cấu hình chính xác, cập nhật và có sẵn cho khách hàng của họ. Điều này được gọi là **shared responsibility model** (mô hình trách nhiệm được chia sẻ).*

IaaS thường được sử dụng trong các tình huống sau:
* **Migrating workloads** (di dời khối lượng công việc). Thông thường, các cơ sở IaaS được quản lý theo cách tương tự như cơ sở hạ tầng tại chỗ và cung cấp đường dẫn di chuyển dễ dàng để đưa các ứng dụng hiện có lên đám mây.
* **Test and development** (thử nghiệm và phát triển). Các nhóm có thể nhanh chóng thiết lập và tháo dỡ các môi trường thử nghiệm và phát triển, đưa các ứng dụng mới ra thị trường nhanh hơn. IaaS làm cho môi trường phát triển và thử nghiệm mở rộng, nhanh chóng và tiết kiệm.
* **Storage, backup, and recovery** (lưu trữ, sao lưu và phục hồi). Các tổ chức tránh sự chi phối vốn và sự phức tạp của quản lý lưu trữ, thường đòi hỏi nhân viên có kỹ năng quản lý dữ liệu và đáp ứng các yêu cầu pháp lý và tuân thủ. IaaS rất hữu ích để quản lý nhu cầu không thể đoán trước và nhu cầu lưu trữ tăng trưởng đều đặn. IaaS cũng có thể đơn giản hóa việc lập kế hoạch và quản lý các hệ thống sao lưu phục hồi.

### Platform as a service (PaaS - Nền tảng như một dịch vụ)

PaaS cung cấp một môi trường để xây dựng, thử nghiệm và triển khai các ứng dụng phần mềm. Mục tiêu của PaaS là ​​giúp bạn tạo một ứng dụng nhanh chóng mà không cần quản lý cơ sở hạ tầng bên dưới. Ví dụ: khi triển khai ứng dụng web bằng PaaS, bạn không phải cài đặt hệ điều hành, máy chủ web hoặc thậm chí cập nhật hệ thống.

PaaS là ​​một môi trường phát triển và triển khai hoàn chỉnh trong đám mây, với các tài nguyên cho phép các tổ chức phân phối mọi thứ từ các ứng dụng dựa trên đám mây đơn giản đến các ứng dụng doanh nghiệp tinh vi để hỗ trợ đám mây. Tài nguyên được mua từ nhà cung cấp dịch vụ đám mây trên cơ sở tiền trao cháo múc và được truy cập qua kết nối Internet an toàn.

PaaS thường được sử dụng trong các tình huống sau:
* **Development framework** (bộ khung phát triển). PaaS cung cấp một khung cho các lập trình viên có thể dựa vào đó mà xây dựng và phát triển hoặc tùy chỉnh các ứng dụng trên đám mây. Giống như Microsoft Excel macro, PaaS cho phép các lập trình viên tạo ứng dụng bằng các thành phần phần mềm tích hợp. Các tính năng của đám mây bao gồm khả năng mở rộng, tính sẵn sàng cao và khả năng cho nhiều người cùng thuê làm giảm số lượng code mà các lập trình viên phải viết.

* **Analytics or business intelligence** (phân tích hoặc kinh doanh thông minh). Các công cụ được cung cấp dưới dạng dịch vụ với PaaS cho phép các tổ chức phân tích và khai thác dữ liệu của họ. Họ có thể tìm thấy những insights (phân tích sâu) và patterns (kiểu mẫu), dự đoán kết quả để cải thiện các quyết định kinh doanh như dự báo, thiết kế sản phẩm và lợi nhuận đầu tư.

### Software as a service (SaaS - Phần mềm dưới dạng dịch vụ)

SaaS là ​​phần mềm được lưu trữ và quản lý tập trung cho end customer (khách hàng cuối). Nó thường dựa trên kiến ​​trúc mà dùng một phiên bản của ứng dụng cho tất cả khách hàng và được cấp phép thông qua đăng ký hàng tháng hoặc hàng năm. Office 365, Skype và Dynamics CRM Online là những ví dụ hoàn hảo về phần mềm SaaS.

## Chi phí và quyền sở hữu

|   |IaaS|PaaS|SaaS|
|---|----|----|----|
|Chi phí trả trước|Không có chi phí trả trước. Người dùng chỉ trả tiền cho những gì họ tiêu thụ.|Không có chi phí trả trước. Người dùng chỉ trả tiền cho những gì họ tiêu thụ.|Người dùng không trả trước; họ trả tiền thuê bao, thường là hàng tháng hoặc hàng năm|
|Quyền sở hữu người dùng|Người dùng chịu trách nhiệm mua, cài đặt, cấu hình và quản lý phần mềm, hệ điều hành, phần mềm trung gian và ứng dụng của riêng họ.|Người dùng chịu trách nhiệm phát triển các ứng dụng của riêng họ. Tuy nhiên, họ không chịu trách nhiệm quản lý máy chủ hoặc cơ sở hạ tầng. Điều này cho phép người dùng tập trung vào ứng dụng hoặc khối lượng công việc họ muốn chạy.|Người dùng chỉ cần sử dụng phần mềm ứng dụng; họ không chịu trách nhiệm cho bất kỳ bảo trì hoặc quản lý phần mềm đó.|
|Quyền sở hữu nhà cung cấp đám mây|Nhà cung cấp đám mây chịu trách nhiệm đảm bảo rằng cơ sở hạ tầng đám mây cơ bản (như máy ảo, lưu trữ và kết nối mạng) có sẵn cho người dùng.|Nhà cung cấp đám mây chịu trách nhiệm quản lý hệ điều hành, mạng và cấu hình dịch vụ. Các nhà cung cấp đám mây thường chịu trách nhiệm cho mọi thứ ngoài ứng dụng mà người dùng muốn chạy. Họ cung cấp một nền tảng được quản lý hoàn chỉnh để chạy ứng dụng.|Nhà cung cấp đám mây chịu trách nhiệm cung cấp, quản lý và bảo trì phần mềm ứng dụng.|


## Trách nhiệm quản lý

Một điều cần hiểu là các thể loại này là các lớp chồng lên nhau. Ví dụ, PaaS thêm một lớp trên IaaS bằng cách cung cấp một level of abstraction (cấp độ trừu tượng). Tính trừu tượng có lợi ích cho việc ẩn các chi tiết mà bạn có thể không quan tâm, để bạn có thể bắt đầu lập trình nhanh hơn. Tuy nhiên, một khía cạnh của trừu tượng là bạn có ít quyền kiểm soát phần cứng bên dưới hơn. Hình minh họa sau đây cho thấy danh sách các tài nguyên bạn quản lý và nhà cung cấp dịch vụ của bạn quản lý trong mỗi thể loại dịch vụ đám mây.

![Các tầng bên duới mỗi loại dịch vụ đám mây](https://docs.microsoft.com/en-us/learn/modules/principles-cloud-computing/media/5-layer-diagram.png)
*Màu xanh nhạt là bạn quản lý, xanh đậm là nhà cung cấp quản lý*

* IaaS yêu cầu người dùng quản lý  nhiều nhất trong tất cả các dịch vụ đám mây. Người dùng chịu trách nhiệm quản lý các hệ điều hành, dữ liệu và ứng dụng.
* PaaS yêu cầu người dùng quản lý  ít hơn. Nhà cung cấp đám mây quản lý các hệ điều hành và người dùng chịu trách nhiệm về các ứng dụng và dữ liệu họ chạy và lưu trữ.
* SaaS yêu cầu mức quản lý ít nhất. Nhà cung cấp đám mây chịu trách nhiệm quản lý mọi thứ và end user chỉ sử dụng phần mềm.

## Kết hợp các dịch vụ đám mây để phù hợp với nhu cầu của bạn

Mỗi IaaS, PaaS và SaaS đều chứa các cấp độ dịch vụ được quản lý khác nhau. Bạn có thể dễ dàng sử dụng kết hợp các loại cơ sở hạ tầng. Bạn có thể sử dụng Office 365 trên máy tính của công ty bạn (SaaS) và trong Azure, bạn có thể lưu trữ máy ảo (IaaS) và sử dụng Cơ sở dữ liệu SQL Azure (PaaS) để lưu trữ dữ liệu của bạn. Với tính linh hoạt của đám mây, bạn có thể dùng bất kỳ tổ hợp nào để cung cấp cho bạn kết quả tối ưu.

[Kế tiếp: Kiểm tra kiến ​​thức](KnowledgeCheck.md)
