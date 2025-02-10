# 🎯 Customer Segmentation Project

## 📌 Problem Framing 
**Business Question:**  
"Làm thế nào tăng hiệu quả marketing 15% bằng cách phân nhóm khách hàng theo hành vi chi tiêu?"

**Success Metrics:**  
- Xác định 5 phân khúc khách hàng (Silhouette Score > 0.6)  
- Tài liệu hóa đặc điểm từng nhóm  

[**Xem chi tiết Problem Framing →**](docs/Problem_Framing.md)

## 🛠 **Công nghệ**
- Python 3.10
- Thư viện: Pandas, Scikit-learn, Matplotlib
- Tools: Jupyter Notebook, Docker

## 📂 **Cấu trúc Dự án**

```plaintext
customer-segmentation/
├── 📂 docs/
│   ├── 📂 raw # Chứa file dữ liệu gốc được thu thập
│   └── 📂 processed
        ├── cleaned_data.csv         # 
        └── standardize_data.csv     #
├── 📂 notebooks/
│   ├── 1_Data_Cleaning.ipynb
    ├── 2_EDA.ipynb                                 # Notebook chính thực hiện phân tích và phân nhóm khách hàng.
│   └── 3_Clustering_Model.ipynb                    # Notebook khám phá dữ liệu ban đầu.
├── 📂 report/
│   ├── 📂 figures/              # Thư mục chứa các biểu đồ và hình ảnh trực quan hóa kết quả.
│   └── report.pdf            # Báo cáo tổng kết kết quả phân tích.
├── 📂 src/
│   ├── data_preprocessing.py # Script tiền xử lý dữ liệu.
│   ├── clustering.py         # Script thực hiện phân cụm và tính toán Silhouette Score.
│   └── utils.py              # Các hàm tiện ích dùng chung.
├── Dockerfile                # File cấu hình Docker cho môi trường dự án.
├── requirements.txt          # Danh sách các thư viện cần cài đặt.
└── README.md                 # File hướng dẫn dự án (bản này).

## Hướng dẫn

## Kết quả

## Tài liệu
