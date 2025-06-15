# <div align="center"> $\color{green}{\text {⭐Duy Swisscoding practice 6-1⭐}}$ 

## $\color{orange}{\text {⭐1. Bối cảnh}} $
* Ở practice này tôi cần đánh giá giúp công ty **TechStream Solutions** đánh giá *đơn vị kinh tế* của công ty trên mỗi cơ sở khách hàng, dựa trên dữ liệu họ thu thập được thông quá trình kinh doanh nhiều năm qua. Sản phẩm kinh doanh của họ là *nền tảng Software as a Service (SaaS)* có tên là *'Streamline Pro'*.
* **_TechStream Solutions_** cung cấp dự liệu trong đường dần sau đây: [Dữ liệu **_TechStream Solutions_**](https://drive.google.com/drive/folders/1qhOW9Y2orRXuzbX-kXEmuJ7TMQiRs2Uv?usp=drive_link)
  * Xác định lợi nhuận của việc thu hút và giữ chân khách hàng.
  * Đánh giá hiệu quả của chiến lược tiếp thị và bán hàng của họ.
  * Đưa ra quyết định sáng suốt về việc mở rộng quy mô hoạt động và tối ưu hóa việc phân bổ nguồn lực.
  * Thông tin này sẽ hướng dẫn TechStream Solutions cải thiện chiến lược kinh doanh, đảm bảo tăng trưởng bền vững và tối đa hóa lợi nhuận.
## $\color{orange}{\text {⭐2. Các yếu tố phân tích}} $
* Từ bối cảnh và mục đích trên ta phân tích các đơn vị kinh tế **_(Unit Economics)_**: <br>
  *1. CAC: Example Calculation* <br>
  *2. Average Revenue Per User (ARPU)* <br>
  *3. COGS* <br>
  *4. Gross Margin* <br>
  *5. LVT* <br>
  *6. LTV / CAC* <br>
* Cuối cùng là đánh giá *_(Conlusion)_* 
## $\color{orange}{\text {⭐3. Tính toán phân tích}} $
 ### ✅3.1 CAC: Example Calculation
 $$ {CAC} = \frac {TotalSalesandMarketingExpenses}{NumberofNewCustomersAcquired}$$
 
 * Tôi tính dựa trên 3 **Google sheet** trong source là: **Monthly_expenses** ; **Payroll** ; **daily_marketing_spendings**. Để có được 'TotalSalesandMarketingExpenses' = $76480.
 
 * Còn 'NumberofNewCustomersAcquired' = 63 , dựa trên **Google sheet: receipt_history**.
 
 **_↪ CAC = $1213.97_**
 
 ### ✅3.2 Average Revenue Per User (ARPU)
 $${APRU} = \frac{TotalRevenue}{NumberofUsers} $$
 
 * Cả 'TotalRevenue' = $83033 và 'NumberofUsers' = 292 tôi tính dựa trên **Google sheet: receipt_history**.

**_↪ ARPU = $284.36_**
 ### ✅3.3 COGS
 $$ {COGS} = {BeginningInventory}+{PurchasesDuringthePeriod}-{EndingInventory}$$

 * Bởi vi đây là công ty về phần mềm nên 'BeginningInventory' và 'EndingInventory' là không có*
 * 'PurchasesDuringthePeriod' tính dựa trên **Google sheet: Monthly_expenses**.
Riêng 2 phần mềm được sử dụng là **'Zoom'** và **'Slack'** không chỉ phòng thiết kế phần mềm sử dụng nên **_giả sử_** chi phí từ 2 phần mềm này họ chỉ sử dụng 60%.

**_↪ COGS = $20264.0_**
 ### ✅3.4 Gross Margin
$${GrossMargin} = \frac{(Revenue - COGS)}{Revenue}*100 $$

* 'TotalRevenue' = $83033 và 'COGS' = $20264.0.

**_↪ Gross Margin = 75.6%_**
 ### ✅3.5 LVT
$$ {LTV} = {ARPU}*{CustomerLifespan}*{GrossMargin} $$

* 'CustomerLifespan' được dựa trên **Google sheet: customers_lifespan_data** theo trung bình tháng 30 ngày.
* 'CustomerLifespan' = 9.84,'Gross Margin' = 75.6%, 'ARPU' = $284.36.

**_↪ LVT = $2115.52_**
 ### ✅3.6 LTV / CAC
$${LTV / CAC} = \frac{LTV}{CAC} $$

* 'LTV' = $2115.52, 'CAC' = $1213.97 .

**_↪ LTV / CAC = 1.74_**
## $\color{orange}{\text {⭐4. Đánh giá nhận định}} $

### $\color{red}{\text {⭐Nhận Định:}} $

**1. CAC:** $1213.97 .

**2. ARPU:** $284.36 .

**3. COGS:** $20264.0 .

**4. GROSSMARGIN:** 75.6% ↪  Biên độ lợi nhuận tốt (>50% ) .

**5. LVT:** $2115.52 .

**6. LTV/CAC:** 1.74 ↪ Các chính sách Marketing và sản phẩm sản xuất ra đang đi đúng hướng , đúng đối tượng khách hàng.

#### ↪ Tiếp tục thực hiện chiến lược kinh doanh của công ty, Marketing thêm nhằm tăng cường số lượng khách hàng mới, phát triển thêm phần mềm mới tới các khách hàng cũ -> nhằm tối ưu hơn về chính sách hậu mãi, cũng như tăng thêm lợi nhuận từng khách hàng lên.

## $\color{red}{\text {⭐NOTE:}}$ Tất cả các code thực hiện tôi để trong đường dẫn sau đây ↪ [Code thực hiện lấy và tính toán dữ liệu](https://github.com/haduy2009sg/Duy_Swisscoding_practice-6_1/blob/main/Duy_practice_6_1.ipynb)
