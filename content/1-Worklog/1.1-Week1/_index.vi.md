---
title: "Worklog Tuần 1"
date: 2026-04-17
weight: 10
chapter: false
pre: " <b> 1.1. </b> "
---


### Mục tiêu tuần 1:

* Thiết lập tài khoản AWS và cấu hình quản lý chi phí.
* Cấu hình IAM theo best-practices.
* Xây dựng hạ tầng mạng VPC cơ bản và các lớp bảo mật.
* Triển khai EC2 và ứng dụng demo.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 6 | - Đăng ký tài khoản AWS, xác thực email <br> - Cấu hình thanh toán <br> - Bật MFA cho root account | 17/04/2026 | 17/04/2026 | |
| 7 | - Tìm hiểu Billing & Cost Explorer <br> - Thiết lập Budget Alerts <br> - Kiểm tra Free Tier | 18/04/2026 | 18/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - Nghiên cứu AWS Support Plans <br> - Mở Support ticket thử nghiệm <br> - Tham khảo AWS Documentation | 19/04/2026 | 19/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - Cấu hình IAM: tạo Users/Groups, gán Policies <br> - Tạo Role cho EC2 <br> - Thiết lập Password policy | 20/04/2026 | 20/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Thiết kế VPC cơ bản: chọn CIDR, tạo VPC <br> - Tạo Public & Private Subnets <br> - Cấu hình Route Tables, Internet Gateway | 21/04/2026 | 21/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Cấu hình bảo mật mạng: tạo Security Groups (web/db), Network ACLs <br> - Tạo NAT Gateway | 22/04/2026 | 22/04/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Khởi tạo EC2 (t2.micro), tạo Key Pair <br> - SSH vào máy, cài Apache/Nginx <br> - Triển khai ứng dụng demo | 23/04/2026 | 23/04/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 1:

* Tài khoản AWS đầy đủ cấu hình cơ bản (MFA, payment).
* Giám sát chi phí và cảnh báo (Budget Alerts) đã được thiết lập.
* IAM được tổ chức theo best-practices bao gồm:
  * Khởi tạo Users và Groups.
  * Gán Policies, thiết lập Password policy.
  * Tạo Role cho EC2 và kích hoạt MFA.
* Hạ tầng mạng cơ bản và bảo mật đã triển khai:
  * Thiết kế VPC, chia Public/Private Subnets.
  * Cấu hình Route Tables, Internet Gateway.
  * Thiết lập Security Groups (web/db) và Network ACLs.
  * Triển khai NAT Gateway.
* Khởi tạo và cấu hình thành công thực thể EC2:
  * Sử dụng instance t2.micro và Key Pair.
  * SSH thành công vào máy chủ.
  * Cài đặt Apache/Nginx và truy cập được ứng dụng demo.
