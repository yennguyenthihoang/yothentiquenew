# yothentiquenew
Develop a web application for managing luxury products.


Web quản lí stock và trưng bày sản phẩm
1. Homepage: short sumary sản phẩm các hãng, estimate giá đặt hàng của 1 sản phẩm, thông tin shop hoặc đội ngũ phát triển phần mềm
2. Trang tính tiền giá order cho một số mặt hàng:
- Đồ siêu thị, quần áo thường: giá tag x 27 + kg x 220k/kg
- Nước hoa mỹ phẩm: giá tag x 27 + 300k/kg
- Đồ hiệu: 
+ LV: tag x 27 + 400k/kg
+ Dior, Gucci, Ysl, Prada, ...: tag x 27 x 0.95 + 400k/kg

3. Admin quản lí stock
- Roles: 
+ End clients: là khách hàng truy cập vào web chỉ có thể thấy toàn bộ sản phẩm mà các shop có cũng như giá thành. Có thể truy cập cách tính giá đặt hàng nhưng theo công thức trên + ít nhất 300/món
+ YO user (admin 1): có quyền login bằng user quy định trong hệ thống, có thể thấy được toàn bộ sản phẩm từ YO shop cũng như các shop khác, 
+ Shopper uer (Admin 2): có quyền login bằng user cấp cho mỗi shop, có thể thấy được sản phẩm chỉ của shop mình, giá nhập và giá bán lại cho YOthentique, giá bán lẻ cho khách hàng cuối

4. Generate barcode cho phép scan và ng dùng đi trực tiếp tới web

Công nghệ dự tính develop website:
https://dev.to/theme_selection/best-web-development-stack-2jpe
