*Phúc bất trùng lai - Họa vô đơn chí*

Sau khi nhặt rác xong, Thanh còn bị thầy phạt phải đi đổ rác.

Nhà C3 có 1 phòng đổ rác, nhưng ở rất xa phòng dự tuyển. Muốn đi đến phải đi qua 1 căn phong nữa. Ta tạm gọi phòng dự tuyển là phòng 1, phòng trung gian là phòng 2, phòng chứa rác là phòng 3. Thanh đang có `N` túi rác chất ở phòng 1, và Thanh muốn chuyển n túi rác này sang phòng 3. Nhưng Thanh lại muốn tiết kiệm năng lượng nhất có thể. Mỗi túi rác có 1 chỉ số cho biết năng lượng Thanh cần sử dụng để chuyển túi rác đó từ phòng này sang phòng khác. Thanh nghĩ ra 1 chiến thuật tham lam như sau:

Thanh chỉ chuyển túi rác thứ k từ phòng A -> phòng B khi và chỉ khi túi rác thứ k tốn nhiều năng lượng nhất so với các túi rác hiện tại ở phòng A và phòng B.

Ví dụ: giả sử Thanh đang đứng ở phòng 1, có 2 túi rác có chỉ số năng lượng là 2 và 3. Nếu Thanh muốn chuyển túi rác có năng lượng bằng 2 sang phòng 2, thì Thanh phải chuyển túi rác có năng lượng bằng 3 sang phòng 2 -> phòng 3, sau đó mới chuyển được túi rác có năng lượng bằng 2 sang phòng 2.

Xác định xem với chiến thuật như thế thì Thanh cần ít nhất bao nhiêu lần chuyển để chuyển toàn bộ túi rác từ phòng 1 sang phòng 3. (Lưu ý đường đi giữa phòng A, B là 2 chiều, tức là Thanh có thể chuyển túi rác thứ k từ phòng A -> B và ngược lại).

## Input

Dòng đầu tiên ghi `T` (`T ≤ 39`) là số lượng test. Mỗi bộ test có dạng:
 - Dòng đầu tiên ghi `N` (`N ≤ 1000`) là số lượng túi rác.
 - Dòng tiếp theo ghi `N` số `X` (`X ≤ 10^6`) là chỉ số năng lượng của mỗi túi rác. (`A[i] ≠ A[j]` với mọi `i ≠ j` (`A[k]` là chỉ số năng lượng của túi thứ `k`)).

## Output

Với mỗi test in ra số lần di chuyển giữa 2 phòng bất kì ít nhất nếu đi theo chiến thuật của Thanh lấy phần dư cho 1000000007.

## Sample

### Input
```
2
1
500
2
696 969
```

### Output
```
2 8
```
