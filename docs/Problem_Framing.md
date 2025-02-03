# Problem Framing Document

## 1. Business Context
- **Công ty:** ABC Retail  
- **Vấn đề hiện tại:** Chiến dịch marketing chung → tỷ lệ chuyển đổi chỉ 12%  
- **Dữ liệu sẵn có:** Age, Income, Spending Score (200 khách hàng)

## 2. Objectives & KPI
| Objective | KPI | Target |
|-----------|-----|--------|
| Phân nhóm khách hàng | Silhouette Score | > 0.6 |
| Tăng hiệu quả marketing | Tỷ lệ chuyển đổi | +15% trong 3 tháng |

## 3. Stakeholder Map
```mermaid
graph TD
    A[Marketing Team]-->|Cần segment chi tiết| B(Data Analyst)
    B -->|Cung cấp data| C[Data Engineer]
    C -->|Yêu cầu business insight| D[CEO]
