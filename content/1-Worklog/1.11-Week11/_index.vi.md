---
title: "Worklog Tuần 11"
date: 2026-06-26
weight: 110
chapter: false
pre: " <b> 1.11. </b> "
---
### Mục tiêu tuần 11:

* Hoàn thiện quy trình xử lý và trích xuất hóa đơn tự động bằng Amazon Textract, Bedrock/OpenAI và DynamoDB.
* Tối ưu hóa hiệu năng, giảm thời gian xử lý và kiểm thử toàn diện AWS Lambda.
* Hoàn thiện dashboard Amazon QuickSight phục vụ trực quan hóa dữ liệu hóa đơn và làm báo cáo thống kê.
* Rà soát cấu hình phân quyền IAM, an toàn lưu trữ trên S3, bảo mật Lambda và API Gateway.
* Kiểm thử tích hợp hệ thống (Integration Testing) từ frontend đến backend và khắc phục các lỗi vận hành.
* Chuẩn bị đầy đủ tài liệu kỹ thuật, slide thuyết trình và kịch bản demo sản phẩm chuẩn bị cho báo cáo cuối kỳ.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------- |
| 6 | - Tối ưu hóa mã nguồn xử lý hóa đơn, tích hợp OpenAI/Bedrock và DynamoDB trong Lambda | 26/06/2026 | 26/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7 | - Kiểm thử đơn lẻ (Unit Testing) hiệu năng của Lambda, đo lường thời gian chạy và tối ưu hóa bộ nhớ | 27/06/2026 | 27/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| CN | - Kết nối dữ liệu DynamoDB (qua Athena) sang Amazon QuickSight, thiết kế và hoàn thiện các biểu đồ trực quan của Dashboard | 28/06/2026 | 28/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2 | - Kiểm tra và rà soát thiết lập IAM Policies cho các dịch vụ (S3, Lambda, DynamoDB), đảm bảo Least Privilege | 29/06/2026 | 29/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Tiến hành kiểm thử tích hợp (Integration Testing) toàn bộ pipeline từ lúc tải hóa đơn lên S3 đến lúc hiển thị kết quả trên Dashboard | 30/06/2026 | 30/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - Phát hiện và khắc phục các lỗi phát sinh (CORS, lỗi định dạng JSON từ OpenAI, lỗi phân quyền API Gateway) | 01/07/2026 | 01/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Soạn thảo tài liệu hướng dẫn kỹ thuật (Technical Spec), chuẩn bị slide báo cáo và quay phim/chụp ảnh kịch bản demo hệ thống | 02/07/2026 | 02/07/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 11:

* **Hoàn thiện pipeline xử lý hóa đơn tự động:**
  * Quy trình xử lý hóa đơn kết hợp Amazon Textract (OCR) và mô hình AI để chuẩn hóa dữ liệu lưu vào DynamoDB hoạt động ổn định và chính xác.
  * AWS Lambda được cấu hình tối ưu tài nguyên (Memory, Timeout) giúp tốc độ xử lý nhanh hơn 30% và xử lý thành công nhiều loại hóa đơn (PDF, PNG, JPEG).

* **Dashboard báo cáo phân tích hoàn chỉnh:**
  * Hoàn thành xây dựng Dashboard trên Amazon QuickSight kết nối trực tiếp với DynamoDB, cập nhật số liệu hóa đơn theo thời gian thực.
  * Dashboard hiển thị trực quan các biểu đồ tổng doanh thu, số lượng hóa đơn theo tháng, phân loại theo thẻ (Tags) và bộ lọc theo nhà cung cấp/khách hàng.

* **Bảo mật và Kiểm thử hệ thống:**
  * Rà soát và khóa các cổng bảo mật bằng các IAM Policy chuyên biệt, đáp ứng tiêu chuẩn an toàn thông tin của dự án.
  * Khắc phục hoàn toàn các lỗi CORS khi Frontend giao tiếp với API Gateway và các lỗi timeout của Lambda khi xử lý tệp tin dung lượng lớn.
  * Chuẩn bị đầy đủ tài liệu kỹ thuật chi tiết cùng kịch bản demo và slide báo cáo phục vụ hội đồng nghiệm thu dự án.
