# BÀI TẬP VỀ NHÀ 03 - MÔN HỆ QUẢN TRỊ CSDL:
## Bài tập 03 của sinh viên: K225480106054-Nguyễn Thị Xuân Phương - Môn Hệ quản trị CSDL

## DEADLINE: 23H59 NGÀY 30/03/2025

## ĐIỀU KIỆN: (ĐÃ LÀM XONG BÀI 2)

## BÀI TOÁN: Sửa bài 2 để có csdl như sau:
  + SinhVien(#masv,hoten,NgaySinh)
  + Lop(#maLop,tenLop)
  + GVCN(#@maLop,#@magv,#HK)
  + LopSV(#@maLop,#@maSV,ChucVu)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + Khoa(#maKhoa,tenKhoa)
  + MonHoc(#mamon,Tenmon,STC)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + DKMH(#id_dk, @maLopHP,@maSV,DiemThi,PhanTramThi)
  + Diem(#id, @id_dk, diem)

## YÊU CẦU:
1. Sửa bảng DKMH và bảng Điểm từ bài tập 2 để có các bảng như yêu cầu.
2. Nhập dữ liệu demo cho các bảng (nhập có kiểm soát từ tính năng Edit trên UI của mssm)
3. Viết lệnh truy vấn để: Tính được điểm thành phần của 1 sinh viên đang học tại 1 lớp học phần.

## HÌNH THỨC LÀM BÀI:
1. Tạo file bai_tap3.md trên cùng repository của bài tập 2:
   Nội dung chứa đề bài, và ảnh chụp quá trình thao tác các yêu cầu khác.
2. Chụp ảnh quá trình sửa bảng DKMH và quá trình thêm bảng Diem, chú ý @ là FK, và thêm CK cho trường điểm
3. Hình sau khi chụp paste trực tiếp vào file bai_tap3.md trên github, cần mô tả các phần trên ảnh để tỏ ra là hiểu hết!
4. dùng tính năng: Tasks -> Generate Scrips => sinh ra file: bai_tap_3_schema.sql  (chỉ chứa lệnh tạo cấu trúc của db)
5. dùng tính năng: Tasks -> Generate Scrips => advance => Check Data only => sinh ra file: bai_tap_3_data.sql  (chỉ chứa dữ liệu đã nhập demo vào db)
6. Tạo diagram mô tả các PK, FK của db. Chụp hình kết quả các bảng có các đường nối 1-->nhiều
7. upload 2 file  bai_tap_3_schema.sql và bai_tap_3_data.sql lên repository.
8. nhớ commit để save nội dung file bai_tap3.md
   ![Ảnh chụp màn hình (786)](https://github.com/user-attachments/assets/89791072-023f-4baa-9c1b-0bd0274e65de)
   ![Ảnh chụp màn hình (787)](https://github.com/user-attachments/assets/1103f67e-9d8b-4af4-8f02-f2257b0b0676)
![Ảnh chụp màn hình (788)](https://github.com/user-attachments/assets/c1c34410-c04b-46fe-927c-50e22a3afc4c)
![Ảnh chụp màn hình (789)](https://github.com/user-attachments/assets/95f4670a-07b7-494c-a459-f34205362f87)
![Ảnh chụp màn hình (790)](https://github.com/user-attachments/assets/82b82806-c86e-4a65-8ce9-484d5dfcac02)
![Screenshot 2025-03-31 000038](https://github.com/user-attachments/assets/6bb82b69-f9ec-4b2c-958b-33cb57db5ac5)
