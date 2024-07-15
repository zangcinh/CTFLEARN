# Overview #
`40points`

# Description #
This website requires authentication, via POST. However, it seems as if someone has defaced our site. Maybe there is still some way to authenticate? http://165.227.106.113/post.php

# Writeup #
Khi kiểm tra source page ta thấy được thông tin sau
`username: admin | password: 71urlkufpsdnlkadsf`
Sử dụng câu lệnh 
`curl -X POST http://165.227.106.113/post.php -d "username:admin&password:71urlkufpsdnlkadsf"` ta được flag
![image](https://github.com/user-attachments/assets/41e5f040-fd79-43d4-b640-dbe159ef7ba7)
