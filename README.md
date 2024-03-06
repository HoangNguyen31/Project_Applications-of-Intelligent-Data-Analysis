# Project_Applications-of-Intelligent-Data-Analysis

## Giai đoạn 1: Thu nhập dữ liệu
- Ta sẽ đóng vai nhà phân tích dữ liệu và chủ đề ta cần phân tích đó là giá thuê căn hộ, chung cư ở Thành phố Hồ Chí Minh.
- Thực hiện thu thập dữ liệu của căn hộ, chung cư cho thuê ở Thành phố Hồ Chí Minh từ trang web [nhatot.com](https://www.nhatot.com/thue-can-ho-chung-cu-tp-ho-chi-minh).

## Giai đoạn 2: Tiền xử lý dữ liệu
- Kích thước dữ liệu, ý nghĩa các dòng và cột thuộc tính.
- Kiểu dữ liệu hiện tại của mỗi cột là gì? Có cột thuộc tính nào có kiểu dữ liệu không phù hợp không?
- Tình trạng lặp dữ liệu.
- Với mỗi cột số, các giá trị được phân bố như thế nào?
- Với mỗi cột phân loại, các giá trị được phân bổ như thế nào?
- Loại bỏ các cột thuộc tính không có ý nghĩa.
- Tình trạng khuyết dữ liệu và Xử lý tình trạng khuyết dữ liệu.

## Giai đoạn 3: Phân tích khám phá dữ liệu
- Phân tích dữ liệu đơn biến.
- Phân tích dữ liệu hai biến.
- Phân tích dữ liệu đa biến.

## Giai đoạn 4: Kiểm định giả thuyết
- Kiểm định một số giả thuyết thống kê.

## Giai đoạn 5: Dự đoán
- Áp dụng các mô hình học máy để dự đoán giá thuê căn hộ, chung cư:
  - Tiền xử lý dữ liệu:
    - Bỏ thuộc tính dữ liệu không cần thiết.
    - Số hóa thuộc tính phân loại.
    - Chuẩn hóa dữ liệu.
  - Mô hình học máy:
    - Linear Regression.
    - Random Forest.
    - XGBoost.
    - CatBoost.
  - Đánh giá kết quả:
    | Model             | Scores   | Times    |
    |-------------------|----------|----------|
    | Linear Regression | 0.167191 | 0.000965 |
    | Random Forest     | 0.185069 | 0.178749 |
    | Xgboost           | 0.779270 | 0.536250 |
    | CatBoost          | 0.832132 | 1.488418 |
  - Nhận xét:
    - Cả 4 thuật toán đều mô hình hóa thành công dữ liệu.
    - Mô hình `Xgboost` và `CatBoost` cho ra kết quả đưa ra kết quả khá tốt, cũng như thời gian chạy lâu hơn.
    - Mô hình đưa ra kết quả tốt nhất là `Random Forest` và `Linear Regression` cùng thời gian huấn luyện là nhanh nhất. Đây là 2 mô hình phù hợp với bài toán và dữ liệu đặt ra.
