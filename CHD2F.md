*Chú thích: Lequocminh1999 là tên được sử dụng tại rất nhiều nơi của Minh, chủ yếu được dùng trên mạng để tránh lộ tên thật và năm sinh.*

Lequocminh1999 là người có tài hứng bia. Có lẽ trong dự tuyển, Lequocminh1999 chỉ thua kém Minh 10.5 (hiện tại đã tiến hóa thành Minh 11). Trò chơi hứng bia rất đơn giản, bia rơi xuống và người chơi phải hứng. Nhưng trò mà Lequocminh1999 chơi không phải hứng bia thường, thay vì không hứng được chết luôn mà sẽ tính điểm theo từng chai mà Minh hứng được.

Trò chơi là một mặt phẳng tọa độ Đề-các, Lequocminh1999 xuất phát tại điểm `(0, 0)`. Mỗi chai bia sẽ có 3 chỉ số, `x[i], y[i]` và `t[i]` nghĩa là ở thời điểm `t[i]` chai `i` sẽ xuất hiện tại vị trí `(x[i], y[i])`. Các chai bia di chuyển 1 đơn vị trên mỗi đơn vị thời gian. Lequocminh1999 có thể di chuyển sang trái hoặc sang phải cũng với vận tốc 1 đơn vị trên 1 đơn vị thời gian. Hỏi tối đa Lequocminh1999 có thể nhận bao nhiêu điểm, biết mỗi chai bia được tính là 1 điểm.

## Input

Dòng đầu tiên ghi số n là số quả. (`1 ≤ n ≤ 10^4`). n dòng tiếp theo, mỗi dòng gồm 3 số `x[i], y[i], t[i]` (`−5000 ≤ x[i] ≤ 5000; 1 ≤ y[i] ≤ 10^4; 1 ≤ t[i] ≤ 15000`) là tọa độ và thời điểm xuất hiện của mỗi quả.

## Output

Nếu không thể nhặt quả nào, in `0`.
Nếu có:
 - Dòng đầu tiên ghi số điểm.
 - Dòng thứ hai: ghi chỉ dẫn hướng đi cho Lequocminh1999. Chỉ dẫn là một chuỗi các kí tự ghi hướng đi của Lequocminh1999 từ giây thứ nhất đến khi quả cuối cùng chạm đất. Chuỗi gồm các kí tự `r` (sang phải), `l` (sang trái) hoặc `w` (đứng yên). (Nếu có nhiều cách đi, in bất kì.)

## Sample

### Input
```
3
1 2 3
2 3 4
-2 4 5
```

### Output
```
2
rrrllrwrl
```
