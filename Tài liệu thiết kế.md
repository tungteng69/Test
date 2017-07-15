# Tài liệu thiết kế
Đây là tài liệu phân tích thiết kế hệ thống trước khi bắt tay và xây dựng phần mềm
## Đặc tả hệ thống
- Hệ thống quản lý sinh viên này chỉ dành cho một lớp người sử dụng (Phòng đào tạo) nên không thực hiện chức năng phân quyền.
- Hệ thống thực hiện các chức năng **Quản lý sinh viên**, **Quản lý điểm**, **Quản lý môn học**, **Quản lý Khoa/Lớp**, **Tìm kiếm** và **Báo cáo - Thống kê**.
- Tất cả những thay đổi tác động qua từng chức năng đều ảnh hưởng đến **Cơ sở dữ liệu**.
## Sơ đồ phân rã chức năng (BFD)
![screenshot 21](https://user-images.githubusercontent.com/27407242/28238962-187324aa-698a-11e7-8274-a469020e8b07.png)
## Sơ đồ luồng dữ liệu (DFD)
![screenshot 22](https://user-images.githubusercontent.com/27407242/28239243-c5798dea-6991-11e7-803e-c6e6dc0fb12e.png)
## Sơ đồ thực thể - quan hệ (ERD)
![erd](https://user-images.githubusercontent.com/27407242/28239269-762657ae-6992-11e7-8aa9-883bbc7041d1.JPG)
## Thiết kế và mô tả mô hình dữ liệu vật lý
| Column Name | Data Type | Allows NULL |
|-------------|-----------|-------------|
| Mã giảng viên | nvarchar(10) | NOT NULL |
| Tên giảng viên | nvarchar(10) | NULL |
