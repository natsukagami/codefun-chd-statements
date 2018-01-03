*Bước nhảy xuống nước luôn là bước khó nhất trong lúc tập bơi.*

Sung sướng lục lọi trong tập link mà mình vừa bỏ tiền ra mua, Thanh chui ngay vào phòng Dự tuyển, mặc các bạn đang chăm chú học hành, mở từng link một, ngắm ngắm soi soi gật gật... Và, trong một giây phút ngỡ ngàng, Thanh đã tìm được tình yêu của đời minh: một webgame tuyệt vời mang tên MNF... Không hề nào núng, Thanh bấm nút Start...   Không nhẹ nhàng tình cảm như Thanh với MNF, ngay từ đầu, MNF đã bắt Thanh phải hoàn thành 1 trò chơi thì mới cho Thanh được chơi tiếp.

Trò chơi trong game là như thế này: Có 2 anh chàng đang chơi bài. 1 bộ bài gồm `N` lá bài có các chỉ số năng lượng khác nhau (`A[i] ≠ A[j] ∀ i ≠ j`). Bộ bài được chia cho 2 người, sao cho không có quân nào thừa ra cả. Sau đó 2 người xếp các lá bài của mình thành 1 xấp.

Luật chơi như sau:

- Mỗi lượt đấu, 2 người lấy ra quân bài đầu tiên trên tập bài của mình và so chỉ số năng lượng. Lá bài của ai có chỉ số năng lượng cao hơn chiến thắng. Trong mỗi lượt, người thắng được phép cướp lấy lá bài của đối phương.

- Giả sử người 1 thắng trong hiệp đấu này, anh ta sẽ lấy quân bài của người 2, đưa nó vào cuối xấp bài của mình, sau đó đưa quân bài của mình vào cuối xấp bài.

- Game bắt Thanh phải xác định xem ai là người chiến thắng. Nếu không có ai có thể chiến thắng thì in ra `-1`.

## Input

Dòng đầu tiên ghi `T` (`T ≤ 39`) là số lượng test. Sau đó là các test. Mỗi bộ test có dạng:

- Dòng đầu tiên ghi `N` (`2 ≤ N ≤ 10`) là số lượng quân bài.
- Dòng thứ 2 ghi 1 số `A` (`A < N`) là số lượng bài của người 1, `A` số sau ghi chỉ số năng lượng của các quân bài của người 1, theo thứ tự nằm đầu xấp bài đến cuối xấp bài.
- Dòng thứ 3 ghi 1 số `B` (`B < N`) là số lượng bài của người 2, `B` số sau ghi chỉ số năng lượng của các quân bài của người 2, theo thứ tự nằm đầu xấp bài đến cuối xấp bài.

(Input đảm bảo `A + B = N`).

## Output

Với mỗi test, in trên một dòng: Nếu có người chiến thắng thì in ra 2 số `R` và `W`: số lượt đấu trước khi trò chơi kết thúc và người chiến thắng (1 cho người 1 và 2 cho người 2). Ngược lại in ra `-1`.

## Sample

### Input
```
2
6
2 
6 5
4
1 2 3 4
3
1
3
2
1 2
```

### Output
```
6 1
-1
```
