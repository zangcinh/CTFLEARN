# Overview #
`30points`

# Description #
I found an interesting game made by some guy named "John_123". It is some betting game. I made some small fixes to the game; see if you can still pwn this and steal $1000000 from me!
To get flag, pwn the server at: nc thekidofarcrania.com 10001

# Writeup #
Nếu để đoán trúng được con số trong game thì dựa vào may mắn hoặc rất khó để đoán để được $1000000
Vì vậy ta sẽ thử cược 1 con số âm 
![image](https://github.com/zangcinh/CTFLEARN/assets/173159694/46b0a9d6-8e75-4ed3-bca1-c8fea138821f)

Game này có 1 lỗ hổng là chỉ cần số dưới 500 là nó đều nhận. Nếu người chơi thua sẽ thì số dư - số cược = số còn lại -> Ta sử dụng mánh khóe này

