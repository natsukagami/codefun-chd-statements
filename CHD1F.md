*Không gì quan trọng bằng những rung động của bản thân khi ta sảng khoái. Đó là điều làm cho cuộc sống tươi đẹp hơn.*

Một phần không thể thiếu khi Thanh chơi MNF chính là cái đầu. Chính cái đầu lắc lư, gật gật, giật giật, tung tăng theo những nhịp điệu điên rồ của những đôi trai gái trong game… Tuy vậy, không hẳn là đầu lắc không có nhịp! Coi vận tốc dao động gật ban đầu (lần 1) là `1`. Mỗi lần gật, vận tốc dao động lại tăng thêm. Cụ thể, ở lần gật thứ `i`, vận tốc dao động gật đầu (cũng như của cặp trai gái trong game) lại tăng thêm `1/(1 + 2 + … + i)` vận tốc ban đầu. Hãy xác định vận tốc gật gật của Thanh sau `n` lần gật!

## Input

Dòng đầu tiên ghi số `T` (`T ≤ 39`) là số test. Mỗi test gồm 1 dòng duy nhất ghi số nguyên `n` (`0 < n ≤ 2*10^6`) chỉ số lần gật.

## Output

Với mỗi test, hãy in trên 1 dòng vận tốc gật gật của Thanh sau `n` lần gật, theo tỉ lệ với vận tốc ban đầu. Hãy in tử số và mẫu số tối giản của tỉ lệ đó.

## Sample

### Input
```
2
1
3
```

### Output
```
1 1
3 2
```
