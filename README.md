# Sử dụng Git & GitHub với Python dành cho người mới
Chào mọi người, mình là Đạt, đây là bài hướng dẫn sử dụng Git & GitHub dành cho người mới
với ngôn ngữ Python và IDE là PyCharm

### I. Sơ đồ các bước sử dụng Git & GitHub

![Python_Git_Img.png](Image%2FPython_Git_Img.png)

### II. Sử dụng Git tích hợp trong PyCharm
Các bước sử dụng Git & GitHub tích hợp trong PyCharm:
#### Bước 1. Tạo project trên PyCharm
Để có thể thực hành sử dụng Git với Python dành cho người mới, ta thực hiện:
* Tạo một project mới với tên `Python_Git_1 `



* Tạo file `main.py` và nhập mã nguồn đơn giản: `print("Hello World")`

![Buoc1_2.png](Image%2FBuoc1_2.png)

#### Bước 2: Đăng nhập tài khoản GitHub trên PyCharm
Tiếp theo, để đăng nhập tài khoản GitHub trên PyCharm, ta thực hiện:
* Bấm vào biểu tượng 3 chấm phía trên bên phải
* Chọn `Settings -> Version Control -> GitHub`
* Thêm tài khoản GitHub của bạn và nhấn `Apply -> OK`

![Buoc2.png](Image%2FBuoc2.png)

Việc đăng nhập tài khoản trên GitHub giúp ta có thể thao tác với local repository và remote repository.
#### Bước 3: Tạo local repository cho project
* Bấm vào biểu tượng 3 chấm phía trên bên trái
* Chọn `VCS -> Enable Version Control Integration`

![Buoc3_1.png](Image%2FBuoc3_1.png)

* Chọn `Git -> OK`

![Buoc3_2.png](Image%2FBuoc3_2.png)

#### Bước 4: Tạo remote repository trên GitHub và liên kết với local repository
* Bấm vào biểu tượng 3 chấm phía trên bên trái
* Chọn `Git -> GitHub -> Share Project on GitHub`

![Buoc4_1.png](Image%2FBuoc4_1.png)

* Nhập thông tin và nhấn `Share`

![Buoc4_2.png](Image%2FBuoc4_2.png)

#### Bước 5: Thêm file vào staging area
Trước khi push project từ local repository lên remote repository, ta cần add những file muốn theo dõi (tracked files) vào staging area, ta thực hiện:
* Tại mục Project, chọn `main.py`
* Bấm chuột phải, chọn `Git -> Add`

![Buoc5.png](Image/Buoc5.png)

#### Bước 6: Commit để lưu các thay đổi từ staging area vào local repository
Sau khi add tracked files vào staging area, ta thực hiện:
* Tại mục Commit, chọn `main.py`
* Nhập Commit Message như `“Initial commit”` và bấm `Commit`

![Buoc6.png](Image%2FBuoc6.png)

#### Bước 7: Push local repository lên remote repository
Cuối cùng, ta push local repository lên remote repository trên GitHub bằng cách 
chọn `master -> Push`

![Buoc7.png](Image/Buoc7.png)

### II. Sử dụng Git cài riêng bên ngoài
=> Đang cập nhật

