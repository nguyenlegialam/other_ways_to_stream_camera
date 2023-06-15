# Các cách khác để thực hiện stream camera lên web  
  
# Cách 1: Sử dụng SDK của đầu thu Hikvision  
Ngôn ngữ: C#  
Nếu các tất cả các camera trong nhà đều được kết nối đến đầu thu Hikvision, có thể tham khảo, nghiên cứu SDK của nhà sản xuất cung cấp để thực hiện lấy luồng stream của camera thông qua đầu thu Hikvision làm trung gian.  
Link download: https://www.hikvision.com/en/support/download/sdk/web-development-kit/
  
# Cách 2: Tham khảo, nghiên cứu project chuyển luồng RTSP lên web bằng Golang server của 1 github được nhiều stars:  
Ngôn ngữ: Golang  
Code của github này khá đầy đủ và có giải thích chi tiết, được nhiều người xem và đánh star. Project được thiết kế cho nhiều cách sử dụng nhiều giao thức khác nhau để stream lên web, API cũng được cung cấp đầy đủ.  
Link Github: https://github.com/deepch/RTSPtoWeb
