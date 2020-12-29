#### Server Requirements
- PHP version 5.6.20 or greater, PHP 7 is highly recommended
- Web Server: Apache or Nginx
- Database: MySQL version 5.0. 15 or greater or any    version of MariaDB.
- (Optional) (Required for Multisite) Apache mod_rewrite module (for clean URIs known as Permalinks)

#### Install 
1. Clone source code  or create new project in folder your web server.
[link source here](https://github.com/shirleyskey/qlsv_xyz)

2. Import .SQL file into new database
- Create new database with 'database name'
- Import file test.sql in root derectory into database

3. Edit URL web application 
- Go to config/config.php edit $url 
- Go to header.php edit $url 

4. Login 
- username: dungbt
- pass: shishi

#### Features
###### 1 Quản Lý Admin
```
Bảng Điều Khiển -> Admin
```
###### 2 Quản Lý Khoa 
```
BẢng Điều Khiển -> Quản Lý Khoa
```
###### 3 Quản Lý Lớp
``` 
Bảng Điều Khiển -> Class
```

###### 4 Quản Lý Học Kỳ
```
BẢng Điều Khiển -> Quản Lý Khoa -> Semester
```
###### 5 Quản Lý Sinh Viên 
```
Bảng Điều Khiển -> Student -> Chọn Lớp 
```

###### Xem Điểm Sinh Viên 
```
- Bảng Điều Khiển -> Student -> Chọn Lớp 
- Click Mã Sinh Viên
- Chọn Học Kỳ

