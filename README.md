# cloudwifi
 Ez Master Cloud AccessPoint - Cloud Wifi

0. Download:

1. 7.zip Open Archive > Extract ezMaster_Rel_v1.0.54.ova 
- Import to VM of VMware Workstation Pro 16.x > VM 80GB thin disk.
- OS: Debian, GNOME Open BSD, SSHD.
2. Stop VM on Workstation Pro and Export to File OVA.
3. Open 7.zip Open Archive > Edit file OVF

![image](https://user-images.githubusercontent.com/106635733/211181099-aee10386-94d2-4567-9cca-ce39bf5eff0e.png)

Sửa lại giá trị  vmx-18  thành vmx-15

![image](https://user-images.githubusercontent.com/106635733/211181122-f61d0168-2da6-460e-8abd-b661fd3e8789.png)

Sau đó lưu lại file Ezmaster *.ovf đã sửa  (bấm phím Ctrl+S)

Tiếp tục bấm OK để lưu cập nhật vào file OVA

![image](https://user-images.githubusercontent.com/106635733/211181153-593f4ddc-e6ec-429c-87a7-0d8d2e8cedf3.png)

Cuối cùng là đóng File 7.zip đang mở.

Ở trên ESXi Host bấm nút phải chuột chọn Create/Register VM

![image](https://user-images.githubusercontent.com/106635733/211181228-b8b94d11-0a12-4b5d-845e-6f1d5ac40714.png)
Chọn Deploy VM:

![image](https://user-images.githubusercontent.com/106635733/211181252-158490c0-123f-42b3-8484-0db959e1296b.png)

Bấm next để tiếp tục

![image](https://user-images.githubusercontent.com/106635733/211181272-5d33202d-fcba-48c6-961e-b82d0b3bb0e1.png)
![image](https://user-images.githubusercontent.com/106635733/211181280-ed8c5494-47df-445f-b466-eae367d1b230.png)
![image](https://user-images.githubusercontent.com/106635733/211181288-41762312-4232-4e80-8246-01e85feb353b.png)
