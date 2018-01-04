*The time has come.*

Bị bạn bè phát hiện chơi MNF trong phòng học, Thanh đã quyết định đóng laptop và cố gắng tẩu thoát!

Có thể coi phòng dự tuyển là một lưới ô hình chữ nhật gồm m dãy bàn, mỗi dãy `n` chiếc bàn dài `1.2`m rộng `0.5`m, giữa các bàn là các đường đi. Có thể coi (`0, 0`) là góc dưới trái của phòng, cửa ra ở tọa độ (`m, n`). Thanh đang đứng ở tọa độ (`x[0], y[0]`), đuổi theo Thanh là `K` người “bạn” của Thanh, người thứ `i` đang ở tọa độ (`x[i], y[i]`). Thanh có vận tốc đi là 1 “ô”, tức trong 1 đơn vị thời gian từ ô (`x, y`) chỉ đi đến được (`x, y+1`), (`x+1, y`), (`x, y-1`), (`x-1, y`) ( và tất nhiên là không đâm vào tường). Các bạn có vận tốc gấp đôi Thanh.

Bạn được tường thuật lại đường chạy của Thanh, đồng thời bạn biết rằng tất cả những người bạn của Thanh đều cố gắng chạy với mục tiêu rút ngắn khoảng cách tới Thanh là nhiều nhất có thể, hãy xác định xem Thanh có tẩu thoát thành công không?

## Input

Dòng đầu tiên ghi số `T` (`T ≤ 39`) là số test. Sau đó là các test. Mỗi bộ test có dạng:
 - Dòng đầu tiên ghi các số `m, n, x[0], y[0]` (`1 ≤ m, n ≤ 100; 0 ≤ x[0] ≤ m, 0 ≤ y[0] ≤ n; (x[0], y[0]) ≠ (m, n)`).
 - Dòng thứ hai ghi số `K` (`0 ≤ K ≤ 10`).
 - `K` dòng tiếp theo, mỗi dòng ghi 2 số `x[i]` và `y[i]` (`0 ≤ x[i] ≤ m, 0 ≤ y[i] ≤ n`) là tọa độ của người bạn thứ `i`. Các người bạn không trùng nhau và không trùng vị trí ban đầu của Thanh).
 - Dòng tiếp theo ghi số `L` (`1 ≤ L ≤ 1000`) là số bước đi của Thanh.
 - Dòng tiếp theo là một xâu có L kí tự có dạng 'W', 'A', 'S', 'D' thể hiện hướng đi của Thanh (lần lượt là tiến lên, sang trái, xuống dưới, sang phải).
Đảm bảo Thanh không bao giờ đâm tường và sẽ ra khỏi phòng Tin sau đúng `L` bước (nếu không bị bắt).

## Output

Với mỗi test in trên 1 dòng:
 - `Got rekt at F` nếu Thanh bị bắt, với `F` là thời điểm Thanh bị bắt.
 - Nếu Thanh không bị bắt, in `Escaped Safely!`.

## Sample

### Input
```
3
3 2 2 1
1
3 1
2
WD
2 2 2 1
1
0 0
1
D
4 4 2 4
1
0 0
4
WAWD
```

### Output
```
Got rekt at 1
Escaped Safely!
Got rekt at 4
```
