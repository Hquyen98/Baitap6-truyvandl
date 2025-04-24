# Baitap6-truyvandl

Bài tập 6: Hệ quản trị CSDL
Chủ đề: Câu lệnh Select
Yêu cầu bài tập: 
Cho file sv_tnut.sql (1.6MB)
1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)
3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
5. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
6. nhập sql để tìm xem có những sv nào trùng tên với em?
7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)

DEADLINE: 23H59:59 NGÀY 25/4/2025

Ghi chú: Giải thích tại sao lại có SQL như vậy.



# Bài làm

1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
   - Tải file sv_tnut.sql
   - Tạo database mới (có thể tạo bằng lệnh CREATE DATABASE sv_tnut;
                                             GO )
   - Mởi file






     ![image](https://github.com/user-attachments/assets/8b3b38ac-d00f-4cb3-8805-2447e2f363a7)




   - Chạy file đã mở







       ![image](https://github.com/user-attachments/assets/2ef971c7-8b0c-467a-b87a-a6464bc3eb3a)







     - Sau khi chạy ta được CSDL như hình bên dưới
    






        ![image](https://github.com/user-attachments/assets/b358a22c-9de8-4953-9786-9be7c4915ec3)






       


2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)





   ![image](https://github.com/user-attachments/assets/01cca7e6-e16b-4d66-9173-507865f94c73)





3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?





   ![image](https://github.com/user-attachments/assets/200cd4da-78cf-4599-bfc2-5d7b821ea848)





4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?







![image](https://github.com/user-attachments/assets/dcef16ca-2921-4301-9621-3da8e394b158)







5. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?






![image](https://github.com/user-attachments/assets/d88db5df-1359-4f94-ac8b-179bca1a3848)






6. nhập sql để tìm xem có những sv nào trùng tên với em?







![image](https://github.com/user-attachments/assets/599dcfd1-2beb-42bb-8306-e4fd4e8fb27e)







7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.






   ![image](https://github.com/user-attachments/assets/0343c42f-cdb9-4579-9224-68a369406a86)







8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.







   ![image](https://github.com/user-attachments/assets/b7b32f94-c399-4081-ac1d-6075fe9fa8a5)








9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
  






   ![image](https://github.com/user-attachments/assets/0a9f2fbb-a8f3-42cd-888c-3b09b2421a92)





10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)


   Để tìm danh sách các bạn nữ học ngành KMT mà không có cột giới tính, ta có thể suy luận như sau:
   - Thường tên các bạn nữa sẽ có chữ "Thị" ta sẽ có thể tìm thông qua việc này, nhưng như vậy sẽ không thể hết tất cả vì vậy
   ta sẽ thêm một số đệm hay thấy như: Anh, Ngọc, Như, Phương.... để truy vấn.
   - Nhưng giả như có bạn tên Anh Tuấn, Như Khiêm là con trai chúng ta sẽ loại bỏ một số tên thường gập như vậy đi.
   - Việc làm như vậy sẽ lọc ra được một danh sách tương đối đúng vì có thể sẽ thiếu 1 số bạn là con gái nhưng tên giống tên
  thường đặt cho nam và ngược lại
    => Kết quả không được tối ưu hay không thể chính xác.



       ![image](https://github.com/user-attachments/assets/110a23bf-573c-4e80-99bd-eabf03801ef9)























   



