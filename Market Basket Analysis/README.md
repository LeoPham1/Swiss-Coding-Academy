## Mục Tiêu Dự Án
Tìm hiểu sự tương quan mua hàng thực phẩm trong nhà hàng để đưa ra chiến lược bán kèm hiệu quả.
## Nguồn dữ liệu được sử dụng:
Dữ liệu mua bán file excel
## Tổng quan về dữ liệu:
Apple : Táo
Banana: Chuối
Bread: Bánh Mì
Butter: Bơ
Cheese: Phô Mai
Eggs: Trứng
Jam: Mứt
Milk: Sữa

## Các công cụ được áp dụng:
pandas 
matplotlib.pyplot
seaborn 

## Những hiểu biết chính được khám phá:
#### Mối tương quan dương mạnh:
Bánh mì và bơ (0.66): Khách hàng mua bánh mì có xu hướng cao cũng mua bơ, thể hiện rõ mối liên kết giữa hai sản phẩm này trong giỏ hàng của người tiêu dùng.

Phô mai và mứt (0.63): Dữ liệu cho thấy khách hàng mua phô mai thường cũng mua mứt, có thể do nhu cầu kết hợp chúng trong các món ăn hoặc sở thích ăn uống.
#### Mối tương quan âm mạnh:
Sữa với phô mai (-0.44) và mứt (-0.44): Sữa có mối tương quan âm vừa phải với cả phô mai và mứt, cho thấy chúng có thể là sản phẩm thay thế hoặc ít được mua cùng nhau do thói quen tiêu dùng.
## Đề Nghị
Tối ưu hóa bố trí sản phẩm: Đặt các sản phẩm có mối tương quan dương gần nhau để khuyến khích mua hàng kết hợp.

Thiết kế chương trình khuyến mãi: Tạo các chương trình khuyến mãi kết hợp các sản phẩm có mối tương quan dương hoặc giảm giá cho một sản phẩm khi mua một sản phẩm khác có mối tương quan âm.


