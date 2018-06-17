*MSI LAPTOP FAQ*

*Q*: Không sử dụng được webcam, ngay cả kiểm tra trong Device Manager cũng không thấy thiết bị ?
*A*: Sử dụng tổ hợp phím Fn + F6 để bật/tắt webcam. Trong trường hợp tổ hợp phím này không có tác dụng, tải phần mềm SCM (System Control Manager) và bật lại. 
Link tải SCM mới nhất (08/05): "Tải tại đây":http://download.msi.com/uti_exe/nb/_ap_MSI%20SCM%20x64%2013.018.03063_13.018.03063_0x8b4df550.zip

***

*Q*: Máy có bàn phím LED RGB, nhưng sau khi mua về chỉ hiện đèn LED màu đỏ ?
*A*: Cài đặt thêm phần mềm Steelseries Engine 3 và/hoặc MSI Dragon Center để chỉnh màu và hiệu ứng LED phím. 
Link tải SSE3 mới nhất: "SteelSeries Engine 3":https://steelseries.com/engine/latest/windows
Link tải Dragon Center mới nhất (8/5): "Dragon Center":http://download.msi.com/uti_exe/nb/DragonCenterv1.2.1802.0501_1.2.1802.0501_0x9f935600.zip

***

*Q*: Không chọn được chế độ hoạt động Sport trong Dragon Center?
*A*: Chế độ Sport chỉ kích hoạt được khi cắm sạc.

***

*Q*: Máy sau khi chuyển sang chế độ Sleep thì khi mở lại màn hình bị sọc và nhiễu, không hiển thị được hình ảnh.
*A*: Lỗi này xảy ra trên các bản Windows 10 mới (1706 và 1709), do xung đột với driver card màn hình. Dùng phần mềm Display Driver Uninstaller để gỡ driver của Intel và nVidia đi, sau đó tải driver mới nhất về cài đặt lại.
Display Driver Uninstaller: "tải tại đây":http://www.guru3d.com/files-details/display-driver-uninstaller-download.html 
Driver Intel: "tải tại đây":https://www.intel.com/content/www/us/en/support/products/80939/graphics-drivers.html   
Driver nVidia: "tải tại đây":https://www.geforce.com/drivers

***
*Q*: Máy cấu hình cao, thừa sức chơi được tốt game nhưng vào game chỉ được 30 (hoặc 60) fps. Mức fps ổn định, gần như không dao động.
*A*: Đây là tính năng tiết kiệm điện của nVidia khi chơi game không cắm sạc. Cắm sạc máy tính vào fps sẽ cao như bình thường.

***
*Q*: Phím Windows và Fn của laptop MSI bị ngược so với bàn phím thông thường, có cách nào đổi lại được không?
*A*: Vào BIOS của máy, chọn mục Advanced -> Fn/Win key swap -> Enable. Sau đó bấm F10 để lưu lại.

***
*Q*: Cách chỉnh độ sáng LED bàn phím
*A*: Dùng tổ hợp phím Fn + nút "-"/"+" bên phần phím số (numpad)

