---
title: Thiết lập bảo mật iPhone
tags:
  - iphone
  - security
  - guideline
source:
keyword:
created: 2025-11-23 12:10
modified: 2026-01-07 00:01
cover: https://i.imgur.com/0AgChWE.jpeg
banner: https://i.imgur.com/0AgChWE.jpeg
---
# Thiết lập tính năng bảo vệ thiết bị khi bị đánh cắp (Stolen Device Protection)
## Mục đích:
- Tính năng chỉ có ở phiên bản iOS 17.3 trở lên
- Chỉ có thể đổi mật khẩu tài khoản icloud ở những vị trí quen thuộc như nhà riêng, nơi làm việc hoặc các địa điểm bạn thường xuyên ghé thăm. 
- Ở những nơi quen thuộc yêu cầu "trì hoãn bảo mật". Giải thích là phải đợi 1 giờ mới có thể được đổi mật khẩu và phải xác thực bằng face ID mới có thể đổi
- **Lưu ý:** Khi bật chế độ trì hoãn bảo mật ***"Luôn luôn"***, iPhone sẽ yêu cầu xác thực sinh trắc học bằng Face ID hoặc Touch ID cho một số hành động quan trọng mà không có tùy chọn sử dụng mã PIN thay thế. (Password, mail,...)
## Hướng dẫn chi tiết:
- Truy cập **Face ID & mật mã** > Bảo vệ thiết bị khi bị đánh cắp > bật lên
- Tùy chọn: Cách xa các vị trí quen thuộc

