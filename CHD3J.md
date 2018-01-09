Hôm nay vì cho Đạt chép code nên Duy được Đạt thưởng cho chơi Tetris. Nhưng trước khi chơi Tetris, Kiều Quốc Đạt yêu cầu Duy phải giải được một bài toán. Bài toán rất đơn giản và giải trí nhưng Duy đang phê quá, giải không nổi nên nhờ bạn giải hộ vậy.

Đề bài toán như sau: Cho 6 số `a[1], a[2], a[3], a[4], a[5], a[6]`, tính: `sqrt((2A^2B^2 + 2B^2C^2 + 2A^2C^2 - A^4 - B^4 - C^4)/16)`. Với:

 - `A = sqrt((a[1])^2 + (a[2])^2 + (a[3])^2 + (a[4])^2 - 2(a[1])*(a[3]) - 2(a[2])*(a[4]))`
 - `B = sqrt((a[1])^2 + (a[2])^2 + (a[5])^2 + (a[6])^2 - 2(a[1])*(a[5]) - 2(a[2])*(a[6]))`
 - `C = sqrt((a[3])^2 + (a[4])^2 + (a[5])^2 + (a[6])^2 - 2(a[3])*(a[5]) - 2(a[4])*(a[6]))`

## Input

Input gồm nhiều test, mỗi test gồm 1 dòng ghi 6 số `a[1], a[2], a[3], a[4], a[5], a[6]`, với `a[1], a[2], a[3], a[4], a[5], a[6]` là các số thực dương, nhỏ hơn `100` và có tối đa 3 số sau dấu phẩy.

## Output

Với mỗi test in ra đáp án, in chính xác 15 chữ số sau dấu phẩy thập phân.

## Sample

### Input
```
1.000 2.000 1.000 2.000 1.000 2.000
```

### Output
```
0.000000000000000
```
