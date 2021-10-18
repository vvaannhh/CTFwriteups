# Chào mừng các bạn đã đến với writeup của Chess but not so Stress 

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

Cảm ơn các bạn đã xem writeup của mình :) 
