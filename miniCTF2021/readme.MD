# miniCTF 2021

Để chào mừng các tân sinh viên và những người có đam mê và muốn tìm hiểu về Cyber Security, ISP Club chúng mình đã tổ chức cuộc thi thường niên miniCTF và đây là writeup cho miniCTF năm 2021.

### Firstlooking  
![](/miniCTF2021/miniCTF2021_file/1.png)
### Overview
 | Title | Category | Flag
 | ------ | ------  | ------ |
 | [Discord](#welcome-discord) | Welcome |  `ISPCLUB {4r3_y0u_r34dy}` |
 | [Dōnyū](#welcome-dōnyū) | Welcome | `ISPCLUB{900D_LUCK_B4BY}` |
 | [Chuunin Exam](#crypto-chuunin-exam) |Crypto	| `ISPCLUB{s3cr3t_pr0t3ct0r}` |
 | [Base no Jutsu](#crypto-base-no-jutsu) | Crypto |  `ISPCLUB{b4s3_1s_n0t_tk4t_d1ff1cult}` |
 | [Gravity Falls Bill](#crypto-gravity-falls-bill) | Crypto |  `ISPCLUB{BJLL_CJPKER}` |
 | [Covi no Dokumushi](#forensic-covi-no-dokumushi) | Forensic | `ISPCLUB{11919}` |
 | [Daichidoukaku](#forensic-daichidoukaku)| Forensic |  `ISPCLUB{5p1it_91f}` |
 | [Sagasu no Jutsu](#forensic-sagasu-no-jutsu) | Forensic |  `ISPCLUB{5uck_4_l0n9_w4y}` |
 | [Rasen...Deku](#forensic-rasendeku) | Forensic |`ISPCLUB{m4q3ky0u_sk4rjnq4n}` |
 | [Baika](#forensic-baika) | Forensic |  `ISPCLUB{ch0_b41k4_n0_jut5u}` |
 | [Chess but not so Stress](#general-skill-chess-but-not-so-stress) |General skill|`ISPCLUB{G4MB1T_QU3EN}` |
 | [Earth Hour](#general-skill-earth-our) | General skill| `ISPCLUB{OUREARTH}` |
 | [Himitsu No Ninmu](#general-skill-himitsu-no-ninmu) | General skill| `ISPCLUB{w3lc0me_t0_1nn3r_s4nCtuM}` |
 | [Start the new schoolyear](#general-skill-start-the-new-schoolyear) | General skill |`ISPCLUB{L1nux_1z_v3ry_c0nV3n1EnT}` |
 | [Sasuke’s Paw Encyclopedia](#general-skill-sasukes-paw-encyclopedia) | General skill | `ISPCLUB{SO_WEIRD_CAT}` |
 | [Faster!!!](#general-skill-sasukes-paw-encyclopedia) |Misc | `ISPCLUB{r1ck_r0ll_4g41n}`|
 | [First Generation](#misc-first-generation) | Misc | `ISPCLUB{CAPTURE_THE_FLAG}` |
 | [Kakuremino no Jutsu](#misc-kakuremino-no-jutsu) | Misc |`ISPCLUB{h1d3_f1l3_1n_p1ctur3}`|
 | [Honest or Tricky](#programming-honest-or-tricky-tricky-or-honest) | Programming | `ISPCLUB{m4th_f0R_dUmm13S!!!!!!!}` |  
 | [Tricky or Honest](#programming-honest-or-tricky-tricky-or-honest) | Programming | `ISPCLUB{F45T_a5_71ghtN1n9!!!!}` |
 | [Reverse no Jutsu](#re-reverse-no-jutsu) | RE |`ISPCLUB{s3xY_n0_jnt5u_K4i_h4r3m}` |
 | [Kakureru](#re-kakureru) | RE |`ISPCLUB{W3ll_c0m3_t0_r3vers!n9}` |
 | [Furipputon - Reveal of the Truth](#re-furipputon---reveal-of-the-truth) | RE  |`ISPCLUB{DekuHoho}`|
 | [Isekai with truck-kun](#warm-up-isekai-with-truck-kun) | Warm up |`ISPCLUB{p0w3R_oF_l0V3!!!}`|
 | [PHP no jutsu](#web-php-no-jutsu) | Web | `ISPCLUB{php_1s_Suck}`|
 | [Deku's Bird](#web-dekus-bird)  | Web | `ISPCLUB{4_G00D_PL4Y3R}`|
 | [Kieru Odama Genso](#web-kieru-odama-genso) | Web | `ISPCLUB{c$$_!5_v3ry_34sy}`|
 | [Beginner](#web-beginner) | Web | `ISPCLUB{Not_the_first_time_huhh??}`|
 | [ISP Ichizoku SHOP](#web-isp-ichizoku-shop) | Web | `ISPCLUB{dung_gian_lan}`|
 | [Shinra Tensei](#web-shinra-tensei) | Web | `ISPCLUB{__H0W_TH3__F^CK_D1D__Y0U_93t__F14G_????}`|
 
 # Welcome: Discord

#### Challenge
Hành trình thu thập vô cùng nguy hiểm và khó lường. Hãy để gia tộc ISP giúp đỡ các bạn:
https://discord.gg/B7xFmWXp5F

#### Solution
Ở bài này mình có thể tìm thấy flag trong channels Rules của server discord [miniCTF2021](https://discord.gg/B7xFmWXp5F)

Flag: ``` ISPCLUB{4r3_y0u_r34dy} ```

# Welcome Dōnyū
#### Challenge
Bạn sắp đặt chân vào thế giới mới. Hãy khám phá nó ...

[Donyu.txt](miniCTF2021_file/Donyu/Donyu.txt)

#### Solution

Đọc đoạn text mà đề cho ta dễ dàng thấy được flag nằm ở cuối file.
```
Làng PTIT (PTITgakure)  từ lâu đã nổi tiếng với các thuật Phong Ấn do gia tộc ISP (ISP Ichizoku)  thực hiện.
Trước kia họ đã dùng chính thuật Phong Ấn của mình để phong ấn các nhẫn thuật cổ xưa, phân tán khắp Nhẫn giới và giam giữ trong các mê cung đầy bí hiểm mà người thường không thể xâm nhập được.
Tổ chức AkatXienPan được thành lập với mục đích thu thập lại các nhẫn thuật đó để gây ra chiến tranh, phá hủy thế giới. 1 thành viên cực mạnh của tổ chức này là Hiruyzawa Kuhan nay cũng đã khám phá rất nhiều mê cung và nắm cho mình rất nhiều nhẫn thuật mạnh.
Chính vì thế hãy luyện tập, level up kĩ năng, dấn thân đi khám phá các mê cung để thu thập lại các bí thuật trước khi Hiruyzawa Kuhan có được nó để đem lại bình yên cho làng PTIT cũng như gìn giữ hòa bình nơi Nhẫn giới nào!!!
ISP Ichizoku đã chuẩn bị một món quà nho nhỏ tặng bạn. Hãy thử làm quen với nó trước khi tham gia thu thập các bí thuật: ISPCLUB{900D_LUCK_B4BY}.
```
Flag: ``` ISPCLUB{900D_LUCK_B4BY} ```

# Crypto: Chuunin Exam
#### Challenge
Kỳ thi Chunnin sắp đến gần, hãy chuẩn bị thật tốt để có thể học hỏi từ các Genin khác và có cơ hội được thăng cấp trở thành Chunnin đầu tiên trong thế hệ D21 làng PTIT!

```$ nc 150.230.217.225 2026 ```  
#### Solution  
Sau intro ngắn thì ta thấy đề bài xuất hiện.  
  
## Stage 1  
  
```
***
First Stage: Written test

Given a ciphertext encrypted using the Roman method of cryptography...



My ciphertext:

Nofovyzon kbyexn 100 LM, xyd exdsv 9dr-moxdebi, Mkockb mszrob gkc mbkmuon gsdr dro nscmyfobi yp pboaeoxmi kxkvicsc.



What is the messages?
````  
  
Tra google với từ khoá tương tự với "Roman encrypt" ta có kết quả là mã hoá Caesar (Caesar Cipher) ở ngay trang đầu.
  
Mã hoá Caesar là kiểu mã hoá bằng phương pháp dịch các chữ cái trong bảng chữ cái đi k ký tự, với k là khoá của mã hoá. 
Ở bài này ta được cho một đoạn mật mã đã mã hoá, nhưng chưa biết key. Ta sẽ tiến hành brute key trong khoảng từ 1 - 25 (Do bảng chữ cái có 26 ký tự) để tìm ra bản rõ.  
  
Ở challenge này, key được sinh ngẫu nhiên. [Decrypt](https://cryptii.com/) với k = 16 ta có plaintext:
```
Developed around 100 BC, not until 9th-century, Caesar cipher was cracked with the discovery of frequency analysis.
```

## Stage 2  
```
***
Second Stage: Forest of Death

You have to bring your team's Scroll to the Building whose position is encrypted by an ancient Greek technique...



My ciphertext:

Lpn_oocScrrcatyyt_pte2tad0el_2dea6_ t_b _ey 



What is the messages?
```
Lần này thì từ khoá ta cần quan tâm sẽ là "Greek encrypt" và cũng dễ dàng xác định đó là kiểu mã hoá Scytale.
Đây là kiểu mã hoá của người Hy Lạp cổ, sử dụng một tấm vải mảnh dài và viết lẻ từng chữ cái lên trên "tấm vải" được tạo ra từ việc cuốn tấm vải quanh một đoạn gỗ. 
Sau khi viết xong, mảnh vải sẽ được gỡ khỏi đoạn gỗ và trở thành đoạn mã tối nghĩa nếu chỉ nhìn tấm vải.  
  
Để giải mã, ta sẽ cần tìm một "đoạn gỗ" có kích thước tương tự với đoạn mà người mã hoá đã sử dụng. [Giải mã](https://dencode.com/cipher/scytale) với "đoạn gỗ" có số ký tự trên một vòng cuốn key = 4 ta có plaintext:
```
Located_at_port_2026_encrypted_by_Scytale  
```

## Stage 3: Final
```
***
Final Stage: Team Fight

The key of teamwork in a fight is to communicate secretly.
This was created at the end of the First World War in German.



Your team using this machine:

_________________________________________________________________

Machine: Enigma M3, reflector UKW B
Rotor - Position - Ring: III - 9 - 3, II - 19 - 20, VI - 16 - 6 
Plugboard: dq cr bi ej kw mt os px uz gh
_________________________________________________________________



My ciphertext:
renoy begxr bczov ukkrg uasgc pkyjw sb



What is the messages? (remove spaces)
```

Tìm kiếm với từ khoá Enigma ta thấy đây là cơ chế mã hoá có nguồn gốc từ Đức, được sử dụng trong thế chiến I và thế chiến II rất nhiều.
Trong bài này thì ta đã được cho chi tiết các thông tin để [decode](https://cryptii.com/) Enigma rất dễ dàng.  
  
![Enigma Decode](/miniCTF2021/miniCTF2021_file/Chuunin-Exam/enigma.png)  
  
  
Plaintext:
```
enigmaisformilitarycommunication
```

Sau 3 stage ta đã vượt qua challenge và nhận được flag:
```
PTITkagure proud of you as a new Chuunin!
New S-rank Hiden Jutsu to you from ISP Ichizoku: ISPCLUB{s3cr3t_pr0t3ct0r}
```

Flag: ``` ISPCLUB{s3cr3t_pr0t3ct0r} ```
# Crypto: Base no jutsu
#### Challenge

Một bí thuật cơ sở bị trộn lẫn bởi Base Ichizoku để che giấu sự nhòm ngó của AkatXienPan!!! 

[Base_no_jutsu.txt](/miniCTF2021/miniCTF2021_file/Base/Baka_no_Jutsu.txt)

####  Solution

Đây là các base (là các hệ cơ số được dùng cho máy tính và mã hóa)
Ví dụ:  Base10 (DEC): 0,1,2,3,4,5,6,7,8,9

	Base2 (BIN): 0,1
	
	Base8 (OCT): 0, 1, 2, 3, 4, 5, 6, 7
	
Và 1 số base khác: Base16, base32, base64….

Sau khi mở file txt, đoạn mã được encrypt: 

```
SVNQQ0xVQns623473335f31735f6e30745fORVTI5C7MQYWMZRRMN2WY5D5
```

Đoạn mã “SVNQQ0xVQns” là base 64, decrypt ra: ISPCLUB{

Đoạn mã “623473335f31735f6e30745f” là base 16, decrypt ra: b4s3_1s_n0t_

Đoạn mã “ORVTI5C7MQYWMZRRMN2WY5D5” là base 32, decrypt ra: tk4t_d1ff1cult}

Flag: ```ISPCLUB{b4s3_1s_n0t_tk4t_d1ff1cult} ```

# Crypto: Gravity Falls Bill

#### Challenge

Đã nhiều lần ăn Ramen tại tiệm Ramen thương hiệu ISP Ichizoku, Deku Haha và bạn đến hôm nay mới để ý thấy rằng trong những tờ hóa đơn thanh toán của tiệm đều có những ký hiệu kỳ lạ. Nghe đồn đây là ấn chú mà chủ tiệm đã khắc lên để nhận biết xem tờ hóa đơn có bị sửa đổi không. Deku Haha thầm nghĩ nếu sắp tới xin gia nhập ISP Ichizoku mà biết được nó và cho vào CV thì rất có ích. Hãy giải mã nó cùng Deku Haha để làm đẹp CV sắp tới của mình nhé!!!

[encrypt.png](/miniCTF2021/miniCTF2021_file/Bill_cipher/encrypt.png)

#### Solution

Khi mở file ảnh mà đề cho, kết hợp với đoạn mô tả và tên của challenge. Ta có thể đoán được đây là mật mã bill cipher. Ở đây mình sẽ sử dụng tool [dcode.fr](https://www.dcode.fr/gravity-falls-bill-cipher) để có thể giải đoạn mã này.

![](/miniCTF2021/miniCTF2021_file/Bill_cipher/1.png)

Thêm các kí tự để đúng với đoạn mã đề cho và flag form. Ta được flag: ISPCLUB{BJLL_CJPKER}

Flag: ``` ISPCLUB{BJLL_CJPKER} ```

# Forensic: Covi no Dokumushi  

#### Challenge

Với cuốn bí thuật ăn cắp được từ Aburame Ichizoku, Hiruyzawa Kuhan đã sử dụng nó triệu hồi virus Covid tấn công PTITgakure. Ngày qua ngày số lượng ca nhiễm càng tăng lên đặt lên vai các y nhẫn giả một áp lực không hề nhẹ.  Theo thống kê, ngày 22/9 số lượng người được chữa khỏi là nhiều nhất. Là genin cũng như là người dân trong làng, liệu bạn có nắm bắt được có bao nhiêu người được chữa khỏi không ???


#### Solution

Đọc đề bài, ta thấy thấy ngay của flag cần tìm là số người đã được chữa khỏi Covid19 trong ngày 22/9. Theo đó, ta tra trên google thì số lượng người được chữa khỏi là 11919 người  
![](https://i.imgur.com/hlyVWxL.png)  
Flag: ``` ISPCLUB{11919} ```

# Forensic: Daichidoukaku 
#### Challenge
 Tam Vĩ đang nổi điên. Chắc chắn là do Hiruyzawa Kuhan đã cho nó say thuốc. Trong lúc đợi các y nhẫn giả đến và chữa trị cho nó, bạn và hàng trăm genin gần đó có nhiệm vụ cùng nhau thi triển 1 nhẫn thuật để mặt đất rung chuyển và tách ra nhằm làm kìm chân Tam Vĩ, không để nó tiến vào trong làng.
 
[Supuritto_no_Jutsu](img/Supuritto_no_Jutsu.gif)

#### Solution
- Từ file gif được cung cấp ta có thể thấy 1 mã QR thoáng qua rất nhanh.                   
![](/miniCTF2021/miniCTF2021_file/Daichidoukaku/img/Supuritto_no_Jutsu.gif)
- Từ đây có thể căn để dừng gif đúng lúc mã QR xuất hiện hoặc có thể dùng https://ezgif.com/split để tách gif 
![](/miniCTF2021/miniCTF2021_file/Daichidoukaku/img/1.png)
- Quét mã QR nhận được flag
- Flag: ``` ISPCLUB{5p1it_91f} ```

# Forensic: Sagasu no Jutsu

#### Challenge

Vẫn chứng nào tật nấy, Deku Haha chưa thể sửa được tính vụng về và thói quen để đồ đạc lộn xộn của mình. Lại 1 lần nữa cậu ta để chung nhẫn cụ triệu hồi với cuốn bí thuật trong túi của mình. Và lại 1 lần nữa cậu ta vô tình kích hoạt nhẫn cụ đó, cả 1 đống cuốn trục trông chả khác gì cuốn bí thuật lại hiện ra. Dù rất là phiền phức nhưng bạn hãy một lần nữa giúp cậu ta nhé!!!

[Sagasu no Jutsu](https://bit.ly/3AWwaCT)

#### Solution

Bài này khi giải nén tệp Maze_runner.rar ta được một list các folder và file nhỏ. Flag là một chuỗi ký tự vậy nên ta có thể thử dùng chức năng Search ở File Explorer để tìm toàn bộ file .txt `*.txt` cũng sẽ ra một vài file .txt và mở lần lượt sẽ thấy được flag.  
Đối với bài này thì phương pháp làm tay là 1 phương pháp không hiệu quả nếu phải tìm với số lượng lớn. Chúng ta sẽ dùng **CLI** (Command Line Interface) với các câu lệnh `findstr` hoặc `grep`. Về cơ bản thì mục đích sử dụng của 2 câu lệnh này là như nhau, dùng để tìm kiếm thông tin bên trong 1 file.  
Đầu tiên ta sẽ mở CLI tại thư mục cần tìm kiếm (cmd đối với windows và Terminal đối với Linux) sau đó dùng 1 trong 2 câu lệnh để tìm kiếm.

`findstr` đối với Windows: 

 ![](/miniCTF2021/miniCTF2021_file/Sagasu%20no%20Jutsu/1.png)
 
 `grep` đối với Linux

 ![](/miniCTF2021/miniCTF2021_file/Sagasu%20no%20Jutsu/2.png)

Flag: `ISPCLUB{5uck_4_l0n9_w4y}`  

# Forensic: Rasen...Deku

#### Challenge

Trong gia tộc của Deku có 1 bức tranh nổi tiếng bền nhất trong PTITgakure, rơi bao nhiêu lần không vỡ. Deku Haha đã sử dụng bức tranh làm bia đỡ khi luyện tập và chắc cũng muốn kiểm tra độ bền của nó. Vì dùng Rasengan hơi mạnh nên bức tranh đã bị thành ra như này. Hãy giúp Deku Haha khôi phục nguyên vẹn bức tranh nhé!!!

[Rasen...Deku](/miniCTF2021/miniCTF2021_file/Rasen/Deku_cukcuk.png)

#### Solution

Khi mở bức ảnh ta thấy bức ảnh đã bị xoáy khiến ta không thể đọc được nội dung trên bức ảnh. Ta chỉ cần xoáy bức ảnh lại để có thể đọc được flag. Ở đây mình dùng tool là [Photopea](https://www.photopea.com/). 

![](/miniCTF2021/miniCTF2021_file/Rasen/1.png)

Flag: ```ISPCLUB{m4q3ky0u_sk4rjnq4n}```

# Forensic: Baika 
#### Challenge
 Jicho - một người trong nhóm bạn của bạn, là 1 thành viên thuộc tộc Akimochi của PTITgakure. Jicho nói rằng người trong tộc Akimochi chỉ có thể sử dụng được thuật thay đổi kích thước cơ thể. Liệu có bí thuật nào có thể tháy đổi kích thước vật thể không ?

 [Baika](/miniCTF2021/miniCTF2021_file/Baika/img/2.png)
#### Solution
- Đề cho một hình ảnh:                                        
![](/miniCTF2021/miniCTF2021_file/Baika/img/4.png)
- Và dĩ nhiên flag hiện ra ngay trong ảnh là flag fake.
- Nhìn kỹ xuống mép dưới của ảnh ta có thể đoán được ảnh bị chỉnh kích thước nên không thể hiển thị hết.
- Sử dụng HXD cùng với kiến thức về IHDR chunk có thể dễ dàng chỉnh lại kích thước của ảnh:
![](/miniCTF2021/miniCTF2021_file/Baika/img/1.png)
- Flag xuất hiện sau khi ảnh được chỉnh:                                 
![](/miniCTF2021/miniCTF2021_file/Baika/img/3.png)
- Flag: ``` ISPCLUB{ch0_b41k4_n0_jut5u} ```

# General skill: Chess but not so Stress 

#### Challenge

Trong cuộc Đại chiến Ninja Lần thứ 4, Deku Haha đang trên đường làm nhiệm vụ tình báo thì gặp phải Nara Shikashisa, một nhẫn giả với IQ 5 chữ số được Orochimacho dùng "Thố Uể Chuyển Sinh" để hồi sinh nhằm chặn đường các nhẫn giả tình báo. Deku Haha phải giải câu đố sau đây của Shikashisa để tiếp tục nhiệm vụ. Đây là 1 bàn cờ vua khá lạ, Shikashisa muốn bạn sắp xếp lại các quân cờ theo 1 thứ tự "giá trị" nào đó và tìm thông điệp ẩn trong các quân cờ (nội dung flag) đó. Bạn có thể muốn đọc lại luật cờ vua cơ bản 1 chút đó :)  
![chess_but_no_stress.png](https://i.imgur.com/PY3MNzU.png)

#### Solution

:> Bài này thực ra không stress lắm đâu :>
![image](https://user-images.githubusercontent.com/72268643/137691220-2897f786-86fc-46a7-8390-76ecfc63efbf.png)

Để làm được bài này bạn chỉ cần nắm chắc được cái điều sau của luật cơ bản:
  + Trắng đi trước đen đi sau.
  + Giá trị 'sức mạnh' của các quân cờ.
![image](https://user-images.githubusercontent.com/72268643/137682677-345b2f5b-1194-478b-9c7b-3b8ec699a264.png)

Qua những manh mối đó, vì Tượng và Mã có giá trị cùng bằng 3 ta có thể sắp xếp các quân cờ theo 2 trường hợp: 

![image](https://user-images.githubusercontent.com/72268643/137687991-37cd75a4-a47b-4382-aec6-b9822748159d.png)

-> Tương ứng với 71 52 77 66 49 84 95 81 85 51 69 78

HOẶC 

![image](https://user-images.githubusercontent.com/72268643/137689551-0a5c71d5-7677-4fab-b429-f2fc78587d87.png)

-> Tương ứng với 71 52 49 84 77 66 95 81 85 51 69 78

Khi đã làm đến bước này thì các bạn chưa biết có thể xem hint hoặc là nhận ra được rằng đây là hệ cơ số 10. 
Sau khi chuyển sang ASCII đoạn nội dung trên, ta được: 
![image](https://user-images.githubusercontent.com/72268643/137690385-0890c9bc-bf5c-4581-8ff0-8fa2ed965e31.png)

Đây sẽ là flag đúng của chúng ta: `ISPCLUB{G4MB1T_QU3EN}` (và tất nhiên flag thứ 2 kia là flag đểu rồi :> )

# General skill: Earth Our

#### Challenge

Hôm nay là ngày Trái Đất! ISP Ichizoku đại diện cho PTITgakure soạn thư gửi tới rất nhiều các quốc gia khác trên Thế giới. Trong thư không chỉ nói lên thông điệp của các nhẫn giả PTITgakure mà còn bao gồm các quốc gia nhận được thư. Hãy xem xem bạn có hiểu được thông điệp của bức thư không nhé!

[messenger.txt](/miniCTF2021/miniCTF2021_file/Messenger.txt)

#### Solution

Khi tải file dưới đề bài ta được đoạn text sau:

`(41.406261, 13.670415) (5.202168, 46.911497) (-20.857119, -59.43613) (2.220493, -72.971320) (20.002158, 103.556915) (47.936819, 33.839043) (-15.149072, -56.503890) { (18.942883, 55.166555) (43.806953, 57.451712) (47.104862, 25.283979) (12.818703, 38.467574) (23.328579, 4.541791) (44.532888, 23.701948) (14.696728, 101.397263) (47.144076, 17.283236) }`
Nhìn đoạn text là ta đã nhận ra ngay các cặp số chính là tọa độ của 1 địa chỉ nào đó.
Thử tra cặp số đầu tiên xem ta được gì nào: 

![](https://i.imgur.com/DEc9gZp_d.webp?maxwidth=1520&fidelity=grand)
Để ý đọc lại đề bài ta sẽ nghĩ ngay đến những điểm đáng chú ý như thư gửi tới rất nhiều các **quốc gia**... bao gồm các **quốc gia**...

Note tên các quốc gia của các địa điểm đó lại ta được:

![](https://i.imgur.com/pbEUKTV.png)

Vì form flag là ISPClUB{} nên để ý các chữ cái trước dấu "{" ta sẽ thấy đó chính là chữ cái bắt đầu của tên các quốc gia đó.
Vậy là ta đã ra flag rồi. Yeah!!!

Flag: ``` ISPCLUB{OUREARTH} ```

# General Skill: Himitsu No Ninmu 

#### Challenge

Bạn nhận được một nhiệm vụ tuyệt mật từ PTITgakuge: liên lạc với gián điệp của làng đang nằm vùng trong tổ chức AkatXienPan để thu thập thông tin tình báo. Dưới đây là bức mật thư đầu tiên của gián điệp đó. Hãy giải mã nó và tìm ra địa điểm trao đổi thông tin nhé!!!

[Himitsu No Ninmu](https://pastebin.com/9ESeD3UB)

#### Solution
> Đây là một challenge bao gồm một chuỗi các câu đố, tập trung vào khả năng suy luận logic và kỹ năng tìm kiếm bằng Google.
- Truy cập thử link pastebin sẽ thấy câu đố đầu tiên:
![](img/1.png)
- Trong câu hỏi có nhắc đến:
> This number is generated by Tupper's formula
- Google nhanh Tupper's formula sẽ thấy đây là 1 công thức biểu diễn trực quan trên 1 vị trí cụ thể trong một mặt phẳng
- Đồng thời, cũng có thể thấy 1 tool online hỗ trợ tính toán và biểu diễn công thức này:
![](img/2.png)
- Sử dụng công cụ trên để biểu diễn số đã cho:
![](img/3.png)
- Có thể thấy đây là 1 link youtube với path /watch quen thuộc. Đi đến link youtube: https://www.youtube.com/watch?v=Ht_8roqxwLw
- Tại giây thứ 8 trong video có thể thấy có 1 hình ảnh hiện lên rất nhanh. Giảm tốc độ phát của video và dễ dàng lấy được hình ảnh đó:
![](img/4.png)
- Sử dụng các công cụ crop string từ image có sẵn trên internet sẽ dễ dàng lấy được string này:
> 31362d363a203439203438203435203530203538203332203438203534203534203438203534203532203438203535203530203439203530203530203439203533203533203439203533203532203439203534203533203439203531203439203439203530203535203439203534203535203438203534203534203439203439203439203439203438203535203439203533203438203438203534203438203439203532203532203439203439203438203439203438203530203439203535203530203439203439203535203439203533203439203438203535203438203439203534203534203439203532203531203439203438203535203439203438203534203439203535203530203439203532203532203439203438203535203439203530203534203439203533203439203439203532203439203439203530203535203438203534203532203439203534203533203439203531203439203438203534203530203438203535203439203439203534203532203439203439203532203438203534203438203439203533203438203439203531203438203439203532203531203439203439203438203439203530203530203439203534203535203439203530203534203439203530203534203439203439203530203438203534203438
- Dựa vào số ký tự xuất hiện trong string, có thể nhận thấy đây là 1 string được encode bằng hệ thập lục phân (hex). Sử dụng trang web [kt.gy]() để decode:
![](img/5.png)
- Sau khi decode hex sẽ thấy gợi ý tiếp theo là 16-6 => string được encode bằng hệ thập phân (dec). Tiếp tục decode dec:
![](img/6.png)
- Gợi ý tiếp theo là 10-2 => string được encode bằng hệ bát phân (oct). Decode oct:
![](img/7.png)
- Gợi ý tiếp theo là 64 => string được encode bằng base64. Decode base64:
![](img/8.png)
- Sau khi decode đước string, các bạn sẽ thu được link pastebin: [https://pastebin.com/HWptpURt](https://pastebin.com/HWptpURt)
![](img/9.png)
- Câu đố tiếp theo sẽ yêu cầu giải mã thông điệp tại [https://pastebin.com/Je5LZv4S](https://pastebin.com/Je5LZv4S)
![](img/10.png)
- Có thể thấy link pastebin ở cuối có dạng A9Bcdefg và thông điệp cho manh mối về các chữ a, b, c, d, e, f, g => Chúng ta cần tìm những chữ cái tại các vị trí a, b, c, d, e, f, g và thay vào link pastebin
- Dựa vào những manh mối được viết hoa, thử google với từ khóa END OF THE WORLD SLEEPING BEAUTY GENIUS LYRICS
![](img/11.png)
- Có thể thấy kết quả đầu tiên là lyrics bài hát Sleeping Beauty của nhóm End of the World tại trang web cung cấp lời bát hát genius.com
- Kết hợp cùng với các rule cho sẵn và hint dòng:chữ, có thể đoán tại mỗi vị trí a, b, c, d, e, f, g sẽ là 1 chữ cái trong lời bài hát này
- Thực hiện các rule đã cho: xóa dấu cách, xóa các ký tự đặc biệt, xóa các dòng có [] và viết thường toàn bộ chữ cái:
![](img/12.png)
- Tìm kiếm các chữ theo thứ tự ta sẽ thu được:
> a = 1:5 = chữ thứ 5 tại dòng 1 = s  
>b = 2:1 = chữ thứ 1 tại dòng 2 =d   
>c = 5:10 = chữ thứ 10 tại dòng 5 = h   
>d = 6:2 = chữ thứ 2 tại dòng 6 = f   
>e = 7:1 = chữ thứ 1 tại dòng 7 = a   
>f = 10:1 = chữ thứ 1 tại dòng 10 = y   
> g = 10:15 = chữ thứ 15 tại dòng 10 = c
- Từ đó có được link pastebin cần tìm: [https://pastebin.com/S9Dhfayc](https://pastebin.com/S9Dhfayc)
![](img/13.png)
- Câu đố tiếp theo yêu cầu tìm ra thông điệp của 1 tiếng ồn trong 1 file nhạc. Tiếng ồn đó được gợi ý là mo*se sound
- Nghe file nhạc sẽ thấy rằng tại phút 6:24 sẽ có 1 đoạn tiếng ồn nhẹ
- Google các từ khóa như là mose sound sẽ có thể google gợi ý đến morse sound:
![](img/14.png)
- Morse code là là một loại mã hóa ký tự dùng trong viễn thông để truyền các thông tin điện báo
- Như vậy câu đố yêu cầu thực hiện giải mã đoạn morse trong file nhạc
- Đến đây chắc hẳn nhiều bạn sẽ cố gắng thực hiện tách đoạn morse đó ra và giải mã nhưng mình tin rằng sẽ không có nhiều bạn sẽ giải mã được đoạn morse code này xD.
- Hãy nhớ rằng đây là 1 chall mình thiết kế để các bạn có thể google được :>
- Google với từ khóa: Is There Still Anything That Love Can Do-RADWIMPS morse sound. Các bạn sẽ bắt gặp 1 link reddit đã viết về vấn đề này:
![](img/15.png)
- Reddit là một mạng xã hội tương tự facebook. Ở đây có rất nhiều vấn đề khác nhau được cộng đồng mang ra mổ xẻ. Và tất nhiên vấn đề các bạn đang thắc mắc cũng không ngoại lệ:
![](img/16.png)
- Đây chính là lý do các bạn không thể giải được đoạn mã morse đó xD. Đơn giản bởi vì đây là mã morse sử dụng cho tiếng Nhật :>
- Sau khi giải mã được đoạn morse, các bạn sẽ thu được 1 chuỗi romanji: Ashita wa hareru yo
- Dựa vào các gợi ý trong câu đố, các bạn sẽ nhận ra ngay mình đang ám chỉ đến mạng xã hội Twitter với biểu tượng hình con chim xanh quen thuộc
- Profile twitter của một người có thể dễ dàng truy cập bằng đường dẫn: https://twitter.com/username
- Lấy 15 ký tự cuối của chuỗi romanji thu được từ mã morse theo đúng format abcdeFgHijklmNo, các bạn sẽ có được profile Twitter cần tìm: https://twitter.com/shitaWaHareruYo
- Khi truy cập đến profile Twitter, các bạn sẽ bắt gặp câu đố tiếp theo:
![](img/17.png)
- Câu đố này yêu cầu tìm ra địa điểm chụp một bức ảnh
- Tiếp tục google với keyword: find location of photos
![](img/18.png)
- Các bạn sẽ thấy ngay một hướng dẫn lấy được gps vị trí chụp bức ảnh thông qua exif data
- Exif là viết tắt của Exchangeable Image File Format, là một tiêu chuẩn để xác định thông tin liên quan đến một bức ảnh được tạo bởi một thiết bị ghi hình cụ thể, các thông số phơi sáng của máy ảnh, tiêu cự, cân bằng trắng, ngày giờ việc ghi hình xảy ra, và cả vị trí GPS
- Thực hiện theo hướng dẫn tìm được hoặc sử dụng các công exif data vierwer có sẵn trên mạng, các bạn sẽ có thể lấy được thông tin gps vị trí chụp bức ảnh:
![](img/19.png)
- Sử dụng google map để tìm vị trí theo vĩ độ và kinh độ gps:
![](img/20.png)
- Như vậy có thể thấy vị trí chụp bức ảnh này là tại Ruby Plaza
=> password để truy cập link pastebin https://pastebin.com/Tt1SBnV7 là rubyplaza:
- Truy cập vào link pastebin để lấy flag:
![](img/21.png)
![](img/22.png)
- Flag: ``` ISPCLUB{w3lc0me_t0_1nn3r_s4nCtuM} ```
- 
# General Skill: Start the new schoolyear 

#### Challenge

Một bài test nhanh cho các Genin!!

[exam](/miniCTF2021/miniCTF2021_file/exam.rar)

#### Solution

Sau khi mở file exam.rar sẽ nhận được 3 file rar và 1 file txt. 

File txt với nội dung:

flag1: Câu lệnh bắt buộc khi ta thực hiện các tác vụ cần quyền root hay superuser.

flag2: Câu lệnh được sử dụng để xem toàn bộ nội dung file trong cửa sổ dòng lệnh Linux.

flag3: Câu lệnh được sử dụng để liệt kê tất cả tệp tin bao gồm cả tệp tin ẩn trong Linux

Sau khi đọc, ta thấy mỗi dữ kiện ứng với mật khẩu của từng file rar:

>Với flag1: Câu lệnh cấp quyền root hay superuser là: sudo

>Với flag2: câu lệnh xem toàn bộ nội dung file trong cửa sổ dòng lệnh (Terminal): cat

>Với flag3: câu lệnh liệt kê tất cả tập tin bao gồm cả tập tin ẩn: ls -a

Sau khi nhập đúng password ta nhận được 3 mảnh ghép và ghép lại ra flag

Flag: ```ISPCLUB{L1nux_1z_v3ry_c0nV3n1EnT}```

# General Skill: Sasuke’s Paw Encyclopedia

#### Challenge

Dù cho đã kiếm đc cả dấu chân của vua mèo nhưng papasuke vẫn còn thiếu dấu chân duy nhất của con mèo ma thuật. Papasuke nói sẽ tặng cho bất kì ai kiếm được dấu chân mèo đó 1 ấn chú cấp S. Hãy tìm ra nó và mang về cho papasuke!!!

** nc 134.209.97.157 10001**

#### Solution

#### Author: Iluvinn

Đề bài cho ta 1 địa chỉ ip và khi kết nối đến nó bằng công cụ `netcat` ngay lập tức có flag xuất hiện
```
iluvinn in ~/miniCTF2021 λ nc 134.209.97.157 10001
            .       .
            \`-"'"-'/
             } 6 6 {
            ==. Y ,==
              /^^^\  .
             /     \  )
            (  )-(  )/
            -""---""---   /
           /   Ncat    \_/
          (     ____
           \_.=|____E

Here your flag:
ISPCLUB{SO_WEIRD_CAT}
```
Flag: ```ISPCLUB{SO_WEIRD_CAT}```

# Misc: Faster!!!

#### Challenge

Tên Hiruyzawa Kuhan là kẻ có thân thủ rất nhanh. Bạn cần luyện tập cho đôi mắt của mình bắt kịp tốc độ của hắn. Hãy xem bạn đã đủ nhanh để theo dõi hắn chưa

https://www.youtube.com/watch?v=95qVduCOWTc
#### Solution

Đi theo đường dẫn thì mình tới được 1 video khá quen :v
Việc trước tiên cần làm khi gặp những challenge liên quan đến youtube đó là kiểm tra các phần mô tả cũng như phụ đề. Challenge này cũng như thế, flag được giấu trong phần phụ đề.
[](/miniCTF2021/miniCTF2021_file/faster/img/2.png)
>Tuy nhiên flag xuất hiện với tốc độ khá nhanh việc dừng lại từng khung hình để kiểm tra là tương đối khó, và flag của mình >cũng có hai ký tự giống nhau đứng cạnh nhau nên khá dễ nhầm lẫn.

Challenge này mình thấy có một số bạn vào phần mở rộng cạnh chức năng lưu để mở bản ghi của video, tuy nhiên giờ cách đó không còn khả dụng.
[](/miniCTF2021/miniCTF2021_file/faster/img/3.png)
Các bạn có thể sử dụng 1 số trang web để down phụ đề youtube về ví dụ như downsub.com

Flag: ```ISPCLUB{r1ck_r0ll_4g41n}```

# Misc: First Generation 
#### Challenge
> Trải qua nhiều thế hệ, biểu tượng của ISP Ichizoku đã được thay đổi rât nhiều nhưng biểu tượng thời sơ khai vẫn được cất giữ cẩn thận trong phòng truyền thống của gia tộc. Trên đó có 1 secret text. Chắc bạn sẽ tìm được nó nhanh thôi.                                                                                                     
Flag form: ISPCLUB{SECRET_TEXT}

#### Solution
- Nói đến biểu tượng của ISP Ichizoku thì chỉ có thể là ảnh đại diện trên fanpage của [CLB ISP](https://www.facebook.com/ATTT.PTIT)
- Biểu tượng thời sơ khai hay nói cách khác là ảnh đại diện đầu tiên trên fanpage của CLB ISP.
- Truy cập album ảnh đại diện và tìm bức ảnh đầu tiên
![](/miniCTF2021/miniCTF2021_file/First_Generation/img/1.png)
- Flag: ```ISPCLUB{CAPTURE_THE_FLAG}```

# Misc: Kakuremino no Jutsu 
#### Challenge

> Kakuremino no Jutsu là một thuật cơ bản nhưng nó rất hữu ích trong việc làm các nhiệm vụ theo dõi, trinh sát hay cả trong chiến đấu,...Hãy làm một bài test nho nhỏ về nhẫn thuật này.                                                                                                                                                                  
[Challenge](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/Challenge.rar)
#### Solution
- Giải nén file được cung cấp ta nhận được 1 file txt kèm với đó là 1 bức ảnh 
- Trước hết ta mở file txt                                                      
![](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/1.png)
- Tưởng chừng như không có gì trong file txt này nhưng dưới cuối file có 1 hint nhỏ
![](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/2.png)
- Change scroll -> file ảnh tên Scroll -> change file scroll. Ta sẽ thử thay đổi phần file name extension của file ảnh sang rar và đúng là ta nhận được 1 file rar có thể sử dụng.
- Giải nén ra ta lại nhận được 2 file tương tự ban đầu. Nhưng lần này sau khi chuyển định dạng ảnh sang rar ta không thể giải nén ngay mà nó yêu cầu mật khẩu.
- File hint cho ta gợi ý về password:
>What is the name of the mountain containing this scroll?

- Password là tên ngọn núi có liên quan đến bức ảnh đi kèm. Bằng chút kiến thức về Naruto ta tìm ra được đó là núi MYOBOKU.
> Ta cũng có thể dùng google hình ảnh để tìm bức ảnh đi kèm và từ đó tìm ra từ khóa về núi MYOBOKU

- Giải nén với pass MYOBOKU lần này là 1 file txt và 1 folder ảnh luôn.
- Thử xem [file txt](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/F^ckkkkkkkkkkkkkkkkkkkk.txt) -> 1 đống ký tự khó hiểu
![](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/3.png)
- Tên file: F^ckkkk... + sử dụng https://www.dcode.fr/cipher-identifier ta có thể biết được đống ký tự đó là JSFuck Language.
- Decode với https://enkhee-osiris.github.io/Decoder-JSFuck/ ta nhận được hint 
> The flag is planted on the ground but it flies in the sky
 - "Flag flies in the sky" là mấu chốt để tìm ra bức ảnh chứa flag.
 - Với từ khóa "sky" ta có thể liên hệ được đến bức ảnh                                                           
 ![](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/4.png)
 > Chữ Nhật trong bức ảnh khi dịch sang tiếng Việt là "thiên" và tiếng Anh là "sky"

- Làm tương tự như những bước trước ta giải nén với pass SKY và nhận được [flag](/miniCTF2021/miniCTF2021_file/Kakuremino_no_Jutsu/img/flag.txt)
- Flag: ```ISPCLUB{h1d3_f1l3_1n_p1ctur3}```

# Programming: Honest or Tricky-Tricky or Honest

#### Challenge

Tưởng shinobi thì không phải làm toán sao, đến bọn trẻ con còn làm tốt nữa là khác. Hãy thử xem liệu bạn có thể hoàn thành những bài toán sau trong thời gian cho phép ko nhé!
Honest or Tricky: ```nc 134.209.97.157  10002 ```
Tricky or Honest: ```nc 134.209.97.157  10003 ```

#### Solution

Tricky or honest và Honest or tricky là 2 bài từ cùng 1 mã nguồn nên cách giải sẽ y hệt nhau <br>
Khi kết nối đến server thì ta nhận được 
```
iluvinn in ~/miniCTF2021 λ nc 134.209.97.157 10002
                                                                                
                                                                                
                                                                                
                                         I                                      
                                      II   II                                   
                                   II         II                                
                                ,I               II                             
                              I,       IIIIII       II                          
                           II       IIIIIIIIIIII       II                       
                        II       IIIIIIIIIIIIIIIIII#      II                    
                     II        IIIIIIIIIIIIIIIIIIIIIII       II                 
                  II        IIIIIIIIIII       IIIIIIII  II      II              
           IIIIII            IIIIIII            IIIIII  IIIII      II           
           IIIII        II    IIIIIII           IIIIII  IIIIIIII      II.       
            #I      I   IIII    IIIIIII         IIIIII  IIIIIIIIIII     I       
                 IIIII  IIIII    IIIIIIIII     .IIIIII  IIII   IIIII    I       
        IIIII  IIIIIII   IIIIII    IIIIIIIII     IIIII  IIII    IIII    I       
        IIIII  #IIIIII   IIIIII       IIIIIIIII      I  IIII   IIII    I        
           I    IIIIIII   IIIIII  I     IIIIIIIIIII     IIIII# IIII    I        
           I     IIIIII   IIIIIII  II      IIIIIIIIII  IIIIIIIIIII    II        
            I    IIIIIII   IIIIIII  III#     IIIIIII   IIIIIIIIIII    I         
            I     IIIIIII   IIIIIII  IIIII  IIIIIIII  IIIIIIIIIII    I          
             I     IIIIIII   IIIIIII  IIII IIIIIIII   IIIIIIIIII    II          
              I     IIIIIII   IIIIIII  II IIIIIIII#  IIIIIIIIII     I           
               I     IIIIIII   IIIIIIII  IIIIIIIII  *IIIIII II     I            
                I     IIIIIII   IIIIIIIIIIIIIIIII   IIIIII II     I             
                 I     IIIIIII   IIIIIIIIIIIIIII   IIIII* II    #I              
                  I      IIIIII    IIIIIIIIIIII   IIIII  I     II               
                   I.     IIIIIII    IIIIIIIII   IIIII II     I                 
                     I      IIIIIII   IIIIII   IIIIII I      I                  
                      II      IIIIII    III   IIIII        I                    
                        II      IIIIII      IIIIII       II                     
                          II      IIIIII   IIIII       II                       
                            II      IIIIIIIIII       II                         
                               II                  I                            
                                 III            II                              
                                    #II     III                                 
                                        III                                     
                                                                                
                                                                                
Too ez for you, right?
Flag? pass my 100 question pls!!!
Remember, you have 60s
quest: 1
15973591 * 62179688 = Too slow!!!No flag for you bae ¯\_(ツ)_/¯
```

Đối với honest or tricky sẽ là 15 câu hỏi trong 100s và tricky or honest là 100 câu hỏi trong 60s <br>
Qua vài lần thử thì có thể thấy server chỉ yêu cầu các phép toán cộng, trừ, nhân, chia vậy nên phương pháp làm đơn giản sẽ là đọc dữ liệu trả về từ server sau đó thực hiện tính toán và gửi trả lại kết quả cho server
```python
# Honest or tricky
from pwn import *
p = remote("134.209.97.157", 10001)
for i in range(15):
	p.recvuntil("quest:")
	p.recvuntil("\n")
	r = p.recvuntil("=")
	r = r.replace(" =","")
	r = int(eval(r))
	p.sendline(str(r))
p.interactive()

# Tricky or honest
from pwn import *
p = remote("134.209.97.157", 10002)
for i in range(100):
	p.recvuntil("quest:")
	p.recvuntil("\n")
	r = p.recvuntil("=")
	r = r.replace(" =","")
	r = int(eval(r))
	p.sendline(str(r))
p.interactive()

```
Khi chạy file python ta sẽ có được flag <br>
Honest or tricky

```
[+] Opening connection to 134.209.97.157 on port 10001: Done
[*] Switching to interactive mode
 yes!
ISPCLUB{m4th_f0R_dUmm13S!!!!!!!}
[*] Got EOF while reading in interactive
$  
```


Flag: ``` ISPCLUB{m4th_f0R_dUmm13S!!!!!!!} ```


Tricky or honest <br>

```
iluvinn in ~/miniCTF2021 λ python solve.py    
[+] Opening connection to 134.209.97.157 on port 10002: Done
[*] Switching to interactive mode
 yes!
ISPCLUB{F45T_a5_71ghtN1n9!!!!}
[*] Got EOF while reading in interactive
$  
```

Flag: ``` ISPCLUB{F45T_a5_71ghtN1n9!!!!} ```

# RE: Reverse no Jutsu

#### Challenge

Có vẻ Deku Haha đã ăn cắp được một mảnh giấy cấm thuật. Nhưng vì quá ảo ma canada nên trong lúc luyện tập phong độn hắn lỡ cắt mảnh giấy thành nhiều phần và bị thổi bay đi. Bây giờ hắn đang khóc lóc và cầu xin bạn giúp tìm từng mảnh để ghép chúng lại. Hắn ta hứa sẽ trả công bạn hậu hĩnh. Bạn có sẵn lòng giúp hắn ko? ( Việc nhẹ lương cao tại sao không làm)

[Reverse no Jutsu](/miniCTF2021/miniCTF2021_file/R3v3rs3_no_jnt5u.cpp)

#### Solution

Đề cho ta một đoạn code C++ như sau:
```C++
#include<bits/stdc++.h>
#include<windows.h>
using namespace std;

int check(string ninjutsu){
			if( ninjutsu.length()==32 &&
                ninjutsu[0x1c]         == 'r' &&
                ninjutsu[18/9]         == 'P' &&
                ninjutsu[14]           == '0' &&
                ninjutsu[21+2*10+2-22] == '_' &&
                ninjutsu[3]  		   == 'C' &&
                ninjutsu[24]           == 'i' &&
                ninjutsu[18/6*10]      == 'm' &&
                ninjutsu[6]            == 'B' &&
                ninjutsu[9]            == '3' &&
                ninjutsu[10]    	   == 'x' &&
                ninjutsu[12]           == '_' &&
                ninjutsu[5]            == 'U' &&
                ninjutsu[16]           == 'j' &&
                ninjutsu[23]           == '4' &&
                ninjutsu[17]           == 'n' &&
                ninjutsu[4]            == 'L' &&
                ninjutsu[18+9-2+2-9]   == 't' &&
                ninjutsu[20]           == 'u' &&
                ninjutsu[0]            == 'I' &&
                ninjutsu[22]           == 'K' &&
                ninjutsu[7]            == '{' &&
                ninjutsu[11]           == 'Y' &&
                ninjutsu[0x1b]         == '4' &&
                ninjutsu[13]           == 'n' &&
                ninjutsu[5*5]          == '_' &&
                ninjutsu[8]            == 's' &&
                ninjutsu[26]           == 'h' &&
                ninjutsu[1]            == 'S' &&
                ninjutsu[29]           == '3' &&
                ninjutsu[15]           == '_' &&
                ninjutsu[21*2-23]      == '5' &&
                ninjutsu[31]           == '}') 
	return 1;
    return 0;
}

int main(){
	cout <<"Ban da tim thay nhung gi Deku Haha can chu\n\n\n";
	string ninjutsu;
	getline(cin,ninjutsu);
	system("cls");
	if(check(ninjutsu)) cout << "\n\n\n								Deku Haha chac chan se rat cam kich truoc tam long hao hiep cua ban giup han tim duoc cam thuat >>_<<";
	else cout << "\n\n\n								Deku Haha guc nga khi biet do khong phai thu han can ~..~"; 
}
```

Quan sát kĩ ta sẽ thấy thứ tự các kí tự của flag bị tráo đổi nên ta cần sắp xếp lại. Để làm việc này thì mình có code đoạn code C++ để sắp xếp lại cho mình.

``` C++
#include<bits/stdc++.h>
#include<windows.h>
using namespace std;
int main(){
    string ninjutsu="";
    for (int i = 0; i < 32; i++)
        ninjutsu += ' ';
    ninjutsu[0x1c]         = 'r' ;
    ninjutsu[18/9]         = 'P' ;
	ninjutsu[14]           = '0' ;
    ninjutsu[21+2*10+2-22] = '_' ;
    ninjutsu[3]  		   = 'C' ;
    ninjutsu[24]           = 'i' ;
    ninjutsu[18/6*10]      = 'm' ;
    ninjutsu[6]            = 'B' ;
    ninjutsu[9]            = '3' ;
    ninjutsu[10]    	   = 'x' ;
    ninjutsu[12]           = '_' ;
    ninjutsu[5]            = 'U' ;
    ninjutsu[16]           = 'j' ;
    ninjutsu[23]           = '4' ;
    ninjutsu[17]           = 'n' ;
    ninjutsu[4]            = 'L' ;
    ninjutsu[18+9-2+2-9]   = 't' ;
    ninjutsu[20]           = 'u' ;
    ninjutsu[0]            = 'I' ;
    ninjutsu[22]           = 'K' ;
    ninjutsu[7]            = '{' ;
    ninjutsu[11]           = 'Y' ;
    ninjutsu[0x1b]         = '4' ;
    ninjutsu[13]           = 'n' ;
    ninjutsu[5*5]          = '_' ;
    ninjutsu[8]            = 's' ;
    ninjutsu[26]           = 'h' ;
    ninjutsu[1]            = 'S' ;
    ninjutsu[29]           = '3' ;
    ninjutsu[15]           = '_' ;
    ninjutsu[21*2-23]      = '5' ;
    ninjutsu[31]           = '}' ;

	cout<<ninjutsu;
}
```
Sau khi chạy code thì ta ra được flag: ISPCLUB{s3xY_n0_jnt5u_K4i_h4r3m}

Flag: ```ISPCLUB{s3xY_n0_jnt5u_K4i_h4r3m}```

# RE: Kakureru

#### Challenge

Bạn và Deku Haha đã tìm thấy một hang động, có lẽ đây là nơi ẩn nấp đã bị bỏ hoang của tổ chức AkatXienPan chăng? Trên hang chứa rất nhiều văn tự nhưng có lẽ chúng đã được viết ngược lại. Hãy giải mã nó để xem có thể tìm được manh mối gì của bọn chúng không nhé!

[Kakureru](/miniCTF2021/miniCTF2021_file/UDRL.py)

#### Solution

Bài này ta chỉ cần hiểu các hàm làm gì và decode các hàm đó để ra flag.

Hàm main:
```
def main():
    flag = "ISPCLUB{}"
    encoded = encode(flag)
    print(encoded)
    print("What does this mean?")
    encoded = "10100000101100011100010010111101100110001101100010101100110010001001100111011000100000101111100111101000100000101001100110100100111110011001110010000010111001001110010010011001100010101001000011011110101010101110011010011110111110101001101010110110"
    
```
"ISPCLUB{}" sau khi encode ta được 1 dãy nhị phân. Nên encoded là flag của bài đã được encode.
Bây giờ ta xem chức năng của từng hàm.
```
def up(x):
    x = [f"{ord(x[i]) << 1:08b}" for i in range(len(x))]
    return ''.join(x)
```
Tách từng kí tự trong string x và dịch trái 1 bit.
Kết quả trả về 1 dãy nhị phân.

```
def down(x):
    x = ''.join(['1' if x[i] == '0' else '0' for i in range(len(x))])
    return x
```
Đảo bit 0 thành 1 và 1 thành 0

```
def right(x,d):
    x = x[d:] + x[0:d]
    return x
```
Xoay string x sang phải d lần

```
def left(x,d):
    x = right(x,len(x)-d)  # = xoay x sang phải len(x)-d
    return x[::-1] #đảo ngược 
```
Xoay string x sang phải len(x)-d lần và reverse(x)

```
def encode(plain):
    d = 32
    x = up(plain)
    x = right(x,d)
    x = down(x)
    x = left(x,d)
    return x
```
Để decode thì bây giờ chúng ta chỉ cần code những hàm chức năng ngược lại với các hàm up, right, down, left và sắp xếp theo chiều ngược lại vói hàm encode.

## Code Solve 
```python
def up(x):
    x = [f"{ord(x[i]) << 1:08b}" for i in range(len(x))]
    return ''.join(x)
    #x[i]*2;

def down(x):
    x = ''.join(['1' if x[i] == '0' else '0' for i in range(len(x))])
    return x
    #not: đảo bit 0 thành 1, 1 thành 0 

def right(x,d):
    x = x[d:] + x[0:d]
    return x
    #xoay x sang phải d lần  

def left(x,d):
    x = right(x,len(x)-d)  # = xoay x sang phải len(x)-d
    return x[::-1] #đảo ngược 

def decode_binary_string(s):
    return ''.join(chr(int(s[i*8:i*8+8],2)) for i in range(len(s)//8))

def dup(x):
    x = [f"{ord(x[i]) >> 1:08b}" for i in range(len(x))]
    return ''.join(x)
    #x[i]*2;

def ddown(x):
    x = ''.join(['0' if x[i] == '1' else '1' for i in range(len(x))])
    return x

def dleft(x,d):
    x = x[::-1]
    x = right(x,d)  # = xoay x sang d
    return x #đảo ngược 

def encode(plain):
    d = 32
    x = up(plain)
    x = right(x,d)
    x = down(x)
    x = left(x,d)
    return x

def decode(plain):
    d=32
    x = plain
    x = dleft(x, d)
    x = ddown(x)
    x = right(x, len(x)-d)
    x = decode_binary_string(x)
    x = dup(x)
    x = decode_binary_string(x)
    return x

def main():
    flag = "ISPCLUB{}"
    encoded = encode(flag)
    print(encoded)
    print("What does this mean?")
    encoded = "10100000101100011100010010111101100110001101100010101100110010001001100111011000100000101111100111101000100000101001100110100100111110011001110010000010111001001110010010011001100010101001000011011110101010101110011010011110111110101001101010110110"
    print(decode(encoded))

if __name__ == "__main__":
  main()

```

Sau khi chạy đoạn code ta ra được flag: ISPCLUB{W3ll_c0m3_t0_r3vers!n9} 

Flag: ```ISPCLUB{W3ll_c0m3_t0_r3vers!n9} ```

# RE: Furipputon - Reveal of the Truth

#### Challenge

Tối mật thư và cuốn trục giải mã mật thư của bọn AkatXienPan đã bị tổ chức Anbu tài năng của PTITkagure lấy được sau nhiều hy sinh. Hãy giúp Anbu tìm ra cách sử dụng cuốn trục để biết được danh tính tên thủ lĩnh tổ chức AkatXienPan! 

Flag form: ISPCLUB{TenThuLinh}

[furipputon.c](/miniCTF2021/miniCTF2021_file/furipputon.c) [Scroll](/miniCTF2021/miniCTF2021_file/Scroll)

#### Solution

Đề bài cho một file source C và một file tên Scroll.  
Đầu tiên là xác định kiểu file Scroll

``` $ file Scroll ```

Output:
```
Scroll: ASCII text
```

Vậy tệp Scroll là một file text ngắn. 

Tiến hành phân tích file source.  
  
```c
#include <stdio.h>                                  
int r=0,x,y=0,    /*                                
nt               \ /                                
c    / \ / ||| /\_                                  
lx  /   X _ _  \ |                                  
u, ^_  / \ \/   /\                                  
dn  \           \_        ]                         
e=   \ .||  /\            =                     p p 
 0 |||   /  ||  ||        f        f       f    r r 
<,  /\          /         tw       t       s s  i i 
sy      <<  ||         i  eh       e       e c  n n 
t=  /\ ___  /   /\     n  li       l       e a  t t 
d0  ||      ||  \/     t  ll       l  {<   k n  f f 
i,             |||        (e s     (  fr   ( f  ( ( 
o   ||  || |     /     tu s( t    usw o; i s (  " " 
.   -/  /   /_ |||   c [[ tg rv   [th rx=f t "  % \ 
h       ||  _/   /  mh111 de{l)   +di (+'( d+%  c n+
>                   aa000 itte; > +il x+ n inc  " "+
 /                  ir000[ns[nytyrrne<=)'<xn,"  , );
 */                 n         =             0     ; 
               main        (       )   {            
                char       v   [                    
                100    ]                   ,  s;    
          int t[100     ]                    ,      
              u[100               ]     ;  u        
                  [                   0             
      ]=ftell(stdin        )       ;                
         while(gets (v    )                 )       
                 {t  [         r ]=                 
             strlen                 (               
               v);y=                                
                 t[         r             ]         
                 >y             ?        t [        
                  r         ]    :   y;             
              u[++r   ]     =                       
        ftell(stdin )   ;                          }
              while          (                    n 
                  <              y        )         
            {for(x=0             ;         x        
            <r;x++) {                           s   
               =' '       ;                         
              if(n<             t        [          
                  x            ]     )    {         
        fseek(stdin    ,u       [     x    ]        
                 +n   ,  0 )                     ;  
        scanf("%c",                          &      
                                       s        )   
                   ;                             }  
       printf("%c",   s                       )     
                                            ;      }
      printf("\n");                 n               
                 ++   ;            }           }
```  
  
Đây là một file C trông khá "lạ" so với code C thông thường. Tiến hành compile thử:  

``` $ gcc flipped.c ```

Thì thấy vẫn compile thành công. Vậy file này đã làm rối trong việc đọc code bằng mắt thường. Ta có thể xử lý bằng cách nhờ đến các code beautifier.  
  
Về nội dung, code này sẽ sử dụng hàm `gets()` để nhận input và tiến hành lật ngược (flip) lại theo đường chéo trên trái - dưới phải.

Tiến hành compile file source và decode thôi!

``` $ gcc flipped.c ```

``` $ ./a.out < Scroll ```
  
Output:
```
      ___                     _                                                          
     -   -_, ,,           ,  - -    /`                                                   
    (  ~/||  ||     _    ||    \\  /    '                     _                          
    (  / ||  ||/\  < \, =||=    \\/    \\  _-_  \\/\\ -_-_   < \, \\/\\                  
     \/==||  ||_<  /-||  ||    ==/\==  || || \\ || || || \\  /-|| || ||                  
     /_ _||  || | (( ||  ||     / \\   || ||/   || || || || (( || || ||                  
    (  - \\, \\,\  \/\\  \\, \\/   \\, \\ \\,/  \\ \\ ||-'   \/\\ \\ \\                  
                                                      |/                                 
                                                      '                                  
 __                                                                                      
|_   _       _   _|  _  _ .   |__|  _  _  .  _ |_   _   _    |_/      _  .  _       _    
|   (_) |_| | ) (_| (- |  .   |  | (_| /_ | (- | ) (_| | )   | \ |_| | ) | | ) \)/ (_|   
                                                                                         
 __          _                            __               __         __                 
/    _   __ (_  _       _   _|  _  _ .   |  \  _ |        /       |  /       |           
\__ (_)     |  (_) |_| | ) (_| (- |  .   |__/ (- |( |_|   \__ |_| |( \__ |_| |(          
                                                                                         
                                           __               __         __                
                                          |  \  _ |        /    _  |  /    _  |          
                                          |__/ (- |( |_|   \__ (_| |( \__ (_| |(         
                                                                                         
 __                        __                 __                                         
/        _  _  _  _  |_   |__)  _   _  _ .   |  \  _ |        |__|  _  |_   _            
\__ |_| |  |  (- | ) |_   |__) (_) _) _) .   |__/ (- |( |_|   |  | (_) | ) (_)           
                                                                                         
 __                                                                                      
/  \ |_ |_   _  _  _ .   |__| .  _        _   _       _    |_/     |_   _   _            
\__/ |_ | ) (- |  _) .   |  | | |  |_| \/ /_ (_| \)/ (_|   | \ |_| | ) (_| | )           
                                                                                         
                                                                                         
                   /\  |   _   _   _      /\  |   _  _  .     |__|  _  .      _ .        
                  /--\ |( (_| | ) (- ,   /--\ |( (- ||| | ,   |  | (_| | |_| |  |        
                                                                       /                 
 __                                           __                                         
|_   _   _   |_ |_   _   |  |  _   _ |  _|   |  \  _   _  .  _   _  |_ .  _   _  |       
|   (_) |    |_ | ) (-   |/\| (_) |  | (_|   |__/ (_) ||| | | ) (_| |_ | (_) | ) .
```

Flag: ``` ISPCLUB{DekuHoho} ```  
  
Một điều đặc biệt là chính file source này cũng đối xứng theo đường chéo trái trên - dưới phải. Thử xem nếu lấy chính source code để làm input ta sẽ có gì?

```$ ./a.out < flipped.c ```

Output: 
```c
#include <stdio.h>                                  
int x,n=0,y=0,    /*                                
nt                 /                                
c    ^  |                                           
lr  /_\ |/ /| |-                                    
u= /   \|\ \| |/                                    
d0                        ]                       p 
e, \ / .   _              =                     p r 
 x  X  |  <_  |/|         f        f       f s  r i 
<, / \ |/ <_  | |         tw       t       s c  i n 
sy  _                  i  eh       e       e a  n t 
t= | \        |        n  li       l       e n  t f 
d0 |_/ /| |/|  /_      t  ll       l  {<   k f  f ( 
i, |   \| | |  _/         (e s     (  fr   ( (  ( " 
o                      tu s( t    usw o; i s "  " \ 
.  /\        | |    m  [[ tg rv   [th rx=f t %  % n 
h  \ /\ |/ /\| |    ac111 de l)   +di (+'( d c  c " 
> \_|\_ |  \/|/|/   ih000 it{e;t> +il x+ n i+"  " )+
 /                  na000[nstny[yrrne<=)'<xnn,  , ;+
 */                  r        =       0        ;    
                main       (       )   {            
               char        v[                       
                100               ]         ,   s  ;
          int t[100   ]                    ,        
              u[100    ]           ;       u        
                  [                         0       
      ]=ftell(stdin        )            ;           
         while(gets (v    )                 )       
                {t[            r ]=                 
             strlen                 (               
               v);y=                                
                  t  [      r             ]         
                 >y             ?        t [        
                  r         ]    :   y;             
              u[++r     ]   =                       
        ftell(stdin )     ;                        }
              while          (                    n 
                  <              y        )         
            {for(x=      0       ;         x        
            <r;x++) {                         s     
               =' '     ;                           
              if(n<             t        [          
                  x            ]     )    {         
        fseek(stdin   , u       [     x    ]        
                +n,0       )                     ;  
         scanf("%c"    ,                     &      
                      s                         )   
                      ;                            }
       printf("%c",                    s      )     
                                            ;  }    
       printf("\n");                n               
                ++;                }             }
```

Vẫn là đoạn code đó nhưng đoạn comment tối nghĩa nay đã trở thành chữ ký `AkatXienPan's Scroll` !!!

# Warm Up: Isekai with truck-kun

#### Challenge 

Một nhãn thuật cấp S được biết đến với cái tên Amaterasu đã thất lạc cùng con mắt mangekyou sharingan của huyền thoại Itachi thông qua 1 đường hầm dị giới. AkatXienPan đang lùng sục cánh cổng dị giới đó. Nhưng theo nguồn tin từ đội anbu thì nó đã bị đóng lại từ lâu, cách duy nhất để xuyên không hiện tại đó là để Truck-kun tông và yên tâm là chúng ta đã sở hữu Rinnegan với luân hồi chuyển sinh. Hãy lên đường tìm kiếm nhãn thuật đi nào, biết đâu 1 cuộc phiêu lưu đang chờ đợi phía trước.

**nc 134.209.97.157 10005**

#### Solution

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
You defeated the boss, here you flag: ISPCLUB{p0w3R_oF_l0V3!!!}
```
Đây là 1 lỗi được gọi là [`interger overflow`](https://en.wikipedia.org/wiki/Integer_overflow) đơn giản thì khi giá trị vượt quá ngưỡng giới hạn trên thì giá trị hiện tại sẽ trở về mốc giới hạn dưới


Flag: ```ISPCLUB{p0w3R_oF_l0V3!!!}```

# WEB: Beginner

#### Challenge 

Một bài tập khởi động trước khi tham gia nhận nhiệm vụ ngày hôm nay!!!

http://134.209.97.157:3202/

#### Solution

Khi vào trang web mà đề bài cho ta thấy một bức ảnh 

![](/miniCTF2021/miniCTF2021_file/Begineer/1.png)

Việc đầu tiên khi làm một bài web là chúng ta sẽ thử check source của trang web đấy. F12 lên và ta thấy được flag của bài này

![](/miniCTF2021/miniCTF2021_file/Begineer/2.png)

Flag: ```ISPCLUB{Not_the_first_time_huhh??}```

# WEB: PHP no jutsu

#### Challenge

Deku Haha tìm được một chiếc rương có chứa cuốn trục về một loại nhẫn thuật mới nhưng không tài nào tìm được mật khẩu để mở được rương. Haha đã đến nhờ bạn tìm mật khẩu giúp. Bạn có thể tìm được mật khẩu của rương kho báu giúp Haha không?

http://134.209.97.157:5003/

#### Solution

Khi vào trang web ta thấy có một ô để nhập mật khẩu

![](/miniCTF2021/miniCTF2021_file/PHP/1.png)

Việc đầu tiên là ta thử xem source của trang web này. Ta thấy có 1 file tên là [hint.txt](http://134.209.97.157:5003/hint.txt). Truy cập vào file ta thấy có một đoạn code PHP 

```php
<?php
if (isset($_GET["password"])) {
    if (hash("md5", $_GET["password"]) == $_GET["password"]) {
       echo $flag;
    }
    else {
        echo "Try again bro";
    }
}
```

Đọc code thì ta thấy là trang web sẽ lấy password mà chúng ta nhập sau đó hash md5 và so sánh với password ban đầu nếu đúng thì sẽ in ra flag. Ở đây chúng ta sẽ tận dụng lỗi PHP type juggling. Lỗi này xảy ra do PHP hỗ trợ 2 phương thức so sánh bằng: so sánh tương đối (Loose comparisons) và so sánh tuyệt đối (Strict comparisons). Ở bài này chúng ta sẽ quan tâm đến so sánh tương đối được sử dụng với 2 dấu băng ``` == ```. Khi sử dụng phương thức này nếu như kiểu dữ liệu khác nhau nó sẽ đưa về một kiểu dữ liệu chung để thực hiện việc so sánh. strings bắt đầu với các ký tự là 0e, khi đó các chuỗi được chuyển thành các lũy thừa ví dự như 0e1234->0^{1234} và 0 luỹ thừa bao nhiêu cũng bằng 0. Vậy ở đây ta sẽ tìm 1 chuỗi có dạng 0e(1 chuỗi số) và sau khi hash md5 ra nó cũng có dạng 0e(1 chuỗi số).

Mình có tìm được 1 chuỗi như thế trong trên github: https://github.com/spaze/hashes/blob/master/md5.md. Nhập chuỗi 0e215962017 và lấy được flag.

Flag: ```ISPCLUB{php_1s_Suck}```

# WEB: Deku’s Bird

#### Challenge

Chú chim quý của nhà Deku được cái đẹp nhưng lại không có não. Nhiều lần nó xổng ra nhưng đều đâm đầu vào tường rồi lăn ra ngất. Hôm nay nó đã xổng lồng và bay vào 1 hang động đầy thạch nhũ. Deku Haha đã dùng Quang độn thắp sáng cả cái hang này, bạn hãy dùng thuật điều khiển bóng để điều khiển con chim bay qua 222 chướng ngại vật để ra ngoài 1 cách an toàn nhé!!! 

http://134.209.97.157:5002/


#### Solution
![](/miniCTF2021/miniCTF2021_file/bird/2.png)
>Một game kiểu flappy bird khá là đơn giản, mục tiêu đã được nói rõ trong gợi ý là đạt 222 điểm.

-Với mục tiêu như thế này, thì hoàn toàn có thể chơi như bình thường để đạt mục tiêu.

-Tuy nhiên cách làm đó khá là hại chuột. Ở challenge này, sau khi hoàn thành thì điểm cao nhất sẽ được lưu lại.

-Sau khi lục lọi một hồi ở phía browser thì mình thấy có 1 cookie dùng để lưu data về điểm cao nhất:
![](/miniCTF2021/miniCTF2021_file/bird/3.png)

-Bây giờ chỉ cần sửa  bestscore value thành giá trị lớn hơn 222 rồi reload lại là mình đã thấy flag.
![](/miniCTF2021/miniCTF2021_file/bird/4.png)

Flag:```ISPCLUB{4_G00D_PL4Y3R}```

# WEB: Kieru Odama Genso

#### Challenge
> Tên Hiruyzawa Kuhan có 1 khả năng rất khó chịu, hắn có thể hấp thu mọi nhẫn thuật mà hắn nhìn thấy và sử dụng lại nó. Chỉ một người trong ISP Ichizoku là ông Giraiga với bí thuật Kieru Odama Genso (thể nâng cấp của bí thuật Odama Genso vì nó đã được kết hợp thêm charka hệ Phong khiến bí thuật này trờ nên vô hình) nhưng hiện tại ông đã quá già không đủ sức để chiến đấu nên ông sẽ thu nhận đệ tử nếu người đó thành thục được Odama Genso trong vòng 5 ngày. Hãy chăm chỉ luyện tập nếu bạn muốn đánh bại Hiruyzawa Kuhan.

http://134.209.97.157:5004/

#### Solution
- Truy cập link ta đến trang web
![](/miniCTF2021/miniCTF2021_file/Kieru_Odama_Genso/img/1.png)
- Inspect ta thấy một phần tử bị thu nhỏ với 
> font-size: 0em 
![](/miniCTF2021/miniCTF2021_file/img/2.png)
- Tăng size cho phần tử vẫn không thấy gì xuất hiện 
![](/miniCTF2021/miniCTF2021_file/Kieru_Odama_Genso/img/3.png)
- Tới đây ta kiểm tra css vì có thể phần tử đã bị ẩn đi và đúng như vậy.                                                      
![](/miniCTF2021/miniCTF2021_file/Kieru_Odama_Genso/img/4.png)
- Bỏ tích ở thuộc tính 
> visibility: hidden
![](/miniCTF2021/miniCTF2021_file/Kieru_Odama_Genso/img/5.png)

- Flag: ```ISPCLUB{c$$_!5_v3ry_34sy}```

# WEB: Shinra Tensei

#### Challenge
Hiruyzawa Kuhan đã lên kế hoạch phá hủy PTITgakure trong thời gian tới. Bạn có thể vượt thời gian để ngăn chặn kế hoạch của hắn không???

http://18.118.154.214:5000/

#### Solution

![](https://i.imgur.com/fByXaj8.jpg)

Mở đầu trang web ra thì mình sẽ thấy có vẻ như là có đồng hồ to đùng trên web và nếu nó chạy về 0 hết thì sẽ có flag xuất hiện

Check thử source code xem sao :D

![](https://i.imgur.com/oL0haqJ.png)

![](https://memehai.net/assets/images/20210802/meo-that-vong-deo-gi-vai-loz-the.jpg)

`Flag in here :D` nhưng check file main.asm thì toàn đống bùi nhùi :< lừa vl

Tiếp theo đó thì mình sẽ check đến request xem sao 😣

![](https://i.imgur.com/KzWMVAF.png)

Mình thấy có 2 endpoints khác được gọi đó là `time.hypnguyen.workers.dev`, `logwork.com`, `cdn.logwork.com` 

`logwork.com` thì khi mình truy cập vào thì thấy ra trang web tạo đồng hồ để nhúng embed vào trang web

`time.hypnguyen.workers.dev` cái này có vẻ khá là đáng nghi khi mình xem response thì thấy nó trả về 1 dãy số có 13 chữ số thì mình đoán chắc nó là timestamp.

![](https://i.imgur.com/pqvarLK.png)

Mình thử trên trang `https://www.epochconverter.com` thì đúng nó là timestamp hiện tại thật :D

![](https://i.imgur.com/3b6AcB3.png)

![](https://memehai.net/assets/images/20210802/bo-nao-duoc-khai-sang-kien-thuc-ky-quai-nay-da-duoc-tiep-thu.jpg)

Mình đoán là sẽ bypass vượt thời gian bằng cách cho cái timestamp này nhỏ xuống :D

Ví dụ như 0 😎

Mình dùng intercept của burpsuite để change response

![](https://i.imgur.com/gFrtARW.png)

Weo done!

![](https://i.imgur.com/LfA20Jx.png)

Flag: ```ISPCLUB{__H0W_TH3__F^CK_D1D__Y0U_93t__F14G_????}```

# WEB: ISP Ichizoku SHOP

#### Challenge
Tại PTITgakure, chỉ có duy nhất một shop cho phép bán items, vũ khí... Nhưng trang web của shop lại bị dính XSS. Bạn có thể tìm ra payload và report cho admin khum?
Chỉ cần alert ra: ISPCLUB

Shop: http://104.248.144.252:5002/

Send payload to admin: http://104.248.144.252:5002/admin

#### Solution
![](https://i.imgur.com/JhUUCKu.png)

Bài này thì chắc là XSS thật rùi

Đầu tiên là mình sẽ xem các dòng code có ý nghĩa gì.

`decodeURIComponent(document.location.search?.split('?')[1])` hàm này sẽ get ra params của url ví dụ như url có dạng `index.html?a=123` thì sẽ trả về `a=123`

Sau đó content của `body` sẽ append thêm code HTML vào bằng innerHTML

Đọc thêm: https://www.w3schools.com/jsref/prop_html_innerhtml.asp

```javascript
params.split('=')[0] === 'xss' ?
            params.match(/xss=(.+?)$/)[1] :
            'Do u know XSS ~.~ If you don\'t know then it\'s probably not for you.<br / > '
```

Đoạn này có vẻ chỉ là hiển thị thông thường chứ không thấy có cái gì đáng nghi lắm.

```javascript
paramURLEncoded = decodeURIComponent(params).split('').map(e => {
            if (e.match(/\<|\>|\"|\'|\/|\\/)) return no_xss()
            return e
        }).join('')
```

Đáng nghi nhất là chỗ này, check trong cái params đó có 1 trong các kí tự `<`, `>`, `"`, `'`, `/`, `\` thì sẽ chuyển hướng đến trang cảnh báo.

Mình sẽ thử xem thế nào

`index.html?a=123` thì thấy chưa thấy có hiện tượng gì cả check source code thì thấy cái này:

![](https://i.imgur.com/Z70ifuM.png)

Adu có vẻ như query này được thực hiện bên phía server nữa, mình sẽ thử thay cứ tự thuộc đã bị filter vào xem

![](https://i.imgur.com/t8lvuVR.png)

Hmm có vẻ như tác giả đã lừa mình quả hơi đau khi mà code javascript frontend không có tác dụng gì lắm, tứk cái lồng ngực 😒.

Nếu như tác giả cố tình làm vậy thì phải đánh lạc mình sang một hướng khác vì mình đoán cú lừa này chắc chắn sẽ có cú lừa khác trong đó, mình thấy thay vì truyền param vào theo kiểu `?` thì sao mình lại khum truyền router vào nhỉ 🤔.

Đánh liền thử: `index.html/abc`

Hmm nó vẫn work chứ không hề báo 404

![](https://i.imgur.com/ubyAc3h.png)

![](https://i.imgur.com/Kc1IshX.png)

Có vẻ như tác giả cố tình hoặc không để ý nên `/` không hề bị filter các kí tự trên :D oh shit

Done, payload: `/index.html/a=<script>alert('ISPCLUB')</script>`

Gửi payload và tài khoản Discord cho admin để lấy flag thôi

Flag: ```ISPCLUB{dung_gian_lan}```


