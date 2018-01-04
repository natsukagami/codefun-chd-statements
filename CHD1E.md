*MNF là một game dạng visual novel - bạn gặp các ngã ba lựa chọn. Lựa chọn đúng, bạn lên tiên cảnh. Lựa chọn sai, game restarts.*

Phần 1, cảnh 9, thử thách thứ 16. Tổng thời gian chơi: 01:52:18.

Thành phố Los Angeles, bối cảnh của MNF, được xác định là một thành phố có xấp xỉ một tỉ người dân. Mỗi người được phân 1 chỉ số trong khoảng `1` đến `10^9`, trong đó số chẵn chỉ phái nữ, số lẻ chỉ phái nam. Luật pháp trong game không chặt chẽ cho lắm, nên chuyện trùng chỉ số cũng là chuyện bình thường.

Thanh và Cindy (objective hiện tại) sẽ chơi một trò chơi. Đầu tiên, Cindy sẽ chọn ra từ trước `N` trong số 1 tỉ chỉ số, và đưa vào khách sạn. Sau đó, `K` bé "gấu" ("hàng" giả) sẽ được khách sạn chọn ngẫu nhiên, mỗi bé "gấu" cũng sẽ nhận một chỉ số ngẫu nhiên với giới tính xác định như trên. Xác suất các chỉ số là như nhau. Thanh và Cindy sẽ lần lượt chơi.

Trong lượt chơi của mình, người chơi sẽ chọn 2 nhân vật nào đó (có thể là gấu, là người?) (ta lần lượt gọi chỉ số 2 người là `x` và `y`) và đưa họ vào phòng riêng... "Dù gái, hay trai, hay gấu, chỉ hai là đủ", 2 người này sẽ làm ra một bé "gấu" mới, mang chỉ số `|x - y|`. Sau đó, 2 người đưa nhau về nhà riêng... Thanh nhường Cindy đi trước. Khi nào chỉ còn lại một nhân vật, tùy theo giới tính mà Thanh sẽ thắng hay thua. Nếu nhân vật còn lại là nam, thì Cindy sẽ theo chàng đó và Thanh sẽ bị cắm sừng. Nếu nhân vật còn lại là nữ, thì Cindy sẽ nổi lòng ghen và Thanh sẽ bị đá. Biết rằng Cindy là máy tối ưu (theo trai), Thanh cũng không phải dạng vừa (nên quyết bị đá), hỏi xác suất Thanh bị đá là bao nhiêu?

## Input

Dòng đầu: `T` - số test. Sau đó là `T` test. Với mỗi test:

- Dòng đầu: 2 số `N, K` cách nhau một dấu cách (`0 ≤ N, K ≤ 10^5, N > 0`).
- Dòng 2: `N` số trong khoảng `1` đến `10^9` cách nhau một dấu cách.

(Input đảm bảo `A + B = N`).

## Output

Với mỗi test, in ra xác suất Thanh bị đá, chính xác đến 6 chữ số thập phân.

## Sample

### Input
```
1
1 1
1
```

### Output
```
0.500000
```
