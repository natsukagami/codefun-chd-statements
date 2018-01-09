Ma Trận Toàn Phương là một bài toán đơn giản và giải trí. Chi tiết bài toán như sau:

 - Cho một số `N`.
 - Ta phải dựng một bảng `N * N` gồm các số nguyên trong khoảng `[1 ... 10^8]` sao cho tổng **bình phương** các số **mỗi hàng** và **mỗi cột** là một số **chính phương**.
 - 2 hàng bất kì không được giống nhau (2 cột vẫn có thể giống nhau). 
 - 2 hàng `i` và `j` giống nhau **khi và chỉ khi** với mọi `1 ≤ k ≤ N` thì `A[i, k] = A[j, k]`.

Dù rất giỏi toán nhưng anh Duy vẫn phải bó tay trước bài toán đơn giản và giải trí này. Hãy giúp anh Duy dựng ma trận toàn phương thỏa mãn.

## Input

Bài gồm nhiều test. Mỗi test gồm 1 dòng ghi số `N` (`1 ≤ N ≤ 100`). Test đảm bảo không cần in quá `2 * 10^5` số.

## Output

Với mỗi test in ra bảng (`N * N`) thỏa mãn, các số trong 1 dòng viết cách nhau 1 dấu cách. Nếu không có cách dựng in `-1`. Nếu có nhiều cách, in ra 1 phương án bất kì.

## Sample

### Input
```
1
```

### Output
```
1
```
