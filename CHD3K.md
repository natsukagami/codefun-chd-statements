Như các bạn đã biết, Tetris là trò chơi đơn giản và giải trí, các khối gạch sẽ rơi xuống, bạn đựoc phép di chuyển nhưng không đựoc quay các viên gạch. Biết vị trí các viên gạch rơi, hãy in ra bảng ở trạng thái cuối cùng. Lưu ý các hàng có đủ gạch **không biến mất**.

## Input

Dòng đầu tiên ghi `T` là số test. Sau đó là `T` test. Mỗi test có dạng:

+ Dòng đầu tiên gồm 2 số `N` (`4 ≤ N ≤ 50`) là độ rộng của bàn chơi và `M` (`1 ≤ M ≤ 50`) là số viên gạch rơi xuống.

+ `M` dòng tiếp theo mô tả các viên gạch, được biểu diễn bởi 2 số `X` (`1 ≤ X ≤ 10`) là loại gạch và `Y` (`1 ≤ Y ≤ N + 1 - |X|`) là vị trí cột trái cùng của nơi viên gạch rơi (`|X|` là độ rộng viên gạch).

Bảng viên gạch như sau (không xoay):

![alt text][image]

[image]: http://i.imgur.com/zS2dAxD.jpg "Các mảnh ghép"

## Output

Với mỗi test:

+ Vẽ bảng gồm `N` cột và `K + 1` dòng, trong đó `K` là độ cao của cột cao nhất. Các cột đánh số từ `1` đến `K + 1` từ dưới lên, với kí tự `o` thể hiện 1 ô có gạch, `.` thể hiện ô không có gạch.

+ Dòng tiếp theo ghi theo format `Score: K` với `K` là độ cao của cột cao nhất.
Dòng tiếp theo in 1 dòng trống

## Sample

### Input
```
2
4 1
3 1
4 2
2 1
1 2
```

### Output

```
....
o...
o...
o...
o...
Score: 4

....
.oo.
.oo.
oooo
Score: 3
```
