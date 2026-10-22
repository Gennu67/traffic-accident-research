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
| 3 | Mostafa và cộng sự (2025) | AI-based prediction of traffic crash severity for improving road safety and transportation efficiency | Hơn 2,26 triệu bản ghi tai nạn giao thông | Các mô hình phân loại Machine Learning, Extra Trees, chọn đặc trưng và xử lý mất cân bằng | Extra Trees đạt Accuracy 96,19% và Macro F1-score 95,28% trong nghiên cứu | Cần kiểm tra khả năng khái quát hóa sang US Accidents và so sánh trên cùng quy trình đánh giá | [Bài báo gốc](https://www.nature.com/articles/s41598-025-10970-7) |
| 4 | Li và cộng sự (2023) | Crash injury severity prediction considering data imbalance: A Wasserstein generative adversarial network with gradient penalty approach | Dữ liệu tai nạn giao thông; chi tiết phạm vi và nguồn cần kiểm tra trong bài gốc | Logistic Regression, MLP, Random Forest, AdaBoost, XGBoost; WGAN-GP; SHAP | XGBoost kết hợp WGAN-GP đạt AUC 0,794 và sensitivity 0,698 | Phương pháp tạo dữ liệu tổng hợp phức tạp hơn; cần kiểm tra tính phù hợp với dữ liệu và nhãn của nhóm | [DOI](https://doi.org/10.1016/j.aap.2023.107271) |
| 5 | Al-Mistarehi và cộng sự (2022) | Using Machine Learning Models to Forecast Severity Level of Traffic Crashes by R Studio and ArcGIS | Dữ liệu tai nạn giao thông tại Zarqa City, Jordan, trong 5 năm | Random Forest, Decision Tree, AdaBoost; phân tích không gian và luật kết hợp | Random Forest đạt Accuracy cao nhất trong các mô hình được so sánh; bài báo đánh giá thêm Precision, Recall và F1-score | Dữ liệu địa phương tại Jordan; kết quả cần được kiểm chứng lại trên bộ US Accidents của nhóm | [DOI](https://doi.org/10.3389/fbuil.2022.860805) |
| 6 | Amiri, Afshari & Soltani (2025) | Machine learning approaches to traffic accident severity prediction: Addressing class imbalance | Dữ liệu tai nạn liên quan đến người đi bộ tại Australia, 2011–2021 | Logistic Regression, SVM, Decision Tree, XGBoost; SMOTE, ADASYN, Random Oversampling, Threshold Moving | XGBoost kết hợp Threshold Moving đạt F1-score 72% cho lớp tử vong và macro-accuracy 84% | Dữ liệu tập trung vào tai nạn liên quan đến người đi bộ tại Australia; cần kiểm tra khả năng khái quát hóa sang US Accidents | [DOI](https://doi.org/10.1016/j.mlwa.2025.100792) |
| 7 | Ma và cộng sự (2021) | RFCNN: Traffic Accident Severity Prediction Based on Decision Level Fusion of Machine and Deep Learning Model | Dữ liệu tai nạn giao thông tại Hoa Kỳ, 02/2016–06/2020 | Random Forest, CNN, mô hình kết hợp RFCNN | Báo cáo Accuracy 0,991, Precision 0,974, Recall 0,986 và F-score 0,980 với 20 đặc trưng quan trọng | Cần kiểm tra cách chia tập dữ liệu, rò rỉ dữ liệu và khả năng tái lập kết quả trước khi so sánh với mô hình của nhóm | [DOI](https://doi.org/10.1109/ACCESS.2021.3112546) |
| 8 | Chưa xác minh tên tác giả (2024) | Traffic accident severity prediction with ensemble learning methods | Dữ liệu tai nạn giao thông đô thị; cần kiểm tra chi tiết nguồn và phạm vi trong toàn văn | Random Forest, AdaBoost và các mô hình tổ hợp dựa trên cây quyết định | Random Forest đạt Accuracy 91,72%; AdaBoost đạt 91,27% theo phần tóm tắt | Cần kiểm tra phân bố lớp, cách chia tập dữ liệu và các chỉ số theo từng lớp trước khi so sánh với kết quả nhóm | [DOI](https://doi.org/10.1016/j.compeleceng.2024.109101) |
| 9 | Chưa xác minh danh sách tác giả (2023) | Advances, challenges, and future research needs in machine learning-based crash prediction models: A systematic review | Tổng hợp các nghiên cứu về dự đoán tai nạn giao thông và mức độ nghiêm trọng | Tổng quan hệ thống các phương pháp Machine Learning | Tổng hợp các hướng dự đoán tai nạn, tần suất tai nạn và mức độ nghiêm trọng; chỉ ra thách thức và hướng nghiên cứu tương lai | Phạm vi rộng, không tập trung riêng vào bộ US Accidents; cần đọc toàn văn để tổng hợp chi tiết các hạn chế | [DOI](https://doi.org/10.1016/j.aap.2023.107378) |
## 3. Tiêu chí đọc và tổng hợp

1. Xác minh thông tin thư mục và đường dẫn bài báo.
2. Xác định bộ dữ liệu, biến mục tiêu và các đặc trưng đầu vào.
3. Ghi lại thuật toán và chỉ số đánh giá mà tác giả thực sự sử dụng.
4. Ghi kết quả theo bài báo gốc; không tự suy đoán số liệu.
5. Ghi hạn chế do tác giả nêu hoặc hạn chế có căn cứ từ phương pháp nghiên cứu.

## 4. Hướng tổng hợp

Sau khi đọc đủ tài liệu, tiến hành so sánh các thuật toán, cách xử lý dữ liệu mất cân bằng, chỉ số đánh giá và khả năng giải thích mô hình. Từ đó xác định hướng tiếp cận phù hợp với dữ liệu US Accidents của nhóm.
