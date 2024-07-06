# Overeview #
`20points`

# Description #
The flag is hidden inside the Penguin! Solve this challenge before solving my 100 point Scope challenge which uses similar techniques as this one.

# Writeup #
`binwalk Tux.jpg` ta thấy có file zip ở trong ảnh
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/e6352adf-e372-4bd6-bcf2-df9240445061)

`unzip Tux.jpg`

![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/6753e157-2737-46ef-ad80-d704e272e721)

Ta cần tìm password để mở file

`file Tux.jpg` 
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/14acbbb7-6c9f-49a5-b387-992020fbe89c)

Ở phần comment có 1 đoạn code. Phần này đã được encode bằng base64. Sau khi decode ta được password
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/12955d94-7c91-4d50-bb43-e59ed21a487a)

Sau khi nhập password xuất hiện file flag
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/a0dd0409-4c3f-4dbf-8954-40a291f3b51c)

![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/d6f67dd6-bc4d-4584-8458-752a571bf7be)
