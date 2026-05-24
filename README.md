# BÀI TẬP MÔN KHOA HỌC DỮ LIỆU
# ĐỀ BÀI: PHÂN TÍCH THỐNG KÊ BIẾN ĐỘNG GIÁ XĂNG CỦA VIỆT NAM (2021-2025)
# Link Youtube (Video): https://youtu.be/BQaGUDkyb1c
## 1. Giới thiệu đề tài
- Đề tài thực hiện phân tích dữ liệu giá xăng RON 95-III tại Việt Nam trong giai đoạn 2021–2025 bằng Python và Jupyter Notebook.
- Mục tiêu của bài toán:
  + Phân tích xu hướng tăng giảm giá xăng.
  + Xác định các giai đoạn giá tăng hoặc giảm liên tiếp.
  + Tìm các tháng có biến động mạnh nhất.
  + So sánh giá trung bình giữa các năm.
  + Trực quan hóa dữ liệu bằng biểu đồ.
- Notebook sử dụng các thư viện phân tích dữ liệu phổ biến như:
  + pandas
  + numpy
  + matplotlib

## 2. Mục đích của chương trình
- Chương trình giúp:
  + Đọc và xử lý dữ liệu giá xăng.
  + Thống kê các thông tin quan trọng.
  + Trực quan hóa dữ liệu bằng đồ thị.
  + Hỗ trợ phân tích xu hướng biến động giá.

## 3. Công cụ và môi trường sử dụng
### Ngôn ngữ lập trình: Python 3.10.20
### Công cụ chạy
- Có thể chạy bằng:
  + Jupyter Notebook
  + VS Code
  + Google Colab
  + Pycharm
### Các thư viện sử dụng

| Thư viện     | Chức năng                                             |
| ------------ | ----------------------------------------------------- |
| `pandas`     | Xử lý dữ liệu dạng bảng                               |
| `numpy`      | Hỗ trợ tính toán số học và xử lý mảng                 |
| `matplotlib` | Vẽ biểu đồ và trực quan hóa dữ liệu                   |
| `warnings`   | Ẩn các cảnh báo không cần thiết khi chạy chương trình |

## 4 Chuẩn bị môi trường
Để chạy được file giaxang.ipynb, trước tiên cần chuẩn bị môi trường lập trình Python và cài đặt các thư viện cần thiết.
### Bước 1: Cài đặt Python
- Mục đích: Python là ngôn ngữ chính dùng để:
  + Xử lý dữ liệu.
  + Tính toán.
  + Vẽ biểu đồ.
  + Phân tích dữ liệu giá xăng.
- Cách cài đặt:
  + Truy cập website chính thức: Python Official Website (https://www.python.org/downloads/?utm_source=chatgpt.com)
  + Tải phiên bản Python mới nhất phù hợp với hệ điều hành Windows.
- Lưu ý rất quan trọng:
  + Khi cài đặt cần tích chọn: Add Python to PATH
  + Nếu không tích chọn, máy tính sẽ không nhận lệnh Python trong Command Prompt.
- Kiểm tra đã cài thành công chưa:
  + Mở Command Prompt và nhập: ```python --version```
  + Nếu hiện: Python 3.x.x -> cài đặt thành công.

### Bước 2: Cài Jupyter Notebook
### Jupyter Notebook là gì?
- Jupyter Notebook là công cụ giúp:
  + Viết code Python.
  + Chạy từng đoạn code.
  + Hiển thị biểu đồ.
  + Trình bày báo cáo trực quan.
- File giaxang.ipynb chính là file Notebook của Jupyter.

### Cách cài
- Mở Command Prompt và nhập: ```pip install notebook```
- Kiểm tra cài đặt: ```jupyter notebook``` -> Nếu trình duyệt tự mở giao diện Jupyter là thành công.

### Bước 3: Cài các thư viện cần thiết
- Chương trình sử dụng các thư viện:
  + pandas
  + numpy
  + matplotlib
- Cách cài: Mở Command Prompt và chạy:
```pip install pandas numpy matplotlib```

## 5. Mở file Notebook
Sau khi cài đặt xong, tiến hành mở file giaxang.ipynb.
### Cách 1: Mở bằng Jupyter Notebook
- Mở Terminal tại thư mục chứa file giaxang.ipynb và chạy: ```jupyter notebook```
- Sau đó:
  + Trình duyệt sẽ tự mở.
  + Chọn file giaxang.ipynb.

### Cách 2: Mở bằng VS Code
- Cài extension Python và Jupyter.
- Mở file giaxang.ipynb.
- Nhấn nút Run để chạy từng ô.

## 6. Cách chạy chương trình
- Chạy từng ô code: Trong Notebook, chương trình được chia thành nhiều ô code.
- Để chạy:
  + Chọn ô code
  + Nhấn: ```Shift + Enter``` hoặc nhấn biểu tượng ▶ (Run) ở bên trái ô code để thực thi chương trình.
- Sau khi chạy:
  + Kết quả sẽ hiển thị ngay bên dưới ô code.
  + Nếu là biểu đồ, hệ thống sẽ tự động hiển thị hình ảnh trực quan.
  + Nếu là bảng dữ liệu, Notebook sẽ hiển thị bảng thống kê tương ứng.

## 7. Kết quả đạt được
Sau khi chạy chương trình:
- Hiển thị đầy đủ thống kê giá xăng.
- Sinh các biểu đồ trực quan.
- Xác định xu hướng tăng giảm.
- Phân tích dữ liệu theo tháng và năm.
- Tìm được các giai đoạn biến động mạnh.

## 8. Ưu điểm của chương trình
- Giao diện trực quan.
- Biểu đồ dễ hiểu.
- Thuật toán phân tích rõ ràng.
- Xử lý dữ liệu nhanh.
- Dễ mở rộng thêm dữ liệu.

## 9. Hạn chế
- Chưa dự đoán giá tương lai.
- Chỉ phân tích dữ liệu lịch sử.
- Chưa kết nối dữ liệu thời gian thực.

## 10. Hướng phát triển
Trong tương lai có thể:
- Áp dụng Machine Learning để dự đoán giá xăng.
- Kết nối API cập nhật dữ liệu tự động.
- Xây dựng dashboard trực tuyến.
- Phân tích thêm dầu diesel và E5.

## 11. Kết luận
Đề tài đã xây dựng thành công hệ thống phân tích giá xăng RON 95 bằng Python.
Chương trình:
- Xử lý dữ liệu hiệu quả.
- Trực quan hóa rõ ràng.
- Hỗ trợ phân tích xu hướng biến động giá.
- Giúp người dùng dễ dàng theo dõi thị trường xăng dầu.
Thông qua bài toán này có thể thấy Python là công cụ mạnh trong:
- Phân tích dữ liệu.
- Thống kê.
- Trực quan hóa.
- Khai thác dữ liệu thực tế.
