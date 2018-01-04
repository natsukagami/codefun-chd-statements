*Nhìn qua thì người ta có thể nghĩ đến game bấm bừa. Nhưng thực sự, MNF đòi khá nhiều hiểu biết. Làm quiz, có khi google không ra. - Thiết Xồng Làm*

Phần 2, cảnh 7, thử thách thứ 7 (thứ 64, tính cả phần đầu). Tổng thời gian chơi: 03:36:01

Mina, cô gái hoạt náo của sòng bài MNF Casino - Casino lớn nhất Las Vegas - yêu cầu Thanh solo 1 ván poker. Muốn tiếp tục, Thanh phải chiến thắng... Giống như các kiểu xì tố khác, trò này được thiết kế để chọn ra “tay chơi” tốt nhất và thắng cuộc.

Trước tiên, mỗi người chơi phải đặt cược một lượng cơ bản. Đầu tiên, mỗi người được phát 1 lá bài “tẩy”, và chỉ người đó mới biết. Sau khi phát xong lá bài tẩy, ở vòng đầu tiên, mỗi người chơi được phát một lá minh bài – là lá bài được đặt trên bàn và ai cũng nhìn thấy. Người có lá minh bài to nhất được quyền tố trước, người này có thể đánh cược, nhường bài, đặt cược thêm, hoặc bỏ cuộc,  cũng có thể showhand (cược toàn bộ). Những người khác có thể đặt cược theo (nếu người đầu tiên showhand thì những người chơi còn lại cũng phải showhand) những người khác có thể từ bỏ. Người từ bỏ không được chơi tiếp. Không được rút lại phỉnh (chip) đã được đặt cuộc…. Sau khi showhand, mỗi người chơi được bổ sung thêm 5 quân bài để xác định thắng bại. Vòng thứ 2, 3, 4 và 5 được thực hiện một cách tương tự. Cuối cùng, so sánh bài cục để xác định người chiến thắng. Ai có bộ lớn nhất sẽ dành chiến thắng.

Bất kể bộ 5 lá bài nào, theo đúng trật tự sau, được xếp từ thấp lên cao, chia theo các kiểu sau:

![alt text](http://s13.postimg.org/wmnehl65z/Screenshot_from_2015_08_19_22_02_25.png)

Sử dụng số và chất để hơn định thắng thua. Số: A>K>Q>J>10>9>8>7>6>5>4>3>2. Lưu ý: Nếu 5 lá bài là 5 4 3 2 A, thì A được coi là lá bài nhỏ nhất,  khi đó vẫn được coi là một chuỗi bài hợp lệ. Chất (từ lớn đến nhỏ): Spades (♠) > hearts (♥) > clubs (♣) > diamonds (♦). Ví dụ 1、Q♦ J♦ 10♦ 9♦ 8♦ > 8♣ 8♥ 8♠ K♥ K♠ 2、9♣ 9♦ 9♠ Q♥ Q♠ > 8♣ 8♦ 8♠ K♥ K♠ 3、A♣ A♦ 8♥ 8♠ Q♠ > A♠ A♥ 7♥ 7♠ K♠ 4、A♠ Q♠ J♥ 9♥ 8♥ > A♦ Q♦ J♠ 9♣ 8♣ 5、4♠ 4♥ A♦ Q♦ 5♦ > 4♣ 4♦ A♠ Q♠ 5♠.

Hãy xác định xem Thanh có bao nhiêu cơ hội thắng, khi đã có 4 quân trong tay. Bạn được biết tay bài của Mina.

## Input

Bài bao gồm nhiều test. Dòng đầu tiên ghi `T` (`T ≤ 39`) là số test. Sau đó là các test. Trong mỗi test :
 - 5 dòng đầu tiên là số lá bài mà Mina có trong tay, mỗi dòng mô tả 1 lá bài dưới dạng 1 xâu ký tự `A of B` với A là số trên lá bài (Nếu giá trị của lá bài lớn hơn 10 thì Ace là Át, King là K, Queen là Q, Jack là J) và B là chất của lá bài (Spades (♠), Hearts (♥), Clubs (♣), Diamonds (♦)).
 - Kế đó là 4 dòng mô tả các lá bài của Thanh dưới dạng 1 xâu ký tự `A of B` với A là số trên lá bài (Nếu giá trị của lá bài lớn hơn 10 thì Ace là Át, King là K, Queen là Q, Jack là J) và B là chất của lá bài (Spades (♠), Hearts (♥), Clubs (♣), Diamonds (♦)).

## Output

Với mỗi test (mỗi test một dòng):
 - Nếu Thanh không có cơ hội thắng, in ra `Case [test thứ mấy]: There is no chance of winning.`
 - Nếu Thanh chỉ có duy nhất một cơ hội để thắng, in ra `Case [test thứ mấy]: There is only 1 chance of winning.`
 - Nếu Thanh có nhiều hơn 1 cơ hội thắng, in ra `Case [test thứ mấy]: There are [số cơ hội thắng] chances of winning.`
 - Nếu Thanh luôn thắng trong mọi trường hợp, in ra `Case [test thứ mấy]: Thanh shall always win!`
## Sample

### Input
```
2
2 of Spades
4 of Clubs
9 of Spades
6 of Hearts
Jack of Diamonds
Queen of Diamonds
7 of Hearts
2 of Hearts
Ace of Hearts
3 of Clubs
3 of Diamonds
King of Hearts
4 of Diamonds
9 of Spades
2 of Diamonds
Jack of Hearts
4 of Spades
10 of Spades
```

### Output
```
Case 1: Thanh shall always win!
Case 2: There are 8 chances of winning.
```
