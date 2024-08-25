# Để trang ngôn ngữ tiếng anh (gốc) Không nhấn dịch trang sang Tiếng Việt vì sẽ có nguy cơ bị lỗi


## Xem trước sau khi thiết lập hoàn tất...
<img src="https://raw.githubusercontent.com/TruongPixel/Img/main/IMG_20240825_134451.jpg" width="200" hight="220">



## Các bước tải xuống và cài đặt
<img src="https://raw.githubusercontent.com/TruongPixel/Img/main/IMG_20240825_134522.jpg" width="200" hight="220">


## 1.
 ```
apt update && yes | apt upgrade && apt update && apt install git -y
```
## 2.
```
cd /sdcard/download
```
## 3.
```
git clone https://github.com/truongpixel/Setup.git
```
## 4.

```
cd Setup/
```
## 5.( Không hẳn cần thiết )
```
ls
```
## 6.
```
bash tep.sh
```
## 7. Sau khi hoàn tất mọi xử lý chỉ cần - mở phiên mới - hoặc nhập
```
source ~/.zshrc
```
## 8. Để đổi lại tên ( Nếu cần thay tên )
```
cd /sdcard/download/setup && python rename.py && source ~/.zshrc
```
## 9. Để loại bỏ Tool ( Về ban đầu )
```
cd /sdcard/download/setup && bash tep.sh --remove && exit
```

## Video hướng dẫn có sẵn trên kênh YouTube
 { [Bấm vào đây](https://youtu.be/8Duxj_-b4og) }

## CHÚC CÁC BẠN THÀNH CÔNG
