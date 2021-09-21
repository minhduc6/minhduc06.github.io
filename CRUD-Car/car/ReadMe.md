Bước 1 : Tạo Project với cấu trúc như sau :

![1](https://user-images.githubusercontent.com/72613060/134251861-7c1fa8c5-8b1f-4f3d-a790-4bf827cd4eb4.png)


Bước 2 : Tạo File json để lấy dữ liệu đọc File :
![2](https://user-images.githubusercontent.com/72613060/134251881-4f4aca3f-47ea-426b-bb63-92ef203fdab7.png)




Bước 3 : Tạo class Car.java trong model

:![3](https://user-images.githubusercontent.com/72613060/134251904-00036d6d-aada-43b2-b488-4ae4519839ef.png)




Bước 4 : Tạo Repository để đọc file add vào cars và xử lý logic như getAll(), thêm ,sửa ,xóa theo ID , tìm kiếm theo keyword , hay sort theo price hay name :

![4](https://user-images.githubusercontent.com/72613060/134251923-be169df8-6585-43ae-ab57-0abaf3db9bd9.png)

![4 1](https://user-images.githubusercontent.com/72613060/134251952-4257ba4d-8d57-4ef4-8453-69a376da1dda.png)

![4 2](https://user-images.githubusercontent.com/72613060/134251968-06f08a16-7058-4530-a671-f4c42e2ba082.png)





Bước 5 Tạo CarController và tiêm CarRepository lên để gọi các hàm logic lên xử lý

![5](https://user-images.githubusercontent.com/72613060/134251990-8eebc7d0-c26e-45a1-8bc2-d8010e8e89e1.png)


Bước 6 : Sử dụng các method HTTP POST,GET để xử lý từng nghiệp vụ xong trả về html:


![6](https://user-images.githubusercontent.com/72613060/134252006-5937f25b-89cb-4873-bb11-e5422b44e034.png)


![6 1](https://user-images.githubusercontent.com/72613060/134252015-cf85afe8-a336-477f-8e5d-baa6c15568b1.png)


Bước 7 :  Tạo trang home.html trả về danh sách các car :


![7](https://user-images.githubusercontent.com/72613060/134252043-1381fa2b-f873-4f7c-a313-d5f764a3a9f6.png)


Bước 8 : Tạo Car-form.html để thêm và sửa car
![8](https://user-images.githubusercontent.com/72613060/134252055-6ac545b2-fdee-4712-8a30-80a8fb3dbaa0.png)


Bước 9 : Để search 1 car theo keyword em sử dụng @RequestParam để lấy keyword truyền xuông sever và rồi xử lý :
![9](https://user-images.githubusercontent.com/72613060/134252066-4444884b-d67f-4b14-bcbd-74cba84dd874.png)


xử lý HTML : 
![9 1](https://user-images.githubusercontent.com/72613060/134252090-1aafec00-6123-408c-84dc-dbc20e176d86.png)


xử lý dưới sever :
![9 2](https://user-images.githubusercontent.com/72613060/134252104-62d5136b-0719-4723-9a7f-527d6dac81b9.png)


Bước 10 :Để sắp xêp car thì em cũng sử dụng @RequestParam để lấy sắp xếp theo cái gì nếu sapxep = 1 thì sắp theo price , sapxep = 2 thì sắp theo name model
  ![10](https://user-images.githubusercontent.com/72613060/134252118-a9762d9e-b272-4822-ab98-9bad02f3ca22.png)


xử lý html :
![10 1](https://user-images.githubusercontent.com/72613060/134252134-42082e77-863f-4b5f-9542-6dcecef6aa69.png)


xử lý dưới sever :


![10 2](https://user-images.githubusercontent.com/72613060/134252144-9b011220-1be5-4d3c-9052-ca32187014a3.png)



Kết Quả :

Lấy danh sách Car :

![list](https://user-images.githubusercontent.com/72613060/134252172-e85b0a22-75a1-4fc5-8ce9-4e062d2526fc.png)

Thêm Car :
![add](https://user-images.githubusercontent.com/72613060/134252187-518d2352-a1ba-4425-b7a2-3d874fff7b44.png)

![add1](https://user-images.githubusercontent.com/72613060/134252202-bcd9eeb2-7d34-4dcf-907f-1a44fd674d3c.png)

Sửa Car :

![update](https://user-images.githubusercontent.com/72613060/134252216-19ed11fc-ae0a-4327-9950-f3acb82c0778.png)


Xóa Car có id 5 :

![delete](https://user-images.githubusercontent.com/72613060/134252231-4a22311d-465f-4b70-997b-d6e4be9480de.png)


Tìm Kiếm theo keyword  = me:

![search](https://user-images.githubusercontent.com/72613060/134252275-5cc283c0-beff-4af3-9f9d-20fabc180584.png)


Chitiet Car :

![20001](https://user-images.githubusercontent.com/72613060/134252576-32b99884-dfb2-4c88-88a9-54f7ceaed21c.png)




Sắp xếp theo price :

![price](https://user-images.githubusercontent.com/72613060/134252255-48a27a26-e075-4286-be97-db3fddce8e2e.png)


Sắp xếp theo name Model :

![name](https://user-images.githubusercontent.com/72613060/134252280-8e175003-bff3-41ab-a0d4-562ffcb95e5a.png)











