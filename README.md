# Fashion-Marketing-Sales-Analysis
It is a fashion company, operating mainly in the retail and e-commerce sectors. The company develops multiple multi-channel marketing campaigns (online and offline) to drive sales and build its brand.

## I. Introduction
### 1. Introduction to Dataset
The dataset includes: 
- Total revenue information (“Order” table) which includes revenue through advertising (“mkt_camp_by_sku_cost” table)
- Marketing spending data including budget, CPM, CPC, CTR, etc. (“mkt_camp_cost” table) along with product categories and classifications to serve the analysis of sales performance and marketing investment efficiency.

### 2. Data Model
<img width="1336" height="1294" alt="image" src="https://github.com/user-attachments/assets/50946d3a-4dbb-4649-b54e-a2a6f4b01541" />

### 3. Business Questions
- Build tactical reports to help company leaders understand the budget spending process and the performance of marketing campaigns.
- Link sales revenue with marketing spending, optimize marketing budget performance based on KPIs.
- From there, propose tactics to improve performance.

## II. Design Thinking Method
Here are the five steps of design thinking:
### Step 1: Empathize
<img width="1091" height="1120" alt="image" src="https://github.com/user-attachments/assets/4e5bf480-53f7-46e6-9e0e-32fae778ee7c" />

### Step 2: Define
<img width="699" height="816" alt="image" src="https://github.com/user-attachments/assets/b026bb62-af0e-4ba9-8d9b-b3bd112afe38" />

### Step 3: Ideats
<img width="1324" height="694" alt="image" src="https://github.com/user-attachments/assets/476fcee6-ef35-4266-a056-bc33bbc734df" />

### Step 4: Prototype

### Step 5: Review

## III. Visualization
### 1. Overview
<img width="2198" height="1240" alt="image" src="https://github.com/user-attachments/assets/c283d3e9-ffde-494b-ad58-e73804585cd4" />

### 2. Campaign Analysis
<img width="2046" height="1169" alt="image" src="https://github.com/user-attachments/assets/1a9b0dd4-fda5-4a28-a954-61943f9dea35" />

### 3. Product Performance
<img width="2044" height="1152" alt="image" src="https://github.com/user-attachments/assets/1a22cf33-2aa9-4fc1-8d52-c3c5a27196c3" />

## IV. Recommand & Insights
### 1. OVERVIEW PAGE – “Toàn cảnh hoạt động Marketing & Sales”
- Key Insights
  + Hiệu quả quảng cáo nổi bật:
    + Doanh thu từ Ads đạt 3.02bn / 4.77bn (≈63%), chứng tỏ quảng cáo là kênh mang lại phần lớn doanh thu.
    + ROAS = 7.67, thể hiện hiệu quả chi tiêu quảng cáo cao (mỗi 1 đồng chi ra thu về 7.67 đồng doanh thu).
  + Chi tiêu ổn định, hiệu suất tốt:
    + Tổng ngân sách: 476.3M, chi tiêu thực tế 394M → Tỷ lệ sử dụng ngân sách ~82.75%, cho thấy có dư địa tối ưu mà không bị overbudget.
    + Tuần 3–4 đạt đỉnh doanh thu (1.58bn–1.54bn), trùng với mức chi tiêu cao → mối tương quan tích cực giữa spend và revenue.
  + Phân tích sản phẩm theo danh mục:
    + “Váy Chiết Eo Xòe” và “Áo Tách Set” là 2 sản phẩm top đầu, chiếm hơn 50% doanh thu tổng.
    + Doanh thu trực tiếp (Direct Sales) cao ở nhóm váy → có thể do sức hút thương hiệu hoặc tệp khách hàng trung thành.
  + Phân bổ chiến dịch:
    + Phần lớn chiến dịch có ROAS < 20, tập trung quanh mức 5–10 → hiệu quả đồng đều, ít outlier quá tốt hoặc quá kém.
- Recommendations
  + Tăng ngân sách cho nhóm chiến dịch có ROAS > 10 (như AUDREY SHIRT LAL new – ib – Op).
  + Tập trung marketing nhiều hơn cho các dòng sản phẩm top như Váy Chiết Eo Xòe, Áo Tách Set.
  + Duy trì tỷ lệ chi tiêu ~80–85% ngân sách → giúp tối ưu hiệu quả mà vẫn linh hoạt.
 

### 2. CAMPAIGN ANALYSIS PAGE – “Phân tích hiệu quả từng chiến dịch quảng cáo”
- Key Insights
  + Hiệu suất quảng cáo cao nhưng cần tinh chỉnh:
    + CPC trung bình 9.46K, CTR 0.82%, cho thấy chi phí click cao nhưng tỷ lệ nhấp thấp → cần cải thiện nội dung hoặc target audience.
    + CPM 77.14K là khá cao → quảng cáo hiển thị đắt, có thể do cạnh tranh ngành.
  + Quan hệ CPC–CTR nghịch biến:
    + Biểu đồ scatter cho thấy khi CPC tăng, CTR giảm → chi phí cao chưa chắc mang lại tương tác tốt.
  + Top chiến dịch nổi bật:
    + AUDREY SHIRT LAL new – ib – Op đứng đầu cả về doanh thu (264M) và ROAS (10.96).
    + Một số chiến dịch như KATY DRESS có ROAS cao (9.1) nhưng CTR thấp (0.33%) → tiềm năng tăng trưởng nếu tối ưu nội dung.
  + Biến động theo ngày:
    + Có giai đoạn tỷ lệ Spend vs Budget vượt 150% → khả năng overspend ngắn hạn, cần kiểm soát tần suất bidding.
- Recommendations
  + Tối ưu nội dung quảng cáo (creative): Nâng CTR lên >1% để cải thiện hiệu suất chi phí.
  + Giữ lại nhóm chiến dịch có ROAS > 8 làm core, thử nhân rộng mô hình quảng cáo tương tự.
  + Theo dõi Spend ratio theo ngày → tránh peak overspend gây lãng phí ngân sách.

### 3. PRODUCT PERFORMANCE PAGE – “Hiệu suất sản phẩm”
- Key Insights
  + Hiệu quả sản phẩm theo danh mục:
    + Nhóm váy vẫn chiếm ưu thế trong doanh thu từ Ads.
    + “Áo Tách Set” và “Váy Chiết Eo Xòe” là top 2 sản phẩm có doanh thu cao nhất → tập trung vào hai nhóm này có thể nâng tổng doanh thu đáng kể.
  + Phân tích chi tiết sản phẩm:
    + Ví dụ “Áo Khoác” đang bán ra với doanh thu 2.64bn, COGS 0.75bn, lợi nhuận gộp cao → nhưng chỉ “đang bán”, chưa đẩy mạnh Ads.
    + Tổng impression 5.1M nhưng CTR chỉ 0.8%, conversion rate 0.1% → funnel còn yếu ở bước chuyển đổi.
    + Top 5 chiến dịch theo Ads Revenue trùng với top của trang Overview → xác nhận xu hướng ổn định.
- Recommendations
  + Tăng đầu tư quảng cáo cho sản phẩm có biên lợi nhuận cao nhưng ít được đẩy Ads (ví dụ Áo Khoác).
  + Với các sản phẩm có CTR thấp nhưng doanh thu cao → thử các chiến dịch để mở rộng tệp khách.
  + Với sản phẩm có nhiều impression nhưng ít đơn hàng → cần cải thiện hình ảnh sản phẩm.
  + Theo dõi riêng hiệu quả Ads vs Direct Sales để tối ưu chiến lược marketing đa kênh.




