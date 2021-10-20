# Author: Iluvinn
# Overview
Khi kết nối tới server ta sẽ được chơi 1 game mô phỏng cày cấp đánh boss và yêu cầu đó là tiêu diệt ma vương Iluvinn
```
iluvinn in ~/miniCTF2021 λ nc 150.230.217.225 10004
*======================  WELCOME  ======================*
* This world is dominated by Iluvinn aka Demon Lord     *
* He had weird power called AMATERASU, it's a black fire*
* which can burn anything in his sight                  *
* People are dying day by day. Many heroes tried to     *
* defeat him but all died. Can you defeat him to bright *
* peace back to this world!!!                           *
*=======================================================*
----------------- Please choose one -------------------
| 1. Adventurer                                         
| 2. Trader                                             
-------------------------------------------------------
>
```

# Solve
Khi chọn 2 ta lập tức bị ngắt kết nối với server cùng với thông báo no flag for you
```
----------------- Please choose one -------------------
| 1. Adventurer                                         
| 2. Trader                                             
-------------------------------------------------------
> 2
===================- NOTIFICATION -====================
| So boring~~~~~
| No flag for you!!!!
-------------------------------------------------------
```
Khi chọn 1 game sẽ yêu cầu ta nhập tên sau đó 1 menu sẽ hiện ra
```
----------------- Please choose one -------------------
| 1. Adventurer                                         
| 2. Trader                                             
-------------------------------------------------------
> 1
----------------- What's your name? -------------------
> B4n4n4
=======================  TOWN  ========================
--------------------  PROPERTIES  ---------------------
| name: B4n4n4
| level : 1
| exp : 0/10
| atk : 100
-------------------------------------------------------
-------------------------------------------------------
| What do you want to do? 
| 1. Fight 
| 2. Train 
| 3. Guide 
-------------------------------------------------------
> 
```
Ở đây ta có các option là Fight, Train, Guide
Chọn Guide cho ta 1 số thông tin hướng dẫn cơ bản về game
```
> 3
$===================  ROAD TO HERO  ==================$
| Each time you lv up 
|  - ATK up 
|  - Get more EXP 
| 
| In 'Fight' you can choose fight with monster to get 
| more exp or fight with the boss
| 
| In 'Train' you can convert your exp to atk point
| 
| Train youself but be smart 
| ILUVINN is very scare of HEALING 
$=====================================================$
```
Ta biết được thêm 1 số thông tin như sau: <br>
`Fight`: cho phép ta chọn lựa đánh boss hoặc farm quái để tăng exp
```
======================== JUNGLE =======================
| 1. Fight monster                                    |
| 2. Fight Boss                                       |
=======================================================

```
`Train`: cho phép ta chuyển đổi lượng exp đang có thành điểm atk nhưng không thể vượt quá lượng kinh nghiệm đang có
Sau khi thử vào ngó mặt ma vương thì số hp của ma vương lên tới con số là 2 tỉ
```
$======================  BOSS ROOM  ==================$
| Dealing 101 damage to boss
| Iluvinn's hp remain: 1999999899
| Iluvinn is using AMATERASU, pls RUN 
$=====================================================$
```
Nhưng với tình hình phải giải quyết nhanh gọn thì không thể đi farm quái lên cấp được, vậy ta cần chú ý dòng in đậm cuối cùng trong phần `Guide`
```
| Train youself but be smart 
| ILUVINN is very scare of HEALING 
```

Và thử nghiệm cho thấy ta có thể chuyển lượng kinh nghiệm thành điểm atk với số âm :>

```
-------------------------------------------------------
| What do you want to do? 
| 1. Fight 
| 2. Train 
| 3. Guide 
-------------------------------------------------------
> 2
----------------------  TRAINING ----------------------
Enter amount exp to atk point
 > -99999999999
You input: -99999999
===================- NOTIFICATION -====================
|                      LEVEL UP              
| ATK : -99999898 => -99999798
| EXP get: 1 => 11
-------------------------------------------------------
=======================  TOWN  ========================
--------------------  PROPERTIES  ---------------------
| name: B4n4n4
| level : 2
| exp : 99999989/30
| atk : -99999798
-------------------------------------------------------
```
Gọi ma vương ra đây :v 
```
======================== JUNGLE =======================
| 1. Fight monster                                    |
| 2. Fight Boss                                       |
=======================================================
> 2
$======================  BOSS ROOM  ==================$
| Dealing -99999648 damage to boss
| Iluvinn's hp remain: 2099999547
| Iluvinn is using AMATERASU, pls RUN 
$=====================================================$
```
A: Ok giờ nó hơn 2 tỉ máu r đấy bro giờ sao nữa <br>
B: Đánh tiếp! hồi máu cho nó tiếp!
```
======================== JUNGLE =======================
| 1. Fight monster                                    |
| 2. Fight Boss                                       |
=======================================================
> 2
$======================  BOSS ROOM  ==================$
| Dealing -99999448 damage to boss
$=====================================================$
You defeated the boss, here you flag: ISPCLUB{h34L_15_p0w3R}
```
Đây là 1 lỗi được gọi là [`interger overflow`](https://en.wikipedia.org/wiki/Integer_overflow) đơn giản thì khi giá trị vượt quá ngưỡng giới hạn trên thì giá trị hiện tại sẽ trở về mốc giới hạn dưới


Flag: ISPCLUB{p0w3R_oF_l0V3!!!}

