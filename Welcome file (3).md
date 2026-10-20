# BÀI LÀM – ÔN TẬP NGÀY 1



-   **Họ tên:** Nguyễn Thị Ngọc Ánh
-   **Lớp:** CNTT1
-   **Link repository:**
-   **Hệ điều hành (Windows/macOS):** windows

## Phần A. Tổ chức thư mục bằng GUI

[](https://github.com/maivietdung45-create/CNTT1_Nhap-mon-CNTT_On-tap-Ngay1/blob/main/bai_lam_ngay1.md#ph%E1%BA%A7n-a-t%E1%BB%95-ch%E1%BB%A9c-th%C6%B0-m%E1%BB%A5c-b%E1%BA%B1ng-gui)

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

[](https://github.com/maivietdung45-create/CNTT1_Nhap-mon-CNTT_On-tap-Ngay1/blob/main/bai_lam_ngay1.md#ph%E1%BA%A7n-b-thao-t%C3%A1c-b%E1%BA%B1ng-cli)

### Các lệnh đã chạy (B1–B7)

[](https://github.com/maivietdung45-create/CNTT1_Nhap-mon-CNTT_On-tap-Ngay1/blob/main/bai_lam_ngay1.md#c%C3%A1c-l%E1%BB%87nh-%C4%91%C3%A3-ch%E1%BA%A1y-b1b7)

pwd
ls -force
mv lich_hoc.txt docs,anh_lop_hoc.jpg media
cp media/logo_trung_tam.png archive
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls
cd ..
cd docs
cp ../media/anh_lop_hoc.jpg ../archive
cd ..

### Kết quả B1 (pwd)

[](https://github.com/maivietdung45-create/CNTT1_Nhap-mon-CNTT_On-tap-Ngay1/blob/main/bai_lam_ngay1.md#k%E1%BA%BFt-qu%E1%BA%A3-b1-pwd)

```
Path
----
C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh


```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

[](https://github.com/maivietdung45-create/CNTT1_Nhap-mon-CNTT_On-tap-Ngay1/blob/main/bai_lam_ngay1.md#k%E1%BA%BFt-qu%E1%BA%A3-li%E1%BB%87t-k%C3%AA-to%C3%A0n-b%E1%BB%99-d%E1%BB%B1-%C3%A1n--b8-windows-get-childitem--recurse--force-macos-ls--ar)

```
    Directory: C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026  14:29PM                archive
d-----        10/20/2026   14:24PM             data
d-----        10/20/2026   14:39AM                docs
d-----        10/20/2026   14:44PM                logs
d-----        10/20/2026  15:29 PM                media
-a----        10/20/2026   15:55PM            83 .env
-a----        10/20/2026   15:55 PM            902 bai_lam_ngay1.md


    Directory: C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   14:20 PM 
          13559 anh_lop_hoc.jpg
-a----        10/20/2026   14:20 PM           5184 logo_trung_tam.png


    Directory: C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   14:20 PM         5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   14:20 PM           
 67 lich_hoc.txt


    Directory: C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   14:20 Pm           1072 access.log


    Directory: C:\Users\ZBOOK\Downloads\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   14:20 PM         13559 anh_lop_hoc.jpg
-a----        10/20/2026   14:20 PM          5184 logo_trung_tam.png


```



