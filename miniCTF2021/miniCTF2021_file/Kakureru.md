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

# Code Solve 
```
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

