### Giới thiệu dữ liệu:
  Bộ dữ liệu về chuỗi cung ứng của công ty DataCo Global. Gồm các giao dịch của công ty với khách hàng. Tập dữ liệu gồm 53 thuộc tính khác nhau, từ thông tin đặt hàng và vận chuyển đến thông tin bán hàng, 180.519 hàng và các tính năng bao gồm sự kết hợp giữa dữ liệu văn bản và dữ liệu số, chẳng hạn như vị trí đặt hàng và dữ liệu bán hàng số. Cụ thể có 24 cột ký tự và 28 cột số.
  Data resource: https://data.mendeley.com/datasets/8gx2fvg2k6/5/files/72784be5-36d3-44fe-b75d-0edbf1999f65
  + 24 cột ký tự và 28 cột số.
  + 180.519 (dòng) * 40 (cột)
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/029eacf7-5ca4-4213-87fd-762bc9b506a4)

  Dựa vào tập dữ liệu thì chúng ta cần đưa ra các báo cáo về doanh số tổng quan của cũng như chi tiết của từng sản phẩm dựa theo từng thuộc tính khác nhau trong tập dữ liệu và đưa ra các nhận xét về cách vận hành của các phương thức vận chuyển từ đó cải thiện hiệu quả. Ngoài ra, còn có thể so sánh hiệu quả bán hàng của các đất nước và khu vực khác nhau.

### Từ các yêu cầu đó thì kho dữ liệu sẽ có:
•	Hai bảng Fact gồm FactSales và FactDelivery cả hai đều thuộc loại Transactions. Business process của mỗi bản Fact:

	FactSales: Dùng để phân tích và báo cáo doanh số, lợi nhuận và số lượng bán ra của từng sản phẩm theo từng thuộc tính.

	FactDelivery: Báo cáo về hoạt động của việc vận chuyển đơn hàng đến cho người dùng

•	Các bảng Dim gồm có: DimDepartment, DimShippingMode, DimTime, DimMarket, DimRegion, DimSegment, DimCustomer, DimCountry, DimCity, DimCategory

Fact Sales: 
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/a9b4cf17-3145-4ae8-8344-98b4a533057c)
Fact Delivery:
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/2bb6b5eb-b247-4869-8ac1-82aee77d83c7)
Constellation Schema:
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/6d15c7b8-16c4-4f01-8d78-ece21034b103)

Tích hợp dữ liệu vào kho (SISS)
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/ae97b4e8-29e2-40ea-8e1c-b69324ae4adb)
