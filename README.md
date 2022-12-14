# DWH-for-sales-data
1. Giới thiệu

  Bước đầu tìm hiểu về DWH, tôi đã dùng bộ dữ liệu có sẵn Northwind để xây một CSDL và một DWH. Sau đó, tôi tiến hành tính toán doanh thu và doanh số dựa trên dữ liệu của các sản phẩm đang được bán bởi công ty và dữ liệu về những nhà cung cấp sản phẩm cho công ty từ khắp các quốc gia trên thế giới. Thực nghiệm này chỉ vì mục đích học và nghiên cứu.

  Tôi đã sử dụng SQL server và BIDS trong thực nghiệm này.
  
2. Dữ liệu

CSDL Northwind:
![image](https://user-images.githubusercontent.com/75480501/181725046-384cbcee-8157-4ae3-af61-264aecbf8234.png)

Đối với DWH, tôi sẽ trích dữ liệu từ dữ liệu ban đầu thành CSDL mới:

![image](https://user-images.githubusercontent.com/75480501/181726078-e69aacb7-b21f-4ada-9f0a-bc2e8c71f0da.png)

Sau đó, tạo các query để nạp dữ liệu vào CSDL mới. Kế tiếp, tôi dùng BIDS để hoàn tất xây DWH và trích xuất các thông tin, báo cáo cần thiết.

3. Phân tích DWH đơn giản

Trên BIDS hỗ trợ rất nhiều trong trích xuất các báo cáo cần thiết. Tôi sẽ minh họa một vài ví dụ khi tôi thực hiện với nó. Đầu tiên là khi tôi gộp tất cả lại thì sẽ là thế này.
![image](https://user-images.githubusercontent.com/75480501/181736095-b2402757-ad77-47bc-a3d6-01ceeddb15f4.png)

Còn đậy là doanh số bán ra theo tên nhà cung cấp.
![image](https://user-images.githubusercontent.com/75480501/181736331-2206d214-4aca-4991-a849-80226ccc3d2c.png)

Khi tôi muốn biết doanh thu và doanh số bán ra theo từng sản phẩm thì sẽ thế này.
![image](https://user-images.githubusercontent.com/75480501/181736835-b700b61d-304e-46e4-8bd5-78e22dc4767d.png)

Ngoài ra, tôi cũng làm thêm vài thứ khác nữa.

4. Nguồn tham khảo

[1]Northwind and pubs sample databases for Microsoft SQL Server, https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs
