## Mục Tiêu Dự Án
Tìm ra mối tương quan giữa (tuổi, giới tính, thu nhập, điểm chi tiêu, sự hài lòng) của khách hàng khi đi mua hàng.
## Nguồn dữ liệu được sử dụng:
Dữ liệu mua bán và đánh giá của khách hàng
## Tổng quan về dữ liệu:
CustomerID: Mã số khách hàng
Age: Tuổi	
Gender: Giới Tính	
Income: Thu nhập	
Spending Score: Điểm chi tiêu của khách hàng	
Satisfaction Rating: Đánh giá của khách hàng
## Các công cụ được áp dụng:
pandas 
matplotlib.pyplot
seaborn 
## Những hiểu biết chính được khám phá:
Tuổi và Thu nhập: Có mối tương quan thuận khá mạnh (0.66). Điều này cho thấy khách hàng lớn tuổi có xu hướng có thu nhập cao hơn.
Tuổi và Điểm chi tiêu/Mức độ hài lòng: Có mối tương quan âm yếu (-0.16 và -0.057). Điều này cho thấy không có mối liên hệ đáng kể giữa tuổi tác và điểm chi tiêu hoặc mức độ hài lòng.
Thu nhập và Điểm chi tiêu/Mức độ hài lòng: Có mối tương quan âm rất yếu (-0.085 và -0.018). Điều này cho thấy không có mối liên hệ đáng kể giữa thu nhập và điểm chi tiêu hoặc mức độ hài lòng.
Điểm chi tiêu và Mức độ hài lòng: Có mối tương quan thuận trung bình (0.55). Điều này cho thấy khách hàng chi tiêu nhiều hơn có xu hướng hài lòng hơn.
## Đề Xuất
Phân khúc khách hàng: Nhóm khách hàng dựa trên tuổi và thu nhập để điều chỉnh các chiến dịch tiếp thị phù hợp.
Tối ưu hóa trải nghiệm khách hàng: Tập trung vào việc cải thiện mức độ hài lòng của khách hàng bằng cách không chỉ tập trung vào điểm chi tiêu mà còn cả các yếu tố khác.
