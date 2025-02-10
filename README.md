# 🎯 Customer Segmentation Project

## 📌 Problem Framing 
**Business Question:**  
"Tăng hiệu quả marketing 15% dựa trên phân nhóm khách hàng theo hành vi chi tiêu"

**Success Metrics:**  
- Xác định 5 phân khúc khách hàng (K_mean = 5)  
- Tài liệu hóa đặc điểm từng nhóm
  
[**Xem chi tiết Problem Framing →**](docs/Problem_Framing.md)

## 🛠 **Công nghệ**
- Python 3.10
- Thư viện: NumPy, Pandas, Scikit-learn, Matplotlib
- Tools: Github (restore và diễn giả dự án) Jupyter Notebook (Anaconda), Docker

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
│   └── 📂 results/            # Báo cáo tổng kết kết quả phân tích.              
        └── EDA/
        │   └── 📂 Elements/
        │   └── eda_summary.md
        └── data_sample.ipynb
        └── final_report.pdf                
├── 📂 src/
│   ├── data_preprocessing.py # Script tiền xử lý dữ liệu.
│   ├── visualization.py         # Script thực hiện phân cụm và tính toán Silhouette Score.
├── requirements.txt          # Danh sách các thư viện cần cài đặt.
├── .gitignore.md
└── README.md                 # File hướng dẫn dự án (bản này).

## Hướng dẫn

## Kết quả

## Tài liệu
