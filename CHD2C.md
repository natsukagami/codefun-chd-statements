*Chú thích: Moerulestheworld là tên nằm vùng của Minh tại vùng đất Cô-Đờ-Pho-Sự.*

Sau nhiều lần bị Moerulestheworld vào trộm máy và đăng nhiều thứ đồi trụy lên nick Codeforces và Facebook, Bách Trượt Tuyển quyết định thực hiện một cuộc cách mạng về mật khẩu. Các mật khẩu trước khi đổi thường rất đơn giản và dễ nhớ chẳng hạn: 12345678, 69696969, 21101999,... Nên Quốc Minh dễ dàng nhìn và đoán được.

Sau khi đổi các mật khẩu rất phức tạp, chẳng hạn như 12345678abc, 69696969abc, 21101999abc,... Nên Moeruletheworld không tài nào nhớ nổi, thậm chí cả Bách Trượt Tuyển cũng không nhớ nổi. Nên ngoài việc đặt password mới, Bách Trượt Tuyển còn viết lại hint.

Moerulestheworld sau nhiều lần cố gắng cuối cùng cũng lấy trộm được tờ hint. Nhưng khổ nỗi tờ hint được viết toàn bằng Brainf*** nên Moerulestheworld không tài nào đọc nổi. Chẳng hạn: `>>>++[<++[<+++[<+++++++>-]>-]>-]<<<.>>>+++[<+++[<+++++++++++++>-]>-]<<.>>>+++[<+++[<+++++++++++>-]>-]<<--.>>>+++[<+++[<+++++>-]>-]<<.>>>++[<+++[<+++++++++++++++++++>-]>-]<<.>>>+++[<+++++[<+++++++>-]>-]<<.>>>+++[<+++[<+++++++++++++>-]>-]<<-.>` lại có nghĩa là `Tua-rit`. 

Moerulestheworld bất lực nên nhờ bạn giải mã hộ vậy! Brainf*** là ngôn nhữ lập trình gồm 30000 ô nhớ, mỗi ô có giá trị tối đa là 256, gồm 8 câu lệnh.

 - `>`: Dịch con trỏ sang phải.
 - `<`: Dịch con trỏ sang trái.
 - `+`: Tăng giá trị ô nhớ tại con trỏ lên 1.
 - `-`: Giảm giá trị ô nhớ tại con trỏ đi 1.
 - `[`: Nếu giá trị của ô nhớ tại con trỏ bằng 0 thì nhảy đến ngoặc đóng tương ứng và bỏ qua đoạn code ở giữa.
 - `]`: Nếu giá trị của ô nhớ tại con trỏ khác 0 thì nhảy đến ngoặc mở tương ứng và bỏ qua đoạn code ở giữa.
 - `.`: In ra giá trị char của ô nhớ tại con trỏ
 - `,`: Đọc vào giá trị, nhưng ta không cần quan tâm vì tờ hint đảm bảo không có dấu `,`.
Ngoài ra, mọi ký tự khác sẽ bị bỏ qua.

## Input

Bài có nhiều test.

Dòng đầu của mỗi test là một đoạn code Brainf\*\*\*.

Cuối mỗi test là 1 dấu `#`. Đảm bảo dấu `#` chỉ xuất hiện ở cuối chương trình.

## Output

1 string kết quả.

## Sample

### Input
```
++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.
```

### Output
```
Hello World!
```
