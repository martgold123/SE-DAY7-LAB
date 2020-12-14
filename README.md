# SE-DAY7-LAB-HaQuocViet-18001084
PROPERTY MANAGEMENT SYSTEM

1.Mục tiêu: Xây dựng app quản lý khách sạn dành cho quản lý, nhân viên bán hàng,lễ tân. 
  Thiết bị : Máy tính cá nhân, Tablet.
2.Chức năng :
  + Khách hàng : Phần mềm có thể đặt-hủy phòng và nhận phòng, thực hiện các thanh toán , giao dịch online cho khách hàng.
  + Nhân viên Lễ Tân ( Receptionist ) : Tìm phòng trống theo yêu cầu trực tiếp của khách, Check-in cho khách đã đặt phòng , Check-out cho khách, In hóa đơn cho khách.
  + Nhân viên bán hàng ( Saler ) : Tìm phòng trống, Đặt phòng theo yêu cầu của khách.
  + Quản lý ( Manager ) : 
  -Thêm/Sửa/Xóa thông tin phòng 
  -Xem báo cáo doanh thu,báo cáo tỉ lệ phòng trống theo (thời gian/phòng/loại phòng).
  -Xem báo cáo khách hàng đặt nhiều theo thời gian.
  
  3. Các đối tượng :
  -	Thông tin về khách sạn bao gồm : tên, địa chỉ, số sao, mô tả (bao gồm mô tả bằng text và bằng hình ảnh).
  - Thông tin về phòng bao gồm : : tên phòng (duy nhất, để phân biệt các phòng), loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng.
  - -	Mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...
  
  
  4. Mô tả hệ thống : 
-	Mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau.
-	Mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau.
-	Tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể.
-	Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.
-	Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.
-	Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán.
-	Khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo.

  
  






