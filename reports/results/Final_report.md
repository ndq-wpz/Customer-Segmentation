# **Báo cáo phân tích Phân nhóm Khách hàng**  
![Cluster Visualization](reports/results/Cluster_analysis/visualize_final_Cluster.png)  
### **1\. Tóm tắt dự án.**

* **Vấn đề kinh doanh:**  
   *"Chiến dịch marketing chung cho tất cả khách hàng dẫn đến tỷ lệ chuyển đổi thấp (12%)"*  
* **Giải pháp:**  
   *"Phân nhóm 5 cụm khách hàng dựa trên thu nhập và hành vi chi tiêu"*  
* **Kết quả chính:**  
  * Phát hiện 3 nhóm khách hàng tiềm năng  
  * Dự kiến tăng khoảng 15% doanh thu

**2\. Phương pháp luận**

### **2.1. Quy trình phân tích**

Data Collection → Data Cleaning → EDA → Clustering → Deployment

### **3\. Phân tích dữ liệu**

### **3.1. Phân phối dữ liệu**

![distribution](reports/figures/distributions.png)

* **Insight:**  
- “Độ tuổi tập trung chủ yếu từ 25 đến 40, với đỉnh là 30”   
- “Thu nhập phổ biến nằm trong khoảng $40,000 \- $80,000”  
- “Phân phối chi tiêu khá đều tạo đỉnh trong khoảng \-+ 50 tuổi”

![Box outliers](reports/figures/boxplot_outliers.png)

*  **Insight:**  
- “50% khách hàng nằm trong độ tuổi từ 28  \- 50, tập trung 25% nằm trong độ tuổi từ 28 \- 35”  
- “Khách hàng có thu nhập từ 40k$ \- 75$ chiếm 50% tổng số khách hàng”  
- “50 điểm chi tiêu nằm trong khoảng 35 \- 70”

### **3.2. Tương quan biến số**

  
**4\. Kết quả phân cụm**

### **4.1. Visualize 5 cụm khách hàng**
 
**4.2. Đặc điểm từng cụm**

![a](reports/figures/Table1.png)

### **4.3. Case study điển hình**
![N](reports/figures/Table2.png)

* **Khách hàng Cluster 0:** Thu trung + Chi trung  
  * **Tỷ lệ:** 41% - chiếm tỷ lệ lớn nhất trong cả 5 nhóm  
  * **Thu nhập bình quân:** 55.3   
  * **Tuổi bình quân:**  
  * **Điểm chi tiêu bình quân:**    
  * **Đặc điểm:**  Thu nhập và chi tiêu ở mức trung bình. Nhóm khách hàng có xu cân nhắc giá trị nhận đucowj so với số tiền mình bỏ ra  
  * **Hành vi:**   
  * **Gợi ý cho Campaign:**
    
* **Khách hàng Cluster 1:** Thu cao + Chi cao  
  * **Tỷ lệ:** 20%
  * **Thu nhập bình quân:**86.5   
  * **Tuổi bình quân:** 33 
  * **Điểm chi tiêu bình quân:** 82.1   
  * **Đặc điểm:** Thu nhập và chi tiêu cao. Sãn sàng đầu tư cho các sản phẩm/ dịch vụ cao cấp. Thường ưu tiên trải nghiệm và chất lượng, có thể chung thành và gắn bó với thương hiêu yêu thích.
  * **Hành vi:**   
  * **Gợi ý cho Campaign:**
      
* **Khách hàng Cluster 2:** Thu thấp + Chi cao  
  * **Tỷ lệ:** 18%
  * **Thu nhập bình quân:** 25.7   
  * **Tuổi bình quân:** 25
  * **Điểm chi tiêu bình quân:**  79.3
  * **Đặc điểm:** Khách hàng trẻ , thu nhập thấp nhưng chi tiêu cao, thích trải nghiệm và thích sự công nhận. Có thể sử dụng các gói tín dụng để bù đắp khả năng tài chính
  * **Hành vi:**   
  * **Gợi ý cho Campaign:**
      
* **Khách hàng Cluster 3:** Thu trung \+ Chi trung  
  * **Tỷ lệ:** 41% \- chiếm tỷ lệ lớn nhất trong cả 5 nhóm  
  * **Thu nhập bình quân:** 55.3   
  * **Tuổi bình quân:**  4141
  * **Điểm chi tiêu bình quân:**  
  * **Giới tính chiếm ưu thế:**  
  * **Đặc điểm:** Điểm chi tiêu thấp, mặc dù thuộc nhóm có thu nhập cao nhất. Ưu tiên tiết kiệm và đầu tư, không chi tiêu nhiều cho các hoạt động tiêu dùng. Ít bị ảnh hưởng bởi các chương trình khuyến mãi.
  * **Hành vi:**   
  * **Gợi ý cho Campaign:**
       
* **Khách hàng Cluster 4:** Thu thấp + Chi thấp  
  * **Tỷ lệ:** 11 
  * **Thu nhập bình quân:** 26.3
  * **Tuổi bình quân:** 45
  * **Điểm chi tiêu bình quân:**  20.9 
  * **Đặc điểm:** Thu nhập và chi tiêu đều thấp. Thường tìm kiếm sản phẩm hoặc giá rẻ hoặc khuyến mãi. Nhóm khách hàng nhạy cảm với giá cả, ưu tiên tính kinh tế.  
  * **Hành vi:**   
  * **Gợi ý cho Campaign:** 

---


### **4.2. KPI đo lường**

| Metric | Target | Timeline |
| ----- | ----- | ----- |
| Tỷ lệ chuyển đổi | +15% | 6 tháng |
| Chi phí acquisition |  | 3 tháng |

---

### **5\. Phụ lục kỹ thuật**

### **5.1. Elbow Method**  

![d](reports/figures/elbow_method.png)
### **5.2. Data Dictionary**

| Biến | Mô tả | Đơn vị |
| ----- | ----- | ----- |
| Spending Score | Điểm chi tiêu từ 1-100 | Điểm |

### **5.3. Giới hạn dự án**

* Chưa xét đến lịch sử mua hàng  
* Dữ liệu giới hạn ở 200 quan sát (khách hàng)

### **Công cụ sử dụng**
* Python & Jupyter Notebook: Xử lý dữ liệu và xây dựng mô hình.
* Pandas, NumPy, Scikit-learn: Phân tích dữ liệu và phân nhóm.
* Matplotlib & Seaborn: Trực quan hóa
---
