# Tổng quan nghiên cứu – Literature Review

## 1. Thông tin đề tài

- **Tên đề tài:** Dự đoán mức độ nghiêm trọng của tai nạn giao thông bằng Machine Learning.
- **Bộ dữ liệu dự kiến:** US Accidents.
- **Mục đích:** Tổng hợp các nghiên cứu trước, phương pháp đã sử dụng, kết quả và hạn chế để làm cơ sở lựa chọn mô hình cho đề tài.

## 2. Bảng tổng hợp bài báo khoa học

| STT | Tác giả, năm | Tên bài báo | Dữ liệu | Phương pháp | Kết quả chính | Hạn chế | DOI/URL |
|---|---|---|---|---|---|---|---|
| 1 | Obasi & Benson (2023) | Evaluating the effectiveness of machine learning techniques in forecasting the severity of traffic accidents | Dữ liệu tai nạn và phương tiện tại Anh, 2005–2014; 2.047.256 bản ghi tai nạn | Random Forest, Logistic Regression, Naive Bayes, Artificial Neural Network | Random Forest và Logistic Regression đạt Accuracy 87%; Naive Bayes và ANN đạt 80% | Nghiên cứu dùng dữ liệu tại Anh và gộp 3 mức độ thành 2 lớp; cần kiểm tra khả năng áp dụng cho bộ dữ liệu US Accidents của nhóm | [DOI](https://doi.org/10.1016/j.heliyon.2023.e18812) |
| 2 | Chưa xác minh tên tác giả (2024) | Addressing imbalanced data in predicting injury severity after traffic crashes: A comparative analysis of machine learning models | Dữ liệu tai nạn tại Chicago, Hoa Kỳ, 2015–2023 | Random Forest, Logistic Regression, XGBoost, SVM; Oversampling, Undersampling, Hybrid sampling | SVM đạt hiệu quả tổng thể tốt nhất; SVM-SMOTE và ClusterCentroid là các phương pháp lấy mẫu nổi bật | Dữ liệu tại Chicago và mức mất cân bằng rất cao; cần kiểm tra khả năng áp dụng sang US Accidents | [DOI](https://doi.org/10.1016/j.procs.2024.05.192) |
| 3 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |
| 4 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |
| 5 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |
| 6 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |
| 7 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |
| 8 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |
| 9 | Chưa điền | Chưa điền | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa xác minh | Chưa điền |

## 3. Tiêu chí đọc và tổng hợp

1. Xác minh thông tin thư mục và đường dẫn bài báo.
2. Xác định bộ dữ liệu, biến mục tiêu và các đặc trưng đầu vào.
3. Ghi lại thuật toán và chỉ số đánh giá mà tác giả thực sự sử dụng.
4. Ghi kết quả theo bài báo gốc; không tự suy đoán số liệu.
5. Ghi hạn chế do tác giả nêu hoặc hạn chế có căn cứ từ phương pháp nghiên cứu.

## 4. Hướng tổng hợp

Sau khi đọc đủ tài liệu, tiến hành so sánh các thuật toán, cách xử lý dữ liệu mất cân bằng, chỉ số đánh giá và khả năng giải thích mô hình. Từ đó xác định hướng tiếp cận phù hợp với dữ liệu US Accidents của nhóm.
