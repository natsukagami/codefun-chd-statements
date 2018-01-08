Giải đề Sao Hỏa là một công việc đơn giản và giải trí của các thành viên đội tuyển. Anh Duy được thầy Phương giao nhiệm vụ đi photocopy đề ACM Sao Hỏa cho các thành viên trong đội tuyển.

Đề (do được viết bằng tiếng Sao Hỏa) được thể hiện dưới dạng một xâu `S` gồm các kí tự Latin thường. Không photocopy được ở hàng của Trái Đất, anh Duy phải lên tận xưởng in ở Sao Hỏa để thực hiện photocopy. Cách tính chi phí ở đây khá là kì lạ:

 - Gọi `A` là tập hợp tất cả các xâu con không nhất thiết liên tiếp khác rỗng của `S`.

 - Với mỗi xâu `T` thuộc `A`, chi phí để photocopy xâu `T` bị tăng thêm một lượng là `K*cnt[T]` với `cnt[T]` là số lần `T` xuất hiện trong `S`, và `K` là 1 hằng số cho trước.

 - Chi phí để photocopy xâu `S` là tổng chi phí photocopy tất cả các xâu `T`. Do lượng quỹ photocopy của đội tuyển có hạn nên anh Duy quyết định sửa đề để làm giảm giá photocopy.

Khổ nỗi dù đã biết xóa những kí tự nào, nhưng anh Duy không thể xác định những kí tự nào phải thay thế vào. Hãy giúp anh Duy điền vào các chỗ bị xóa, sao cho chi phí photocopy là nhỏ nhất có thể.

## Input

Input gồm nhiều test, mỗi test gồm 1 dòng ghi xâu `S` (`1 ≤ |S| ≤ 10^5`) và số `K` (`1 ≤ K ≤ 10^9`). Input đảm bảo tổng độ dài `S` của các test không quá `10^5`.

## Output

Với mỗi test in ra chi phí nhỏ nhất. Do chi phí vẫn có thể rất lớn nên hãy in nó lấy phần dư khi chia `1000000007`.

## Sample

### Input
```
? 5
a?b 3
```

### Output
```
5
21
```

Giải thích: ở test thứ 2 ta có thể thay `?` bằng `a`.
