# Môn Kiến trúc phần mềm hướng dịch vụ (25D1INF50902201)
## Excercise 1

### Mô tả các kiến thức đã áp dụng
**Minimal APIs và Web Service**
  - Xây dựng Minimal APIs với .Net 9 để xử lý các chức năng CRUD (Create, Read, Update, Delete).
  - Sử dụng Entity Framework Core với InMemory Database để lưu trữ và quản lý dữ liệu.
  - Triển khai các endpoint API:
    - `GET /todoitems`: Lấy danh sách to-do.
    - `POST /todoitems`: Thêm to-do mới.
    - `PUT /todoitems/{id}`: Cập nhật to-do.
    - `DELETE /todoitems/{id}`: Xóa to-do.

### Kết quả đạt được:
- Triển khai thành công các endpoint với Minimal APIs và thực hiện được các thao tác CRUD cơ bản.
- Sử dụng Swagger để kiểm thử và hiển thị chi tiết API tại `https://localhost:5152/swagger/index.html`.
- Tạo ứng dụng API tối giản, dễ mở rộng, phù hợp với các hệ thống microservices.

1. (GET) Lấy danh sách tất cả công việc - Lấy danh sách công việc hoàn thành - Lấy thông tin chi tiết một công việc
   ![Alt text](https://github.com/SOA-Excercises-Vo-Minh-Phuc/MINIMAL_API/blob/main/get.png)

2. (POST) Thêm một công việc 
   ![Alt text](https://github.com/SOA-Excercises-Vo-Minh-Phuc/MINIMAL_API/blob/main/post.png)

3. (DELETE) Xóa một công việc
   ![Alt text](https://github.com/SOA-Excercises-Vo-Minh-Phuc/MINIMAL_API/blob/main/delete.png)
4. (PUT) Cập nhật thông tin công việc 
   ![Alt text](https://github.com/SOA-Excercises-Vo-Minh-Phuc/MINIMAL_API/blob/main/put.png)
