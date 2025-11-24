# 🤖 Cuối kỳ Khai Phá Dữ Liệu & Học Máy 

## 📌 Giới Thiệu Dự Án 

Đây là dự án ứng dụng các thuật toán Học máy và Khai phá dữ liệu để giải quyết bài toán . Dự án bao gồm các giai đoạn: tiền xử lý dữ liệu, phân tích khám phá (EDA), xây dựng mô hình phân loại (Classification) và thực hiện phân cụm (Clustering).

Mục tiêu chính là tìm ra mô hình dự đoán hiệu quả nhất và rút ra các thông tin chi tiết có giá trị từ dữ liệu.

## 🎯 Mục Tiêu Chính

1.  **Tiền xử lý Dữ liệu:** Xử lý và làm sạch dữ liệu thô để tối ưu hóa đầu vào cho các mô hình Học máy.
2.  **Xây dựng Mô hình Phân loại:** Áp dụng và đánh giá hiệu suất của nhiều thuật toán Phân loại khác nhau.
3.  **Thực hiện Phân cụm:** Áp dụng Phân cụm (Clustering) để khám phá cấu trúc và nhóm tự nhiên trong dữ liệu.
4.  **Đánh giá Hiệu suất:** So sánh hiệu suất của các mô hình đã xây dựng để chọn ra mô hình tối ưu.

## 🛠️ Công Cụ và Công Nghệ

| Công cụ | Tệp Notebook liên quan | Mục đích |
| :--- | :--- | :--- |
| **Python** | `Data_preprocessing.ipynb`, các tệp `.ipynb` khác | Ngôn ngữ lập trình chính cho phân tích và mô hình hóa. |
| **Pandas, NumPy** | `Data_preprocessing.ipynb` | Thao tác và tính toán trên dữ liệu. |
| **Scikit-learn** | Tất cả các tệp mô hình | Triển khai các thuật toán ML: Decision Tree, Random Forest, KNN. |
| **Jupyter Notebook** | Tất cả các tệp `.ipynb` | Môi trường lập trình để ghi chép và thực thi code từng bước. |

## 📁 Cấu Trúc Repository

| Tên Tệp | Mô tả |
| :--- | :--- |
| `Data_preprocessing.ipynb` | **Giai đoạn Tiền xử lý:** Xử lý dữ liệu thô, làm sạch, xử lý Missing Values, và chuẩn hóa/mã hóa dữ liệu. |
| `preprocessed_data_finalversion.csv` | Dữ liệu sau khi đã được tiền xử lý và sẵn sàng cho giai đoạn mô hình hóa. |
| `Decision_Tree_,_Random_Forest_.ipynb` | Xây dựng và đánh giá mô hình **Cây Quyết định (Decision Tree)** và **Rừng Ngẫu nhiên (Random Forest)**. |
| `KNNCK_pynb.ipynb` | Xây dựng và đánh giá mô hình **K-Nearest Neighbors (KNN)**. |
| `Hierarchical.ipynb` | Áp dụng thuật toán **Phân cụm Phân cấp (Hierarchical Clustering)** để khám phá nhóm dữ liệu. |
| `Final_KHO_(1).ipynb` | Tệp Notebook tổng hợp cuối cùng (có thể là tệp tổng hợp các mô hình hoặc báo cáo cuối dự án). |
| `final_dw.csv` | Tập dữ liệu cuối cùng của dự án (Data Warehouse/Final Data). |

## 🧪 Kết Quả và Phân Tích Mô Hình

Dự án đã tập trung vào các thuật toán sau:

### 1. Phân loại (Classification)
* **Decision Tree & Random Forest:** Đánh giá hiệu suất dự đoán (Accuracy, F1-Score, v.v.) của hai mô hình cây này.
* **K-Nearest Neighbors (KNN):** Phân tích hiệu suất của mô hình KNN và tối ưu hóa tham số K.

### 2. Phân cụm (Clustering)
* **Hierarchical Clustering:** Áp dụng để xác định các nhóm tự nhiên trong dữ liệu, hỗ trợ cho việc phân khúc khách hàng hoặc nhận dạng mẫu.

[**Ghi chú:** *Bạn nên bổ sung thêm kết quả cụ thể ở đây, ví dụ: "Mô hình Random Forest đạt Accuracy cao nhất là 85%."*]

## 💡 Hướng Phát Triển Tương Lai

* Thử nghiệm các mô hình Học máy phức tạp hơn (ví dụ: Support Vector Machines, Gradient Boosting).
* Thực hiện tối ưu hóa siêu tham số (Hyperparameter Tuning) chuyên sâu hơn.
* Xây dựng giao diện đơn giản (ví dụ: Streamlit) để trực quan hóa kết quả dự đoán.
