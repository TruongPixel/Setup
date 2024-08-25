# Thiết lập tập lệnh
This Bash script contains Oh-My-Zsh With, command autosuggestion, syntax highlight plugins and terminal header with own name for TERMUX. 
## Xem trước sau khi thiết lập hoàn tất...
<img src="https://raw.githubusercontent.com/TruongPixel/Img/main/IMG_20240825_134451.jpg" width="200" hight="220">

## Tập lệnh này chứa các tính năng phổ biến

- [x] oh-my-zsh themes
- [x] zsh-autosuggest-command plugins
- [x] zsh-syntax-highlighting plugins
- [x] termux-banner
- [x] PS1 with custom trim path indicator
- [x] Custom prompt cursor
- [x] other (git prompt)

## Các tính năng của bàn phím Termux với các phím tắt

- [x] open new session `CTRL + t`
- [x] close terminal <sub><sub><img src="https://raw.githubusercontent.com/google/material-design-icons/master/symbols/web/keyboard/materialsymbolsoutlined/keyboard_20px.svg"></sub></sub> swipe up throughout that icon
- [x] swich between two sessions `CTRL + 4` and `CTRL + 5`
- [x] other shortcuts need video guide.

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
