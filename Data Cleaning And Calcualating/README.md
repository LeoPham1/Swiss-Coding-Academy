## Mục Tiêu Dự Án
Làm sạch dữ liệu và tạo ra bảng matplotlib để so sánh tương quan 
## Nguồn dữ liệu được sử dụng:
Dữ liệu mua bán file excel
## Tổng quan về dữ liệu:
#### CustomerID
Mã định danh duy nhất cho mỗi khách hàng
#### Name
Họ và tên khách hàng
#### Date Of Birth
Ngày sinh của khách hàng
#### Sign upDate
Ngày khách hàng đăng ký tài khoản hoặc dịch vụ
#### Last Purchase Date
Ngày mua hàng gần nhất của khách hàng
#### Purchase Amount
Tổng số tiền khách hàng đã chi tiêu
#### Loyalty Points
Số điểm tích lũy của khách hàng trong chương trình khách hàng thân thiết
#### Region
Khu vực địa lý của khách hàng
#### Email
Địa chỉ email của khách hàng
#### Subscription Type
Loại gói đăng ký mà khách hàng đã chọn
## Các công cụ được áp dụng:
pandas 
matplotlib.pyplot
seaborn 
## Những hiểu biết chính được khám phá:
Mối tương quan yếu: Nhìn chung, các biến không có mối tương quan mạnh với nhau. Giá trị tương quan tuyệt đối lớn nhất là 0.57 giữa SignupDate và LastPurchaseDate, cho thấy mối tương quan dương vừa phải. Điều này có nghĩa là khách hàng đăng ký sớm hơn có xu hướng mua hàng lần cuối sớm hơn.
Không có tương quan tuyến tính: Các giá trị tương quan khác đều rất gần 0, cho thấy không có mối tương quan tuyến tính đáng kể giữa các biến còn lại. Ví dụ, số tiền mua hàng (PurchaseAmount) không liên quan nhiều đến điểm trung thành (LoyaltyPoints), ngày đăng ký (SignupDate), hoặc ngày mua hàng cuối cùng (LastPurchaseDate).
## Đề Nghị
Khuyến mãi: Do không có mối tương quan giữa điểm trung thành và số tiền mua hàng, có thể cần xem xét lại hiệu quả của chương trình khách hàng thân thiết hoặc điều chỉnh chính sách khuyến mãi.
Chăm sóc khách hàng: Do không có mối tương quan giữa ngày đăng ký và số tiền mua hàng, có thể cần tập trung vào việc chăm sóc khách hàng mới và khách hàng cũ để tăng giá trị mua hàng trung bình.
