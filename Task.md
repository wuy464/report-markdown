# Chapter1

##1. Cơ chế hoạt động của internet
    - Internet là một mạng lướt cáp toàn cầu. Khi truy cập vào trang web. máy tính sẽ yêu cầu gửi đường dây này tới 1 máy chủ.

    - Máy chủ là nơi lưu trữ trang web. Khi gửi yêu cầu tới. máy chủ sẽ truy xuất trang web  và gửi dữ liệu chính xác trở lại máy tính. Và việc đó chỉ diễn ra trong vài giây

##2. Giải thích về protocol của HTTP/HTTPS
    # HTTP:

        + Http (HyperText Transfer Protocol) là giao thức truyền tải siêu văn bản được sử dụng trong www dùng để truyền tải dữ liệu giữa Web server đến các trình duyệt Web và ngược lại. Giao thức này sử dụng cổng 80 (port 80) là chủ yếu.

    # HTTPS:

        + Https (HyperText Transfer Protocol Secure) là giao thức Http có sử dụng thêm SSL (Secure Sockets Layer) để mã hóa dữ liệu trong lúc truyền tải dữ liệu nhầm gia tăng thêm tính an toàn cho việc truyền dữ liệu giữa Web server và trình duyệt Web. Giao thức Https thì sử dụng cổng 433 để truyền dữ liệu.

    # Sự khác nhau giữa HTTP và HTTPS 

        + Hiện nay thì việc sử dụng giao thức Https chủ yếu được dùng cho các trang web có giao dịch trực tuyến sử dụng thẻ thanh toán đơn hàng. Nhằm đảm bảo an toàn cho giao dịch, tránh những rủi ro bị lấy mất thông tin thể trong quá trình thanh toán.

        + Ngoài ra web sử dụng giao thức Https là 1 tín hiệu để Google xếp hạng từ khóa. Việc này khiến rất nhiều trang Web chuyển qua dùng giao thức Https để Seo được tốt hơn.

        + Tuy nhiên việc dùng Https sẽ khiến cho việc truy cập của Website chậm hơn so với Http. Và nhiều trang không có giao dịch trực tuyến hay truyền tải thông tin dữ liệu quan trọng thì thông tin có bị lộ hay không cũng không quá quan trọng.

        + Nhưng hiện nay Chrome sắp có cảnh báo với những website còn sử dụng Http, và ưu tiên cho các trang web sử dụng Https.

        + Để có thể sử dụng giao thức Https thì Website của bạn phải có chứng chỉ SSL. Còn không thì sẽ gặp tình trạng hiển thị là kết nối không bảo mật trên trình duyệt Chrome.

        + Ngoài ra web sử dụng giao thức Https là 1 tín hiệu để Google xếp hạng từ khóa. Việc này khiến rất nhiều trang Web chuyển qua dùng giao thức Https để Seo được tốt hơn.

##3. Cơ chế hoạt động của browser và sự khác nhau giữa các browser

    # Cơ chế hoạt động của browser

        + User Interface: Là tầng cao nhất, nơi tương tác chủ yếu giữa người dùng và trình duyệt, nó bao gồm các thành phần quen thuộc như thanh Address, các nút Reload – Back – Home, Biểu tượng Bookmarks… Những thành phần này không ảnh hưởng đến việc hiển thị của trang mà chủ yếu giúp cho việc tương tác thuận tiện hơn

        + Browser Engine: Đây là tầng nằm giữa và là cầu nối giữa User Interface & Rendering Engine. Tầng này sẽ cung cấp các hành động (actions) để giao tiếp và xử lý dữ liệu từ tầng Rendering Engine lên tầng User Interface và ngược lại, chuyển đổi những hành động người dùng thao tác trên tầng Interface xuống Rendering Engine. Ví dụ khi bạn nhấp vào nút Reload trang ở User Interface thì sẽ có một “tên” mang thông điệp đó xuống bên dưới để xử lý và thực hiện load lại trang, “tên” đó đang đóng vai trò như Browser Engine. Vậy để dễ phân biệt bạn có thể xem Reload icon là User Interface, còn Reload page action là Browser Engine lo.

        + Rendering Engine (Layout engine): Đây là một tầng quan trọng, nó đóng vai trò xử lý (rendering) các thẻ – câu lệnh HTML, CSS, XML, JS để hình thành giao diện (layout) hiển thị lên tầng User Interface, những gì chúng ta sẽ nhìn thấy và tương tác. Nên cũng có thể hiểu nếu tầng này xử lý không hiệu quả thì phía trên người dùng cũng không hiển thị tốt.

        + JavaScript interpreter: xử lý và thực thi các đoạn mã JavaScript để hiển thị lên trang web. Đây cũng là một thành phần rất quan trọng ảnh hưởng đến việc hiển thị trang web, do các trang web hiện nay thường cần xử lý và sử dụng khá nhiều mã JavaScript.

        + Data persistence: Có chức năng lưu trữ thông tin và dữ liệu trên máy local. Những dữ liệu này có thể là Cache, Cookies, localStorage, IndexedDB, WebSQL and FileSystem tùy vào từng hệ thống web.

    # Sự khác nhau giữa các browser

        + Google: 

            - Là trình duyệt được sử dụng nhiều nhất hiện nay. Nó được yêu thích vở khả năng tương thích, nhanh, nhẹ, khả năng tìm kiếm chính xác.

        + Coccoc: 

            - Là trình duyệt sinh ra để dành cho người Việt. Chưa thực sự tốt như google. Thế nhưng chúng có những ưu điểm vượt trội như hỗ trợ tải xuống, chỉnh sửa chính tả.

        + IE: 

            - Là trình duyệt do Microsoft phát triển. Đây là trình duyệt được tích hợp sẵn trên windows. ĐƯợc biết đến với sự khô cứng. Thế nhưng nó cho được là có khả năng tương thích và bảo mật cao. Đồng thời cho phép người dùng lọc và cảnh báo xấu.

        + Opera:

            - Là một trình duyệt khá phổ biến trên các thiết bị di động. Chúng được sử dụng nhiều ở nước ngoài và ít hơn ở việt Nam. Chúng được biết đến nhờ sự ổn định và giao diện đẹp

        + Firefox:

            - Là trình duyệt phát triển bởi TQ, Nó được sử dụng nhiều cho các máy tính và thiết bị cấu hình yếu. Nhờ khả năng chống ngốn ram, khả năng tuỳ biến giao diện và thân thiện với người dùng.

