# JS_exercise
Bài tập 1: Viết bảng cửu chương 1->10, chỉ được phép dùng javascript, sử dụng document.write() để in bảng cửu chương ra màn hình
 
![image](https://user-images.githubusercontent.com/93200025/188941014-685c1f42-c23a-4885-9937-04c4af619c97.png)

Bài 2. Vẽ đồ thị bằng cách nhập liệu từ Form, số lượng đồ thị có thể tùy biến dựa vào array có sẵn: Ví dụ:
  	var myArray = new Array();
  	myArray[0] = "Anh";
  	myArray[1] = "Phap";
myArray[2] = "Duc";
myArray[3] = "Nga";
myArray[4] = "Nhat";
Đồ thị được vẽ vào trong 1 thẻ DIV
![image](https://user-images.githubusercontent.com/93200025/188941036-38e31604-347f-426b-b316-14a1d91bb827.png)

 
 
Bài 3: Làm đồng hồ thể thao bấm giây, có 3 nút:
Bắt đầu: bắt đầu đếm,
Dừng lại : tạm dừng đồng hồ,
Reset: quay về 00:00.0
![image](https://user-images.githubusercontent.com/93200025/188941058-b6c71d52-c1c8-4d77-9e1b-8ea09e9b314e.png)

 
Quy tắc đồng hồ, cứ 100ms thì số cuối tăng thêm 1 đơn vị
Cứ số cuối đến 10 thì số cuối sẽ về 0 và số giây sẽ tăng thêm 1 đơn vị
Cứ 60s thì giây quay về 00 và số phút tăng lên 1
 
Gợi ý dùng hàm setInterval(), clearInterval() kết hợp các toán tử %, / và các hàm toán học như Math.round làm tròn, Math.floor lấy phần nguyên
 
 
 
Bài 4: In ra tam giác theo quy luật hình dưới đây, ô text nhập giá trị nguyên dương bất kỳ.
Gợi ý: tam giác được show trên thẻ div
 ![image](https://user-images.githubusercontent.com/93200025/188941090-18e6f372-cb1a-4ab6-bfe1-ec6d51f734fb.png)

 

Bài 5: Tương tự câu 4 vẽ tam giác theo quy luật sau
![image](https://user-images.githubusercontent.com/93200025/188941111-51b42dbb-0d60-4516-acfd-e1c554784648.png)


Bài 6: Tạo chương trình máy tính điện tử như sau:
![image](https://user-images.githubusercontent.com/93200025/188941133-bab8f16c-d785-4540-aeb0-3f7986a49b01.png)


Bài 7: Tạo chương trình mô tả lịch để bàn như sau:
![image](https://user-images.githubusercontent.com/93200025/188941174-67e6ed1d-4bba-44d8-bf8e-02f3f86fd191.png)

Có 2 nút Prev và Next để chuyển giữa các tháng

Bài 8 (cho vị trí Frontend): Sử dụng ReactJS tạo game đánh cờ caro OFFLINE 2 người chơi đơn giản có các tính năng sau:
Nhập tên 2 người chơi tương ứng lần lượt với ô X và O.
Sau khi nhập tên người dùng thứ 2 xong thì bất đầu đếm thời gian chơi.
Đồng hồ đếm thời gian chơi nhảy theo giây, khi có 1 người chơi thắng thì đồng hồ tắt.
Nếu mỗi bên đạt được năm ô cờ chung hàng (có thể là hàng ngang, hàng dọc, hàng chéo) thì thắng. Lưu ý, nếu đạt được năm ô cùng hàng mà bị chặn trước hai đầu là chưa thắng. Chỉ có năm ô cùng hàng mới thắng, 6,..n ô thì không thắng.
Sau 20p chơi nếu chưa xác định được người thắng thì báo kết quả hoà.
Độ rộng của bàn cờ là không xác định (giá trị ban đầu là 30x30), tự động co giãn kích thước theo số ô mà người dùng chơi.
Khi có người chơi thắng thì thông báo người thắng, thời gian chơi là bao lâu.
