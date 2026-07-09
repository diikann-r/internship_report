---
title: "Worklog Tuần 4"
date: 2026-05-08
weight: 40
chapter: false
pre: " <b> 1.4. </b> "
---
### Mục tiêu tuần 4:

* Nghiên cứu và sử dụng công cụ Reachability Analyzer để kiểm tra cũng như phân tích khả năng kết nối trong hệ thống mạng AWS.
* Thực hành cấu hình EC2 Instance Connect Endpoint kết hợp với AWS Systems Manager Session Manager nhằm hỗ trợ quản lý và truy cập máy chủ an toàn mà không cần kết nối SSH trực tiếp.
* Cấu hình CloudWatch Monitoring & Alerting để theo dõi hoạt động của hệ thống và thiết lập cảnh báo khi xảy ra sự cố.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 6 | - Tìm hiểu AWS Reachability Analyzer: khái niệm, use cases, cách phân tích path kết nối giữa các resource trong VPC | 08/05/2026 | 08/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - **Thực hành:** sử dụng Reachability Analyzer kiểm tra connectivity giữa EC2, Subnets, Security Groups <br> - Xác định và sửa lỗi mạng | 09/05/2026 | 09/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - Cấu hình EC2 Instance Connect Endpoint: tạo Endpoint trong VPC, Security Group, routing | 10/05/2026 | 10/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - Thiết lập AWS Systems Manager Session Manager: IAM role, SSM Agent, Instance profile cho EC2 | 11/05/2026 | 11/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành:** kết hợp EC2 Instance Connect Endpoint và Session Manager để truy cập máy chủ an toàn không cần SSH trực tiếp | 12/05/2026 | 12/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Cấu hình CloudWatch Monitoring: metrics EC2/VPC, tạo Dashboard theo dõi hoạt động hệ thống | 13/05/2026 | 13/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Thiết lập CloudWatch Alarms & Alerting: ngưỡng cảnh báo CPU/disk/network <br> - SNS notification khi xảy ra sự cố | 14/05/2026 | 14/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 4:

* Sử dụng thành thạo Reachability Analyzer để kiểm tra và phân tích khả năng kết nối trong hệ thống mạng AWS.
* Thiết lập thành công quản lý truy cập máy chủ an toàn không cần SSH trực tiếp:
  * Triển khai EC2 Instance Connect Endpoint.
  * Tích hợp với Systems Manager Session Manager.
  * Gán IAM Roles, Instance Profiles và kích hoạt SSM Agent.
* Cấu hình đầy đủ giám sát CloudWatch Monitoring & Alerting:
  * Xây dựng CloudWatch Dashboards theo dõi metrics tài nguyên.
  * Thiết lập CloudWatch Alarms cho CPU, Disk, Network.
  * Tích hợp Simple Notification Service (SNS) để gửi cảnh báo tự động khi xảy ra sự cố.
