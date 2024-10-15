# BÀI TẬP NHÓM QUẢN TRỊ HỆ THỐNG THÔNG TIN - NHÓM 1

## THÀNH VIÊN NHÓM
1. Hạ Quang Dũng
2. Lê Đình Tú
3. Đỗ Hữu Tuấn
4. Nguyễn Thị Thơm
5. Đỗ Hữu Thịnh

## GIỚI THIỆU CHỦ ĐỀ BÀI TẬP LỚN
### **Chủ đề:** 
**Xây dựng hệ thống bán hàng tự động đa nền tảng cho cửa hàng quần áo**

Đề tài này tập trung vào việc xây dựng một hệ thống bán hàng tự động, tích hợp nhiều nền tảng như fanpage Facebook, website bán hàng trực tuyến, và các sàn thương mại điện tử. Mục tiêu của hệ thống là tối ưu hóa quy trình kinh doanh cho cửa hàng quần áo bằng cách tự động hóa việc tiếp cận khách hàng, quảng bá sản phẩm, xử lý đơn hàng, thanh toán và chăm sóc khách hàng.

Ngoài ra, hệ thống CRM (Quản lý quan hệ khách hàng) sẽ giúp lưu trữ và phân tích dữ liệu khách hàng, cung cấp các công cụ hỗ trợ chăm sóc hiệu quả. Điều này không chỉ nâng cao trải nghiệm người dùng mà còn giúp tối ưu hóa hoạt động bán hàng và tăng doanh thu cho doanh nghiệp.

Hệ thống sẽ được thiết kế để tự động hóa các quy trình từ tiếp thị đến quản lý giao dịch, giúp doanh nghiệp tiết kiệm thời gian và nâng cao hiệu suất bán hàng.

---

## QUY TRÌNH THỰC HIỆN

### 1. Tương tác trên Fanpage Facebook
#### 1.1. Review sản phẩm
- Fanpage Facebook đăng bài review sản phẩm bao gồm hình ảnh, video và mô tả chi tiết.
- Các bài đăng có thể kèm theo bình luận, thảo luận và đánh giá từ khách hàng.

#### 1.2. Hành vi của khách hàng
- Khách hàng có thể "Thích", "Bình luận", "Chia sẻ" hoặc "Nhắn tin" trực tiếp với fanpage để hỏi thêm thông tin.
- Hành vi này giúp doanh nghiệp theo dõi mức độ quan tâm và tiềm năng mua hàng của khách.

#### 1.3. Gắn link điều hướng
- Các bài đăng hoặc tin nhắn tự động kèm theo liên kết dẫn đến website hoặc sàn TMĐT để khách hàng có thể mua hàng trực tiếp.
- Các liên kết này có thể sử dụng mã tracking để theo dõi nguồn gốc khách hàng.

### 2. Chuyển đổi từ Fanpage sang kênh bán hàng
#### 2.1. Truy cập website bán hàng
- Khách hàng nhấp vào liên kết dẫn đến website với thông tin chi tiết về sản phẩm và giá cả.
- Website tích hợp công cụ đo lường như Google Analytics, Facebook Pixel để theo dõi hành vi khách hàng.

#### 2.2. Mua hàng trên sàn thương mại điện tử
- Khách hàng cũng có thể điều hướng đến các sàn TMĐT như TikTok Shop, Shopee, Lazada để hoàn tất mua hàng.
- Hành vi như truy cập, xem sản phẩm, thêm vào giỏ hàng, và mua hàng được ghi nhận.

### 3. Ghi nhận thông tin vào CRM
#### 3.1. Tích hợp dữ liệu từ các kênh bán hàng
- **Từ Facebook**: CRM ghi nhận thông tin khách hàng như tên, lịch sử tương tác, sản phẩm quan tâm thông qua các công cụ phân tích.
- **Từ Website**: CRM lưu thông tin khách hàng như các sản phẩm đã xem, lượt truy cập, và các hành động mua hàng.
- **Từ sàn TMĐT**: CRM cập nhật thông tin đơn hàng, giá trị giao dịch và địa chỉ giao hàng qua API.

#### 3.2. Quản lý dữ liệu khách hàng
- CRM lưu trữ thông tin cá nhân, lịch sử tương tác và sản phẩm khách hàng quan tâm từ các kênh.
- Phân tích dữ liệu để xác định khách hàng tiềm năng và điều chỉnh chiến lược bán hàng phù hợp.

#### 3.3. Theo dõi hành vi và chăm sóc khách hàng sau bán
- Thực hiện các hoạt động chăm sóc khách hàng như gửi email cảm ơn, gợi ý sản phẩm, hoặc chương trình khuyến mãi.
- Theo dõi hành trình khách hàng từ khi quan tâm đến sản phẩm cho đến khi hoàn tất mua hàng.

### 4. Tích hợp ERP vào quy trình bán hàng và chăm sóc khách hàng
#### 4.1. Đồng bộ thông tin bán hàng từ Fanpage Facebook vào ERP
- ERP theo dõi đơn hàng từ fanpage và đồng bộ thông tin như sản phẩm, số lượng, giá trị đơn hàng, và trạng thái thanh toán.
- ERP cập nhật lượng hàng tồn kho ngay sau khi đơn hàng được xác nhận.

#### 4.2. Quản lý chuỗi cung ứng từ ERP
- Dựa vào dữ liệu từ fanpage và các kênh bán hàng, ERP sẽ tự động đề xuất đặt hàng bổ sung từ nhà cung cấp khi cần.

#### 4.3. Quản lý tài chính và hóa đơn trong ERP
- ERP quản lý các khoản thanh toán, hóa đơn liên quan đến đơn hàng từ các kênh bán hàng.
- Hệ thống tạo báo cáo doanh số, lợi nhuận và các chỉ số tài chính, giúp doanh nghiệp đánh giá hiệu quả từng kênh bán hàng.

### 5. Kết quả và lợi ích
- **Cải thiện tỷ lệ chuyển đổi**: Theo dõi hành trình khách hàng từ khi tương tác đến khi mua hàng giúp tối ưu hóa quy trình bán hàng và tăng tỷ lệ chuyển đổi.
- **Quản lý quan hệ khách hàng hiệu quả**: CRM giúp doanh nghiệp hiểu rõ hơn về hành vi khách hàng, từ đó cải thiện tiếp thị và chăm sóc khách hàng.
- **Đồng bộ hóa thông tin**: Khách hàng có trải nghiệm liền mạch từ lúc tương tác trên Facebook cho đến mua hàng, nhờ vào hệ thống CRM và ERP tích hợp chặt chẽ.


## Quy trình hệ thống
![Quy trình hệ thống](https://ibb.co/XSH0cHS)

## Quy trình trên website
![Quy trình trên website](https://ibb.co/Q70L4f2)

## Quy trình trên sàn Thương mại điện tử
![Quy trình trên sàn TMĐT](https://ibb.co/fQC11LG)
