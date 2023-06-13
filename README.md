<p align="center">
 <h1 align="center">Khái quát chung về Docker</h1>
</p> 

## Docker là gì ?

- Docker là một nền tảng để cung cấp cách để building, deploying và running ứng dụng dễ dàng hơn bằng cách sử dụng các containers (trên nền tảng ảo hóa). Hay nói một cách khác nó là một nền tảng để cung cấp cách để building, deploy và run các ứng dụng một cách dễ dàng trên nền tảng ảo hóa - "Build once, run anywhere". Ban đầu viết bằng Python, hiện tại đã chuyển sang Golang

## Mục đích sử dụng docker

- Trọng tâm chính của docker là tự động hóa việc triển khai các ứng dụng bên trong bộ chứa phần mềm và tự động hóa ảo hóa cấp hệ điều hành. Nó nhẹ hơn các Container tiêu chuẩn và khởi động trong vài giây.
- Đóng gói và chạy các ứng dụng trong các container

- ![image](https://github.com/thangdtph27626/DocKer.github.io/assets/109157942/6e70e361-eefc-4366-952e-bedeff96ae77)

## Ưu nhược điểm của docker

Các Container  có thể thực hiện được nhờ các khả năng ảo hóa và cách ly quy trình được tích hợp trong nhân Linux. Các khả năng này chẳng hạn như  nhóm điều khiển phân bổ tài nguyên giữa các quy trình và  không gian tên  để hạn chế quyền truy cập hoặc khả năng hiển thị của quy trình đối với các tài nguyên hoặc khu vực khác của hệ thống cho phép nhiều thành phần ứng dụng chia sẻ tài nguyên của một phiên bản duy nhất của máy chủ vận hành hệ thống theo cách giống như cách một virtual machines (VMs) chia sẻ CPU, bộ nhớ và các tài nguyên khác của một máy chủ phần cứng. 

Do đó, công nghệ vùng chứa cung cấp tất cả các chức năng và lợi ích của máy ảo bao gồm solation, cost-effective scalability, và disposability với các lợi thế bổ sung quan trọng:
- Trọng lượng nhẹ hơn: Không giống như máy ảo, bộ chứa không mang trọng tải của toàn bộ phiên bản hệ điều hành và trình ảo hóa. Chúng chỉ bao gồm các quy trình và phụ thuộc hệ điều hành cần thiết để thực thi mã. Kích thước vùng chứa được đo bằng megabyte (so với gigabyte đối với một số máy ảo), tận dụng tốt hơn dung lượng phần cứng và có thời gian khởi động nhanh hơn. 
- Cải thiện năng suất của nhà phát triển: Các ứng dụng được đóng gói có thể được viết một lần và chạy ở mọi nơi. Và so với VM, các container nhanh hơn và dễ dàng hơn để triển khai, cung cấp và khởi động lại. Điều này làm cho chúng trở nên lý tưởng để sử dụng trong  các quy trình tích hợp liên tục  và  phân phối liên tục  (CI/CD) và phù hợp hơn cho các nhóm phát triển áp dụng các phương pháp Agile và  DevOps  .
- Hiệu quả sử dụng tài nguyên cao hơn: Với bộ chứa, nhà phát triển có thể chạy số lượng bản sao của ứng dụng trên cùng một phần cứng nhiều gấp nhiều lần so với khi họ có thể sử dụng máy ảo. Điều này có thể làm giảm chi tiêu đám mây.
- Tiện Lợi: Bạn có thể tạo một môi trường nhanh chóng một môi trường ảo hóa chứa đầy đủ những cài đặt
- Khả năng di động: môi trường develop được dựng lên bằng docker có thể chuyển từ người này sang người khác mà không thay đổi cấu hình bên triong 
- Chi sẻ: DockerHub là một app store for dọker images trên Docker có hàng ngàn docker public inmages được tạo bởi cộng đồng. Bạn có thể de3ex dàng tìm kiếm những images cần và chỉ cần pull và một vài sửa đổi nhỏ 
- Môi trường chạy và khả năng mở rộng: bạn có thể chia nhỏ những chức nằng cảu ứng dụng thành các container riêng lẻ

  ## Lộ trình tìm hiểu Docker

 một số bước cơ bản có thể giúp bạn bắt đầu với Docker:

1 Cài đặt Docker trên máy tính của bạn.\
2 Tìm hiểu về các khái niệm cơ bản của Docker như image, container và registry.\
3 Tìm hiểu cách sử dụng Dockerfile để xây dựng image.\
4 Tìm hiểu cách sử dụng docker-compose để quản lý các container.\
5 Thực hành bằng cách tạo các image và container đơn giản.

Bạn có thể tham khảo lloj trình tìm hiểu docker [tại đây](https://roadmap.sh/docker)
