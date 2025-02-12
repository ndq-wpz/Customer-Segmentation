# 🎯 Customer Segmentation Project
![Cluster Visualization](reports/results/visualize_final_Cluster.pdg)

## 📌 Problem Framing 
**Business Question:**  
"Tăng hiệu quả marketing 15% dựa trên phân nhóm khách hàng theo hành vi chi tiêu"

**Success Metrics:**  
- Xác định 5 phân khúc khách hàng (K_mean = 5)  
- Tài liệu hóa đặc điểm từng nhóm
  
[**Chi tiết Problem Framing →**](docs/Problem_Framing.md)

## 🛠 **Công nghệ**
- Python 3.10
- Thư viện: NumPy, Pandas, Scikit-learn, Matplotlib
- Tools: Github (triển khai, restore dự án) Jupyter Notebook (Anaconda), Power BI

## 📂 **Cấu trúc Dự án**

```plaintext
customer-segmentation/
├── 📂 docs/
│   ├── 📂 raw                           # Chứa file dữ liệu gốc
│   └── 📂 processed                     # Chứa dữ liệu đã qua xử lý
│        ├── cleaned_data.csv                    # Dữ liệu đã được làm sạch
│        └── standardize_data.csv                # Dữ liệu đã chuẩn hóa
│        └── standardize_data.csv                # Dữ liệu đã chuẩn hóa
│        └── customers_with_clusters.csv         # Dữ liệu đã phân nhóm, sẵn sàng trực quan hóa và phòng mar có thể dùng
├── 📂 notebooks/                        # Thư mục triển khai Jupyter Noteboook
│   ├── 1_Data_Cleaning.ipynb                   # Notebook xử lý dữ liệu thô, làm sạch 
│    ├── 2_EDA.ipynb                             # Notebook thực hiện phân tích khám phá dữ liệu (EDA)
│   └── 3_Clustering_Model.ipynb                # Notebook thực hiện phân nhóm khách hàng
├── 📂 report/
│   ├── 📂 figures/                            # Thư mục chứa các biểu đồ và hình ảnh trực quan hóa kết quả.
│   └── 📂 results/                            # Chứa tài liệu báo cáo kết quả phân tích dữ liệu.     
│       └── EDA/                                    # Tổng hợp kết quả từ giai đoạn phân tích khám phá dữ liệu. 
│        │   └── 📂 Elements/                             # Hình ảnh/ minh họa cho phân tích EDA
│        │   └── eda_summary.md                           # Tóm tắt kết quả phân tích khám phá dữ liệu (EDA) 
│        └── data_sample.ipynb
│        ├── cluster_summary.md                  # Tóm tắt dữ liệu khác hàng phân nhómnhóm
│        ├── final_report.pdf                    # Báo cáo tổng hợp cuối cùng về phân nhóm khách hàng.
│        └── visualize_by_PBI.pdf           # Visualize bằng Power BIBI
├── 📂 src/
│   ├── data_preprocessing.py                   # Script tiền xử lý dữ liệu.
│   ├── visualization.py                        # Script tạo biểu đồ, phân tích cụm và tính toán độ hiệu quả của mô hình clustering.  
├── requirements.txt                       # Danh sách các thư viện Python cần thiết để chạy dự án.
├── .gitignore.md
└── README.md                              # Hướng dẫn tổng quan về dự án, cách sử dụng và mục tiêu phân tích.
```
## 📖 Hướng dẫn  
Dự án này nhằm phân tích và phân nhóm khách hàng dựa trên dữ liệu thu thập được.

### 1️. **Cài đặt môi trường**  
Cài đặt các thư viện cần thiết bằng cách chạy lệnh sau trong terminal hoặc command prompt: pip install -r requirements.txt

### 2️. **Cấu trúc dữ liệu**  
- **📂 docs/raw/**: Chứa dữ liệu gốc chưa qua xử lý.  
- **📂 docs/processed/**: Chứa dữ liệu đã qua xử lý, bao gồm dữ liệu đã làm sạch, chuẩn hóa và phân nhóm.  
- **📂 notebooks/**: Chứa các Jupyter Notebook thực hiện làm sạch dữ liệu, phân tích khám phá dữ liệu (EDA) và phân nhóm khách hàng.  
- **📂 report/**: Chứa kết quả phân tích dưới dạng biểu đồ, báo cáo markdown và tài liệu PDF.  
- **📂 src/**: Chứa các script Python hỗ trợ tiền xử lý dữ liệu và trực quan hóa kết quả.  

### 3️. **Chạy dự án**  
1. Mở và chạy notebook `1_Data_Cleaning.ipynb` làm sạch dữ liệu.  
2. Chạy `2_EDA.ipynb` khám phá dữ liệu.  
3. Chạy `3_Clustering_Model.ipynb` phân nhóm khách hàng.  
4. Kết quả trong thư mục [**Reports→**](reports/)   

---

## 📊 Kết quả  
Sau khi thực hiện phân nhóm khách hàng, dự án sẽ cung cấp:

- **Báo cáo phân tích khách hàng:**  
  - Tóm tắt xu hướng và đặc điểm từng nhóm khách hàng.  
  - Trực quan hóa dữ liệu bằng biểu đồ và đồ thị.  

- **Dữ liệu đã phân nhóm:**  
[**Xem chi tiết Dữ iệu khách hàng đã phân nhóm →**](data/processed/customers_with_clusters.csv)  

- **Báo cáo chi tiết:**  
[**Xem chi tiết Final Report →**](reports/results/final_report.pdf)

- **Báo cáo trực quan hóa:**  
[**Xem chi tiết Visualize →**](reports/results/visualize_by_PBI.pdf)

---

## 📑 Tài liệu  
Dưới đây là các tài liệu tham khảo và nguồn dữ liệu được sử dụng trong dự án:
### 1. **Nguồn dữ liệu**  
- Bộ dữ liệu khách hàng được lấy từ [Kaggle](https://www.kaggle.com/)

### 2. **Công cụ sử dụng**  
- **Python & Jupyter Notebook**: Xử lý dữ liệu và xây dựng mô hình.  
- **Pandas, NumPy, Scikit-learn**: Phân tích dữ liệu và phân nhóm.  
- **Matplotlib & Seaborn**: Trực quan hóa 
