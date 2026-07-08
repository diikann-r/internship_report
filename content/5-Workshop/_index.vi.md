---
title: "Workshop"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Xây dựng hệ thống Serverless AI Invoice Scanner trên AWS

#### Tổng quan

Trong bài lab này, bạn sẽ thiết lập và triển khai một giải pháp xử lý hóa đơn tự động hóa hoàn toàn bằng mô hình **Serverless** trên AWS phối hợp với **OpenAI API**.

Hệ thống cho phép người dùng đăng nhập bằng Cognito, tải lên hóa đơn, tự động kích hoạt Lambda để gửi sang Amazon Textract thực hiện OCR trích xuất chữ viết, sau đó chuyển kết quả qua OpenAI API để chuẩn hóa dữ liệu và lưu trữ vào DynamoDB. Người dùng có thể quản lý, lọc, gắn tags và xuất Excel thông qua giao diện ReactJS.

![Architecture Diagram](/images/architecture-log.png)

#### Nội dung

1. [Giới thiệu](1-introduce/)
2. [Chuẩn bị môi trường](2-environmentsetup/)
3. [Xử lý Hóa Đơn bằng AI](3-aipoweredinvoiceprocessing/)
4. [Triển khai API Gateway](4-deployingapigateway/)
5. [Kiểm thử với Postman](5-testwithpostman/)
6. [Triển khai ứng dụng Frontend](6-deployingfrontend/)
7. [Dọn dẹp tài nguyên](7-cleanup/)