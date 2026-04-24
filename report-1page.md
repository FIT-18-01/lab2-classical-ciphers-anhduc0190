# Report 1 Page – FIT4012 Lab 2

## 1. Mục tiêu
Tóm tắt ngắn gọn mục tiêu của bài lab.

## 2. Cách làm
- Hoàn thiện Caesar Cipher cho chữ thường, dấu cách và giải mã.
- Hoàn thiện Rail Fence Cipher cho giải mã, giữ dấu cách, kiểm tra đầu vào và đọc file.
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Caesar Cipher
| Input | Key | Ciphertext / Plaintext | Nhận xét |
|---|---:|---|---|
| I LOVE YOU | 3 | L ORYH BRX | Dịch 3 ký tự, giữ nguyên dấu cách thành công. |
| hello world | 5 | mjqqt btwqi | Xử lý tốt chữ thường và dấu cách. |
| LORYH BRX | 3 | ILOVE YOU | Giai mã chuẩn xác (chấp nhận LORYH BRX thiếu dấu cách đầu). |

### 3.2 Rail Fence Cipher
| Input | Rails | Ciphertext / Plaintext | Nhận xét |
|---|---:|---|---|
| I LOVE YOU | 2 | ILV O OEYU | Giữ được dấu cách giữa các từ. |
| I LOVE YOU | 4 | I  EYLVOOU | Đường zigzag chia thành 4 hàng và gộp lại chuẩn xác. |
| IOEOLVYU | 2 | ILOVEYOU | Thuật toán giải mã ghép đúng các ký tự về vị trí ban đầu. |

### 3.3 Input validation / file input
- Trường hợp đầu vào không hợp lệ: Nhập `I love you @123` -> Chương trình báo lỗi và dừng chạy (bắt lỗi tốt).
- Kết quả đọc từ `data/input.txt`: Chương trình đọc thành công dòng chữ `I LOVE YOU` và thực hiện mã hoá như bình thường.

## 4. Kết luận
Bài lab giúp em củng cố kiến thức về mã hóa cổ điển. Khó khăn lớn nhất là hình dung và cài đặt thuật toán giải mã Rail Fence Cipher, tuy nhiên việc vẽ mô phỏng ra giấy đã giúp em hoàn thiện thuật toán thành công.