***
*Q*: Game bị sụt fps/cho fps thấp hơn bình thường
*A*: 
Có rất nhiều nguyên nhân có thể dẫn tới tình trạng này. Dưới đây là một số cách khắc phục:
* Tắt tùy chọn V-Sync/Đồng bộ dọc trong phần thiết lập đồ họa của game đi.
* Cắm sạc vào khi chơi game (GPU bị sụt giảm hiệu năng rất nhiều khi sử dụng pin) và kích hoạt chế độ Sport (hoặc Turbo) trong Dragon Center. Có thể bật chế độ quạt Cooler Boost lên nếu cần.
* Máy lâu ngày chưa vệ sinh có thể bị nóng và quá nhiệt. Đem đi vệ sinh lại quạt và trét lại keo tản nhiệt.
* Update driver của card đồ họa nVidia lên bản mới nhất.
* Chạy game bằng card rời (chuột phải vào file .exe chạy game, chọn Run with graphics processor -> High performance processor (nVidia).
* Google xem liệu gần đây game có ra bản patch gì gây sụt giảm hiệu năng không. Một số game crack không tốt cũng cho fps thấp hơn.
* Tắt Windows DVR (tính năng tự động quay video khi chơi game của Microsoft). Gõ DVR vào thanh tìm kiếm của Windows 10, chọn tùy chọn “Control how game bar opens and recognize your game” -> chọn Game DVR bên tay trái -> chuyển thanh trượt ở mục Record in background while I’m playing a game sang Off. Với các bạn dùng Windows 10 phiên bản cũ thì xem hướng dẫn ở đây: "https://www.facebook.com/groups/msigamingvn/permalink/1177604708999336/":https://www.facebook.com/groups/msigamingvn/permalink/1177604708999336/

***
*Q*: Các chế độ hoạt động Power Options, ECO, Comfort, Sport, Turbo có ý nghĩa gì?
*A*: 
* Power Options: máy sẽ chạy theo thiết lập đang sử dụng của Windows.
* ECO: tiết kiệm điện, giảm độ sáng màn hình và tốc độ của linh kiện, bù lại máy mát và thời lượng pin cao.
* Comfort: cân bằng giữa hiệu năng và nhiệt độ/điện năng tiêu thụ.
* Sport: chạy ở mức công suất cao nhất của linh kiện, tiêu tốn điện năng hơn bình thường.
* Turbo: ép xung CPU và/hoặc GPU theo sở thích của người dùng (MSI không chịu trách nhiệm nếu có hỏng hóc do sử dụng tính năng này). Chỉ có trên một số sản phẩm.

***
*Q*: Quạt một bên không quay
*A*: Laptop MSI sử dụng cụm quạt riêng cho CPU và GPU (cụ thể là card rời nVidia). Khi không sử dụng ứng dụng nào cần card đồ họa rời thì quạt tản nhiệt cho GPU sẽ không quay.

***
*Q*: Nút nguồn chuyển màu liên tục giữa xanh và cam
*A*: Đèn nút nguồn chuyển cam khi có ứng dụng sử dụng card đồ họa rời nVidia (có thể là game 3D, hoặc ứng dụng sử dụng nhân CUDA). Màu xanh là khi sử dụng card đồ họa tích hợp của Intel.

***
*Q*: Pin sạc chỉ tới 92-95% rồi ngừng, báo Plugged in, not charging
*A*: Đây là tính năng tăng tuổi thọ pin của laptop MSI. Vòng đời của pin sạc được tính bằng số lần sạc đầy 100% dung lượng pin, việc chỉ sạc tới 92-95% dung lượng này giúp tăng số vòng sạc của pin lên một chút.

***
*Q*: Sau một thời gian sử dụng pin lại báo 100% bình thường
*A*: Có thể pin bị chai đi một chút (pin sạc sẽ tự động chai dần đi khi tiếp xúc nguồn nhiệt, bất kể là có được sử dụng hay không), hoặc mạch pin nhận không đúng dung lượng. Có thể dùng Dragon Center, chạy tính năng Battery Calibration (ở tab Tools and Help) để nhận diện lại dung lượng pin. Lưu ý là quá trình này khá lâu (khoảng 2-3 tiếng), và thường chỉ cần chạy sau mỗi 6 tháng - 1 năm.

***
*Q*: Ổ cứng HDD có tiếng kêu
*A*: Có thể đem tới trung tâm bảo hành để kiểm tra nếu thấy nghi ngờ, hoặc dùng phần mềm để kiểm tra tình trạng ổ cứng (ví dụ như Crystaldisk Info). Tuy nhiên thì HDD trong quá trình sử dụng sẽ có phiến đĩa quay, và để tiết kiệm điện thì khi truy xuất ít dữ liệu sẽ ngừng quay/quay chậm lại. Tới khi cần truy xuất dữ liệu lớn/tốc độ cao thì sẽ quay nhanh trở lại, tạo ra một số tiếng rì rầm nhỏ. Đây là cơ chế tiết kiệm điện của HDD tên là HDD APM (HDD Advance Power Management). Nó sẽ tự dừng vòng quay của đĩa HDD để tiết kiệm điện, tránh các hiện tượng va đập hay rung rắc là đầu từ làm xước đĩa (nếu có).

***
*Q*: Máy mới mua không có ổ quang, làm thế nào để cài đặt Driver/các phần mềm tiện ích của MSI?
*A*: Laptop MSI chính hãng ở VN trên ổ cứng có một phân vùng chứa Driver, các bạn có thể vào đó để cài đặt. Hoặc giải pháp tốt nhất (tải được phiên bản mới nhất) là lên trang chủ của MSI tìm. Có thể Google theo cú pháp tên sản phẩm + msi.com  . Truy cập trang sản phẩm, chọn mục Service để chọn Driver/phần mềm muốn tải.

***
*Q*: Vừa chơi game/chạy phần mềm nặng vừa cắm sạc có sợ nhanh chai pin không
*A*: Các hãng laptop hiện nay đều dùng pin sạc có mạch thế hệ mới, tự động chuyển sang dùng điện từ ổ cắm nếu pin đã đầy và đang cắm sạc. Do đó tuổi thọ của pin không bị ảnh hưởng.

***
*Q*: Máy bị lỗi 100% disk thì khắc phục bằng cách nào?
*A*:
Đây là lỗi rất phổ biến trên Windows 10. Có thể thử một số cách khắc phục sau:
* Lắp thêm SSD cho máy.
* Gõ Notifications vào thanh tìm kiếm của Windows 10, chọn mục Notifications and actions, tắt toàn bộ các mục Notifications đi.
* Dùng tổ hợp phím Windows + R, gõ “services.msc” (không có ngoặc kép vào) rồi Enter. Tìm service có tên là Superfetch, chuột phải vào, chọn Properties -> ở mục Startup Type chọn Disabled. Sau đó restart lại máy.
* Làm tương tự như cách 3, nhưng với service Windows Search.

***
*Q*: Nhiệt độ khi sử dụng như thế nào là bình thường?
*A*: Từ 40-55 độ khi để idle hoặc tải nhẹ. Khi chơi game thì từ 65-85 độ là bình thường, 85-95 là nóng (nhưng vẫn nằm trong ngưỡng giới hạn hoạt động). Lưu ý là nhiệt độ CPU thường sẽ cao hơn GPU (do GPU được ưu tiên nhiều ống đồng dẫn nhiệt hơn).