![|500](https://i.imgur.com/pBNm8a7.png) 
# Thiết lập bật giới hạn:
## Mục đích:
- Bật tính năng giới hạn về bảo mât, quyền riêng tư như:
	- Không cho phép thay đổi mật mã & face ID (Mục mật khẩu và FaceID sẽ bị ẩn đi không hiện ra)
	- Không cho thay đổi tài khoản icloud (bao gồm cả không cho thoát tài khoản > Phần tài khoản sẽ bị làm mờ không click được)
## Hướng dẫn chi tiết:
### Bật tính năng giới hạn:
- Cài đặt > Thời gian sử dụng > Khóa cài đặt thời gian sử dụng > đặt mật mã **(Lưu ý không được trùng với mã mở khóa máy)**
- Bật giới hạn > Kéo xuống dưới cùng mục cho phép thay đổi đối với:
	- Mật mã & face ID: chọn **Không cho phép**
	- Tài khoản: chọn **Không cho phép**
- Sau khi thiết lập xong, mục Face ID & mật mã sẽ bị ẩn đi, mục truy cập tài khoản icloud cũng sẽ bị mờ đi như hình 

![|500](https://i.imgur.com/MoJrVDt.png) 

# Bảo mật khôi phục tài khoản:
## Mục đích:
- Dự phòng cho các trường hợp bị mất tài khoản không truy cập được
- Khôi phục bằng số điện thoại, khôi phục bằng người tin tưởng, người kế thừa, bằng khóa khôi phục
## Hướng dẫn chi tiết:
- Truy cập Cài đặt > tài khoản icloud > Đăng nhập và bảo mật
### Email & số điện thoại:
- Sử dụng 1 email chỉ dùng mục đích khôi phục tài khoản, không dùng các email được đăng nhập nhiều nơi, làm việc, giải trí
- Sử dụng số điện thoại chéo: vd như tài khoản A sử dụng số điện thoại của B để khôi phục và ngược lại, tránh trường hợp mất điện thoại sẽ bị gửi mã về đúng điện thoại đang sử dụng để lấy tài khoản
### Bảo mật:
- Bật xác thực 2 yếu tố: chức năng này yêu cầu phải có 2 thiết bị trở lên để cấp quyền truy cập cho nhau
### Phương pháp khôi phục:
- Liên hệ khôi phục: Gửi lời mời đến các tài khoản người thân trong gia đình để khôi phục khi bị mất quyền truy cập
- Khóa khôi phục: **Mã chỉ cấp 1 lần duy nhất** . Lưu lại ở 1 nơi khác ngoài điện thoại, ghi ra giấy, nhật ký, máy tính, hoặc tạo 1 nick name trong danh bạ note vào ghi chú của contact đó với cách mình dễ nhớ nhất
- Người kế thừa: Chọn 1 người sẽ kế thừa tài khoản

![|500](https://i.imgur.com/EUJEIW5.png) 
# Thiết lập bảo vệ SIM điện thoại:
## Mục đích:
- Khi bị mất điện thoại, kẻ gian không thể sử dụng sim để khôi phục mở khóa điện thoại, lấy cắp tài khoản, lừa đảo người thân
## Hướng dẫn xử lý:
- Ưu tiên sử dụng esim vì esim khi chuyển đổi máy phải ra nhà mạng xác thực để chuyển đổi thiết bị
- Cài đặt mã PIN cho SIM để khi mở máy sẽ phải nhập mã PIN mới sử dụng được. Chức năng này cần bật cho cả SIM vật lý lẫn eSIM.
	- ESIM mở máy lên sẽ hỏi mã
	- SIM vật lý lấy qua máy khác cũng sẽ hỏi mã
	- Mã mặc định của các nhà mạng
		- Viettel: 0000
		- MobiFone: 1111 hoặc 0000
		- VinaPhone: 1234
- Truy cập: Cài đặt > Di Động > Chọn SIM > kéo xuống dưới cùng chọn "PIN của SIM" > Thiết lập mã và ghi nhớ (Có thể dùng chung mã 4 số giống mã giới hạn bên trên)
# Tắt xem trước ở màn hình khóa:
## Mục đích:
- Tránh các trường hợp điện thoại đang khóa nhưng người khác vẫn xem được tin nhắn, quyền riêng tư
- Quan trọng hơn trong trường hợp mất điện thoại, kẻ gian lấy lại mật khẩu gửi OTP về SĐT để truy cập và đọc tin nhắn từ màn hình khóa
## Hướng dẫn xử lý:
- Cài đặt > Thông báo > Mục "Hiển thị bản xem trước" > Chọn "Khi được mở khóa"

![|500](https://i.imgur.com/au5dz3G.png) 

# Tắt quyền truy cập ở màn hình khóa
## Mục đích:
- Khóa các chức năng ở màn hình khóa như:
	- Trung tâm thông báo (Xem các thông báo như SMS, facebook, mail...)
	- Trung tâm điều khiển (Tắt mở bluetooth, mạng di động..) tránh khi mất máy tắt mạng 5G để tìm kiếm
	- Ví, phụ kiện...
## Hướng dẫn:
- Cài đặt > Face ID & Mật mã
- Kéo xuống mục "Cho phép truy cập khi bị khóa" > tắt các chức năng không muốn cho phép
	- Trung tâm thông báo
	- Trung tâm điều khiển
	- Ví, phụ kiện

![|500](https://i.imgur.com/zkqg0se.png) 
# Tự động xóa mã xác minh (OTP) sau khi sử dụng:
## Mục đích:
- Không lưu lại mã OTP sau khi sử dụng, tránh kẻ gian truy cập và lấy cắp
- Khi SMS OTP được gửi đến sẽ hiện thông báo OTP đến trên thông báo. Trên ứng dụng điền OTP sẽ hiển thị để tự động điền. Sau khi bấm vào sử dụng sẽ tự động xóa trong tin nhắn
- Chức năng này sẽ có lúc khá bất tiện đối với 1 vài ứng dụng không hỗ trợ tự điền, cần người dùng truy cập để xem lại và điền thủ công, nhiều khi sẽ không tìm thấy và khá khó chịu (Có thể tắt chức năng này)
## Hướng dẫn bật/tắt:
- Cài đặt > Cài đặt chung > Tự động điền & Mật khẩu > Kéo xuống dưới đến mục "Mã xác minh" > Xóa sau khi sử dụng > ON/OFF

![|500](https://i.imgur.com/I18kJEW.png) 
# Các lưu ý khác:
- Bảo mật giống như nhiều lớp khóa, khi sử dụng sẽ gây nhiều bất tiện nhưng an toàn khi có sự cố
- Các mật mã không được là ngày sinh, năm sinh của mình, hãy tạo mật khẩu ghép gồm nhiều người nhiều ngày kỉ niệm với nhau sẽ an toàn hơn
  
