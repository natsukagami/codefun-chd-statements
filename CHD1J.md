*Không thông minh dẫn đến tử vong, không có dấu hiệu của bệnh tật.* a.k.a. *Ngu thì chết chứ bệnh tật gì.*

Việc gì đến cũng phải đến! Phúc bất trùng lai, dù Thanh đã rùa được 2 lần nhưng không thể né được lần thứ ba, Thanh đã bị thầy Phương bắt tận mặt. Và để trừng phạt Thanh, thầy bắt Thanh phải dọn rác trong phòng tuyển.

Phòng tuyển có thể được miêu tả bằng 1 ma trận (`N*M`), các hang được đánh số từ 1 -> `N` từ trên xuống, cột được đánh số từ 1 -> `M` từ trái sang. Thanh phải bắt đầu dọn rác từ ô (`1, 1`) (Để đề phòng Thanh chơi xấu dọn không sạch!). Có tất cả là `K` mảnh rác nằm rải rác trong phòng tuyển và Thanh phải nhặt hết cả `K` mảnh đó.

Do rất ân hận về hành động của mình nên Thanh không dám nhìn thầy Phương, vì thế nên Thanh quyết định sẽ không đi ngược lại chiều mình đi. Cụ thể hơn, Thanh sẽ không đi về hướng bắc, và mỗi khi đi từ hàng `i` -> hàng `i+1`, Thanh sẽ quay ngược lại hướng quay của Thanh ở hàng `i`. (Giả sử Thanh đang ở hàng `i` và quay mặt về hướng đông, thì khi đi xuống hàng `i+1` Thanh sẽ quay mặt về hướng tây và phải đi ít nhất 1 bước để quay mặt lại hướng đông).

## Input

Dòng đầu tiên ghi `T` (`T ≤ 39`) là số lượng test. Sau đó là các test. Mỗi bộ test có dạng:
 - Dòng đầu tiên ghi `N, M` (`1 ≤ N, M ≤ 969`) là giới hạn của phòng tuyển.
 - `N` dòng sau, mỗi dòng có `M` kí tự biểu diễn phòng tuyển: kí tự *T* (biểu thị ô có chứa rác) và kí tự *C* (biểu thị ô sạch sẽ).

## Output

Với mỗi test, trên 1 dòng in ra số bước đi ít nhất để Thanh dọn dẹp sạch sẽ phòng tuyển.
(Lưu ý là Thanh sẽ dừng ở mảnh rác cuối cùng).

## Sample

### Input
```
1
3 5
CCTTT
TTTTT
TTTCC
```

### Output
```
12
```
