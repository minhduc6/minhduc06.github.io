Bước 1 : Viết BookController để thực hiện method HTTP Get,POST,... và gọi các hàm xử lý logic từ bài trước để xử lý





Bước 2 : Để hiển thị list danh sách các em tạo  file html allbooks ở đây em có sử dụng bootstrap để hiển thị :

sử dụng thymleaf for-each để hiển thị:





Đât là kết quả : 


Bước 3  : Để thêm 1 book mơi em tạo ra file html book_form như trên :




Kết Quả :

Bước 4 : Update book theo id thì cũng như tạo 1 book mới nhưng khi add id chưa có còn update thì có rồi và tìm kiếm book theo ID  rồi sửa

và đều sử dụng method POST("/book/savve") book_form 



Kết quả :

Bước 5 : Delete Book thì cũng tương tự tìm kiềm theo id rồi xóa




Bước 6 : Tìm kiếm theo Id :

Em sử dụng request Param nhập ID trong allbook :




KQ:




























