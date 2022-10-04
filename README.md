# VCS_PROG03

sshtrojan1
-	Sửa file config của PAM và dùng module pam_exec để thực hiện log password login được
![image](https://user-images.githubusercontent.com/80744099/193728179-47f9d0da-81dc-4565-919a-0c8af5ceb8e0.png)
-	Dùng module auth để kết nối với expose_authtok  để chạy lệnh shell $file_exec đọc password từ input nhập vào 
-	Kết quả sẽ được lưu vào file $file_log
-	PAM_USER là biến môi trường của auth
-	Password được lấy từ input nhập vào