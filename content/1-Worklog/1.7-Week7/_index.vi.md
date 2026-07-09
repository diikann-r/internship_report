---
title: "Worklog Tuần 7"
date: 2026-05-29
weight: 70
chapter: false
pre: " <b> 1.7. </b> "
---
### Mục tiêu tuần 7:

* Thực hiện đóng gói ứng dụng bằng Docker, xây dựng và quản lý Docker Image phục vụ quá trình triển khai trên nền tảng AWS.
* Triển khai ứng dụng container trên Amazon Lightsail Containers và Amazon EKS; cấu hình môi trường vận hành, tài nguyên hệ thống và kiểm tra khả năng hoạt động của ứng dụng.
* Thực hiện chuyển đổi ứng dụng Monolithic sang Microservices bằng Docker và AWS Fargate; triển khai các dịch vụ độc lập và đánh giá khả năng mở rộng của hệ thống.
* Xây dựng quy trình CI/CD với AWS CodePipeline và GitHub nhằm tự động hóa quá trình build, kiểm thử và triển khai ứng dụng container.
* Cấu hình giám sát, quản lý tài nguyên và áp dụng các biện pháp bảo mật cho môi trường container nhằm đảm bảo tính ổn định và an toàn của hệ thống.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 6 | - Đóng gói ứng dụng bằng Docker: viết Dockerfile, build Image, quản lý tag và push lên Amazon ECR | 29/05/2026 | 29/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - Quản lý Docker Image trên AWS: ECR lifecycle policy, image scanning, versioning phục vụ triển khai | 30/05/2026 | 30/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - Triển khai container trên Amazon Lightsail Containers: cấu hình service, domain, kiểm tra hoạt động ứng dụng | 31/05/2026 | 31/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - Triển khai container trên Amazon EKS: deploy workload, cấu hình tài nguyên, kiểm tra scaling và availability | 01/06/2026 | 01/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Chuyển đổi Monolithic sang Microservices với Docker và AWS Fargate; triển khai dịch vụ độc lập, đánh giá khả năng mở rộng | 02/06/2026 | 02/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Xây dựng CI/CD với AWS CodePipeline và GitHub: tự động build, test và deploy ứng dụng container | 03/06/2026 | 03/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Giám sát container (CloudWatch Container Insights), quản lý tài nguyên và bảo mật: IAM, secrets, network policies | 04/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 7:

* Đóng gói ứng dụng thành công bằng Docker và quản lý an toàn Image trên Amazon ECR.
* Triển khai ổn định container trên hai nền tảng:
  * Amazon Lightsail Containers.
  * Amazon EKS (Elastic Kubernetes Service).
* Chuyển đổi thành công kiến trúc từ Monolithic sang Microservices trên AWS Fargate, tối ưu khả năng mở rộng linh hoạt.
* Tự động hóa quy trình CI/CD qua sự kết hợp giữa AWS CodePipeline và GitHub.
* Tăng cường tính ổn định và an toàn hệ thống nhờ:
  * Cấu hình giám sát bằng CloudWatch Container Insights.
  * Quản lý chặt chẽ IAM Roles, Secrets Manager và Network Policies.
