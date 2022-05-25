# Store-NodeJS
## NodeJS + Nodemon + Visual Code

## *Mô tả: 
- Là 1 Website đơn giản để biết các lệnh trong nodejs.

Trang chủ:

![image](https://user-images.githubusercontent.com/101527833/170256434-baaed068-aa98-4229-93b2-3f4f17080020.png)

 

	 

	Đây là trang chủ giao diện chính gồm:
-	Có thanh công cụ vị trí đầu trang.
-	Logo shop.
-	Phần menu gồm 4 loại giày: 
+ nike
+ adidas.
+ puma.
+ vans.
Trang chi tiết sản phẩm

a)	ADIDAS:

 
 
b)	NIKE:

 

c)	PUMA:

 



d)	VANS:

 


	Trang chi tiết gồm:
-	Hình ảnh sản phẩm.
-	Thông tin sản phẩm.
-	Khách hàng, nhà cung cấp, loại và link sản phẩm.


Danh mục sản phẩm đã xem

-	Nằm ở phần cuối trang chi tiết sản phẩm:
-	Lúc đầu sẽ không có sản phẩm nào nếu đó là sản phẩm được xem đầu tiên.

 
 
 
2.6 CODE:
Cấu trúc chương trình

 


Cơ sở dữ liệu tạm để test

 



2.7 Thực hiện test:

File server.js

 



File model/pet.js


 



 


Thư mục chứa dữ liệu test

 
File test/indes.js

 
File test/pet.js

 


 
 
 



File test/users.js

 
-	Thực hiện Test với lệnh: npm run test.


Chạy TEST chương trình

 
	Khi chạy chương tình với lệnh npm run test ta được bảng kết quả:
-	Test kết nói thành công với GET indexs + time.
-	Kết nối thành công với GET, POST + truy suất được id của file pet + time chạy xong quá trình Test.
-	Test kết nói thành công với GET user + time.