##4. Cơ chế hoạt động của DNS và domain

    # Cách thực hoạt động của DNS: 

        + Khi bạn muốn truy cập vào trang web có địa chỉ là abc.vn

        + Người dùng gửi yêu cầu tìm kiếm địa chỉ IP ứng với tên miền abc.vn tới Name Server cục bộ Máy chủ domain cục bộ sẽ tìm kiếm trong kho dữ liệu xem có cơ sở dữ liệu chuyển đổi từ tên miền sang địa chỉ IP của tên miền mà người dùng yêu cầu hay không.

        + Nếu “có” thì nó sẽ gửi trả lại địa chỉ IP của máy có tên miền đó.

        + Nếu “không có” nó sẽ hỏi lên các máy chủ tên miền ở mức cao nhất (ROOT). Máy chủ tên miền mức ROOT này sẽ chỉ cho máy chủ tên miền cục bộ địa chỉ mà nó quản lý có đuôi “.vn”.

        + Máy chủ tên miền cục bộ gửi yêu cầu đến máy chủ quản lý tên miền Việt Nam “.vn” tìm tên miền abc.vn.

        + Máy chủ tên miền cục bộ sẽ hỏi máy chủ quản lý tên miền “.vn” địa chỉ IP của tên miền abc.vn” và gửi trả lại cho máy chủ tên miền cục bộ.

        + Máy chủ tên miền cục bộ chuyển thông tin đến máy của người dùng.

        + Người dùng sử dụng địa chỉ IP này kết nối đến server chứa website có địa chỉ abc.vn”.
    
    # Cách thức hoạt động của Domain

        + Khi bạn nhập một domain name vào thanh URL của trình duyệt web, lúc này nó sẽ gửi yêu cầu truy cập đến một mạng lưới máy chủ toàn cầu hình thành nên hệ thống domain (DNS). Sau đó các máy chủ toàn cầu này sẽ tìm kiếm các máy chủ có tên được liên kết với domain và chuyển tiếp yêu cầu đến các máy chủ tên đó.

##5. Giải thích về hosting server

    # Hosting là gì: 

        + Hosting đây được hiểu là dịch vụ cho thuê không gian trên máy chủ (Server) để lưu trữ, xử lý dữ liệu Website trên Internet. Server của nhà cung cấp dịch vụ Hosting sẽ có IP và đường truyền riêng với cấu hình rất cao nên hoạt động luôn ổn định và bảo mật tốt.

    # Cách hoạt động của hosting

        + Web Hosting sẽ hoạt động trên nguyên lý cho phép lưu trữ các tập tin dữ liệu từ Website cá nhân, tổ chức lên hệ thống mạng máy tính có hiệu suất vận hành cao (high-powered computers) được kết nối tới hệ thống internet toàn cầu. Khi mọi người gõ vào địa chỉ Website, hệ thống internet toàn cầu kết nối tới máy chủ Web chứa dữ liệu Website và chuyển thông tin Website trở lại máy tính cá nhân. Nhờ cơ chế như vậy, mọi người có thể trải nghiệm Website truy cập theo như ý muốn.

    # Tính năng của hosting:

        + Tên miền (Domain): Tên miền sẽ giúp Website dễ dàng hiển thị trên Internet hơn là thông qua giao thức mã hóa IP truyền thống.

        + Dung lượng lưu trữ: Thông số này đại diện cho khả năng lưu trữ dữ liệu trên Website. Khi dung lượng lưu trữ đã dùng hết, Website sẽ vận hành rất chậm.

        + Băng thông: Băng thông mô tả lượng dữ liệu thông qua Website được phép truyền tải trong một thời gian nhất định.

        + Bảo mật và sao lưu : Cơ chế bảo mật và sao lưu giúp dữ liệu được bảo vệ an toàn và phục hồi nhanh chóng khi có trường hợp xấu xảy ra.

        + Các công cụ lập trình phần mềm trên Internet và các công cụ viết sẵn để phục vụ các hoạt động giao dịch trên Website như gửi mail, upload qua trang Web.

        + Các dịch vụ email như POP3 email, email forwarding,...
