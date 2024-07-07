# Overview #
`30points`

# Overview #
Think the flag is somewhere in there. Would you help me find it? hint-" Steghide Might be Helpfull"

# Description #
Cần sử dụng streghide để trích xuất dữ liệu từ ảnh nên ta cần passphrase
Sử dụng `strings` thấy `myadmin` 1 chuỗi kí tự cố thể đọc được -> có thể là passphrase
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/ac13ee7b-29dc-47a2-a380-812a84a4555b)

`steghide extract -sf Minions`.jpeg` 

Decode bằng base64 ta được flag

![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/bcd306cb-2704-4384-8983-4a78a7be4a7f)

`CTFlearn{this_is_fun}`
