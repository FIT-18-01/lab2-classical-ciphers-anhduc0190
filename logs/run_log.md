# Run Log – FIT4012 Lab 2

## Caesar Cipher
- [x] Encrypt `I LOVE YOU` với key `3`
- [x] Encrypt `hello world` với key `5`
- [x] Decrypt `LORYH BRX` với key `3`

## Rail Fence Cipher
- [x] Encrypt `I LOVE YOU` với `2` rails
- [x] Encrypt `I LOVE YOU` với `4` rails
- [x] Decrypt một bản mã Rail Fence hợp lệ

## Validation / File input
- [x] Kiểm tra đầu vào không hợp lệ
- [x] Đọc thông điệp từ `data/input.txt`

## Điều em học được từ bài lab
Qua bài lab 2, em đã hiểu rõ bản chất của hai thuật toán mã hoá cổ điển là Caesar và Rail Fence. Về mặt lập trình C++, em học được cách xử lý chuỗi linh hoạt (giữ nguyên khoảng trắng, phân biệt chữ hoa/thường) bằng các hàm như `isalpha()` và `isupper()`. Thử thách lớn nhất là mô phỏng thuật toán giải mã Rail Fence, qua đó rèn luyện cho em tư duy thao tác với mảng hai chiều (vector) để vẽ đường zigzag và cách đọc dữ liệu đầu vào an toàn từ file text.
