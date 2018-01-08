Anh Duy, một thành viên kì cựu của Đội tuyển Tin Tổng Hợp, là một người rất yêu thích những dãy số, đặc biệt là các dãy anh em của Fibonacci vì chúng rất đơn giản và giải trí.

Một dãy được gọi là anh em của Fibonacci nếu nó được định nghĩa bởi công thức truy hồi có dạng `F[n] = A * F[n-1] + F[n-2]` với `A` là một số nguyên dương. Đồng thời `F[i] = i` với `i < 2`. Cho một dãy anh em Fibonacci `F'`, hãy tính `F'[n]`. Do số có thể rất lớn nên hãy in 5 chữ số đầu tiên của số

## Input

Input gồm nhiều test, mỗi test bao gồm 2 số `n` (`1 ≤ n ≤ 500`) và `A` (`1 ≤ A < 10`).

Input đảm bảo `F'[n]` có ít nhất 5 chữ số.

## Output

Với mỗi test in trên 1 dòng đáp số.

## Sample

### Input
```
21 1
30 1
```

### Output
```
10946
83204
```
