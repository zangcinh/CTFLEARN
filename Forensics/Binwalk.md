# Overview #
`30points`

# Descripion#
Here is a file with another file hidden inside it. Can you extract it? https://mega.nz/#!qbpUTYiK!-deNdQJxsQS8bTSMxeUOtpEclCI-zpK7tbJiKV0tXYY

# Writeup #
Sử dụng `binwalk` để kiểm tra, ta thấ có file ẩn trong ảnh
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/0b532f8a-c259-4b55-bf3f-7d0ed9c2c510)

Sử dụng `binwalk -D = '.*' PurpleThing.jpeg` để giải nén 
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/96d69fcd-9a77-482d-962a-f0621754f1cd)

Mở file vừa được giải nén ra ta có flag 
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/eec2b937-a6ba-42d7-9aa8-649458fba267)
