Dựa vào tập dữ liệu thì chúng ta cần đưa ra các báo cáo về doanh số tổng quan của cũng như chi tiết của từng sản phẩm dựa theo từng thuộc tính khác nhau trong tập dữ liệu và đưa ra các nhận xét về cách vận hành của các phương thức vận chuyển từ đó cải thiện hiệu quả. Ngoài ra, còn có thể so sánh hiệu quả bán hàng của các đất nước và khu vực khác nhau.
Từ các yêu cầu đó thì kho dữ liệu sẽ có:
•	Hai bảng Fact gồm FactSales và FactDelivery cả hai đều thuộc loại Transactions. Business process của mỗi bản Fact:
	FactSales: Dùng để phân tích và báo cáo doanh số, lợi nhuận và số lượng bán ra của từng sản phẩm theo từng thuộc tính.
	FactDelivery: Báo cáo về hoạt động của việc vận chuyển đơn hàng đến cho người dùng
•	Các bảng Dim gồm có: DimDepartment, DimShippingMode, DimTime, DimMarket, DimRegion, DimSegment, DimCustomer, DimCountry, DimCity, DimCategory

Fact Sales: 
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/a9b4cf17-3145-4ae8-8344-98b4a533057c)
Fact Delivery:
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/2bb6b5eb-b247-4869-8ac1-82aee77d83c7)

Tích hợp dữ liệu vào kho (SISS)
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/ae97b4e8-29e2-40ea-8e1c-b69324ae4adb)
