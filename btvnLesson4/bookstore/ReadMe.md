Bước 1 : Viết tạo ra RestController để Restful API

Bước 2 Viết các hàm Imp từ class Dao xử lý logic


Bước 3: sử dụng @Authorwired để tiêm class Dao vào Controller


Bước 4 : gọi các hàm viết ở BookDao ở các HTTP method thực hiện các công việc tìm kiếm id ,thêm , xóa , sửa theo id

Bước 5 : Xử lý Exception nếu như tìm kiếm id không có trong list book ta đưa ra Exception : Not Found Exception


Bước 6 : Test Kết quả trên POSTMAN

Lấy ra list book :




Tìm kiếm theo id :




Nếu Không Có đưa ra Exception :




Thêm sách vào List :





Update Theo ID:




Delete Theo ID :

