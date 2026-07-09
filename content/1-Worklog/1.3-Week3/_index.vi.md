---
title: "Worklog Tuần 3"
date: 2026-05-01
weight: 30
chapter: false
pre: " <b> 1.3. </b> "
---
### Mục tiêu tuần 3:

* Tìm hiểu các chức năng cơ bản của Amazon EC2: lựa chọn Instance Type, quản lý AMI, Backup, Key Pair và Elastic Block Store (EBS).
* Thực hành tạo và cấu hình máy chủ ảo trên AWS.
* Thiết lập lưu trữ dữ liệu và backup với EBS.
* Thiết lập bảo mật kết nối trên AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 6 | - Tìm hiểu Amazon EC2 và lựa chọn Instance Type phù hợp: General Purpose, Compute Optimized, Memory Optimized, Free Tier | 01/05/2026 | 01/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - Quản lý AMI: tạo custom AMI, copy AMI giữa các Region, snapshot từ EC2 instance | 02/05/2026 | 02/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - Key Pair: tạo, lưu trữ an toàn, sử dụng SSH key để xác thực kết nối EC2 | 03/05/2026 | 03/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - Elastic Block Store (EBS): volume types (gp3, io2), tạo volume, gắn/gỡ volume vào EC2 | 04/05/2026 | 04/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - **Thực hành:** tạo EC2 instance (t2.micro), chọn AMI, cấu hình Security Group, kết nối SSH | 05/05/2026 | 05/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Backup dữ liệu: tạo EBS snapshot, tạo AMI từ snapshot, chiến lược backup và khôi phục | 06/05/2026 | 06/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Thiết lập bảo mật kết nối: hardening SSH, Security Groups inbound/outbound, Elastic IP, kiểm tra truy cập an toàn | 07/05/2026 | 07/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 3:

* Nắm vững các chức năng cơ bản của EC2: Instance Type, AMI, Key Pair và EBS.
* Khởi tạo, cấu hình và kết nối SSH thành công vào EC2 instance.
* Quản lý lưu trữ dữ liệu và backup với EBS:
  * Tạo EBS snapshot.
  * Tạo AMI từ snapshot.
  * Xây dựng và kiểm thử chiến lược backup và khôi phục.
* Thiết lập bảo mật kết nối theo best-practices:
  * Thực hiện hardening SSH.
  * Cấu hình chi tiết Security Groups inbound/outbound.
  * Cấu hình Elastic IP và kiểm tra truy cập an toàn.
