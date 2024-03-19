Đề bài: Viết một script Bash để tự động cập nhật các package trên một máy chủ Linux.
Yêu cầu:
Script cần sử dụng ‘apt-get’ hoặc ‘yum’ để cập nhật các package.
Script phải được thiết kế để chạy định kỳ, chẳng hạn mỗi tuần hoặc mỗi tháng
Script cần ghi log lại quá trình cập nhật và gửi email thông báo kết quả cho quản trị viên
Đề bài: Viết một script Bash để tự động sao lưu cơ sở dữ liệu MySQL.
Yêu cầu:
Script cần kết nối tới csdl MySQL để sao lưu dữ liệu.
Script phải tạo ra các tập tin sao lưu có định dạng thời gian nhất định để dễ dàng quản lý.
Script cần kiểm tra xem sao lưu đã thành công hay không và ghi log lại kết quả
Đề bài: Viết một script Bash để tự động tạo và quản lý các bản sao lưu của csdl MongoDB.
Yêu cầu:
Script cần kết nối đến cơ sở dữ liệu MongoDB để tạo bản sao lưu.
Script phải tự động xóa các bản sao lưu cũ để tránh lãng phí không gian lưu trữ.
Script cần gửi email báo cáo kết quả của quá trình sao lưu.
Đề bài: Viết một script Bash để tự động kiểm tra và cập nhật SSL/TLS certificate trên máy chủ web.
Yêu cầu:
Script cần kiểm tra xem certificate hiện tại đã hết hạn chưa và tự động cập nhật nếu cần.
Script phải cập nhật cả certificate chính và certificate intermediate.
Script cần gửi email thông báo kết quả cập nhật đến người quản trị.
Đề bài: Viết một script Bash để tự động quét các tập tin log của ứng dụng và thông báo về các sự cố quan trọng.
Yêu cầu:
Script cần quét các tập tin log của ứng dụng để tìm kiếm các sự kiện quan trọng như lỗi hệ thống hoặc tấn công.
Script phải gửi email hoặc thông báo Slack về các sự kiện quan trọng đã được phát hiện.
Script cần chạy định kỳ và ghi log lại kết quả quét.
Đề bài: Viết một script Bash để tự động cài đặt và cấu hình môi trường phát triển trên một máy tính mới.
Script cần cài đặt các công cụ phát triển như Git, Node.js, Python, và các gói phần mềm khác.
Script phải cấu hình các biến môi trường và tùy chọn cấu hình cho môi trường phát triển.
Script cần chạy một loạt các kiểm tra tự động để đảm bảo rằng môi trường đã được cài đặt đúng cách.
Đề bài: Viết một script Bash để tự động đồng bộ hóa các thay đổi từ một repository Git lên máy chủ triển khai.
Yêu cầu:
Script cần pull các thay đổi từ repository Git về máy chủ triển khai.
Nếu có thay đổi mới, script phải thực hiện các bước cần thiết để cập nhật ứng dụng hoặc dịch vụ trên máy chủ.
Script cần chạy định kỳ để đảm bảo rằng máy chủ luôn được cập nhật với phiên bản mới nhất.
Đề bài: Viết một script Bash để tự động cài đặt và cấu hình các công cụ DevOps phổ biến như Docker và Kubernetes.
Yêu cầu:
Script cần cài đặt Docker và Kubernetes trên một máy chủ Linux.
Sau khi cài đặt, script phải cấu hình Docker và Kubernetes để chuẩn bị cho việc triển khai và quản lý container.
Script cần kiểm tra lại việc cài đặt và cấu hình để đảm bảo rằng môi trường đã được thiết lập đúng cách.
Đề bài: Viết một script Bash để tự động định cấu hình firewall trên một máy chủ Linux.
Yêu cầu:
Script cần mở các cổng cần thiết cho dịch vụ như SSH, HTTP, và HTTPS.
Script cần tạo các quy tắc firewall để chặn truy cập từ các địa chỉ IP không an toàn.
Script cần chạy mỗi khi máy chủ khởi động lại để đảm bảo rằng các cài đặt firewall được áp dụng.
Đề bài: Viết một script Bash để tự động kiểm tra sự khả dụng của các máy chủ trong một cụm máy chủ.
 	Yêu cầu:
Script cần ping các máy chủ trong cụm và kiểm tra xem chúng có phản hồi không.
Nếu một máy chủ không phản hồi, script cần gửi thông báo cảnh báo cho nhóm quản trị.
Script cần chạy định kỳ để theo dõi liên tục trạng thái của các máy chủ.
Đề bài: Viết một script Bash để tự động tạo và quản lý các backup của các máy chủ trong một hạ tầng điện toán đám mây.
Yêu cầu:
Script cần kết nối đến các máy chủ trên điện toán đám mây và tạo bản backup của hệ thống hoặc dữ liệu quan trọng.
Script phải xác định và tuân thủ các quy tắc sao lưu như chu kỳ sao lưu và lưu trữ sao lưu.
Script cần ghi log lại quá trình sao lưu và gửi email thông báo cho người quản trị.
Đề bài: Viết một script Bash để tự động kiểm tra các gói phần mềm đã cài đặt trên một máy chủ Linux và cập nhật chúng nếu cần.
Yêu cầu:
Script cần kiểm tra xem các gói phần mềm đã cài đặt trên máy chủ có phiên bản mới không.
Nếu có phiên bản mới, script phải cập nhật gói phần mềm đó lên phiên bản mới nhất.
Script cần chạy định kỳ để đảm bảo rằng máy chủ luôn được cập nhật với các bản vá bảo mật và các cải tiến mới nhất.
Đề bài: Viết một script Bash để tự động gửi email báo cáo hàng ngày về trạng thái của hạ tầng IT.
Yêu cầu:
Script cần tổng hợp thông tin về CPU, RAM, lưu lượng mạng, và các sự kiện quan trọng khác từ các máy chủ và dịch vụ.
Script phải gửi email chứa báo cáo hàng ngày đến địa chỉ được chỉ định.
Script cần được cấu hình để chạy mỗi ngày vào thời điểm cố định.
Đề bài: Viết một script Bash để tự động kiểm tra tính sẵn sàng của một ứng dụng web bằng cách kiểm tra trang web và kiểm tra response code.
Yêu cầu:
Script cần gửi yêu cầu HTTP GET đến trang web và kiểm tra response code.
Nếu response code không phải 200 OK, script phải gửi email cảnh báo đến nhóm quản trị.
Script cần chạy định kỳ để theo dõi liên tục trạng thái của ứng dụng web.
