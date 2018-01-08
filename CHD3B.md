Cờ Bật là một trò chơi đơn giản và giải trí. Trò chơi như sau:

- Một ván cờ bật được chơi trên 1 bảng `1 * N`, đánh số `1` đến `N` từ trái qua phải. Ngoài ra, trên mỗi ô được ghi 1 số từ `1` đến `N` theo thứ tự bất kì, mỗi số được ghi đúng 1 lần.

- Người chơi xuất phát từ ô số `1`. Mỗi bước, người chơi sẽ đi từ ô đang đứng đến ô có đánh số là số được ghi trên ô đang đứng.

- Người chơi thứ nhất sẽ thực hiện đặt cược: sau nước đi thứ `X`, ta sẽ ở ô đánh số `Y`. Người chơi thứ hai sẽ thực hiện ghi số các ô. Sau đó, nếu sau `X` nước đi người chơi thứ nhất ở đúng ô `Y` thì sẽ giành phần thắng. Anh Duy là người rất thông minh nên biết chắc người chơi thứ nhất sẽ có chiến thuật dành chiến thắng.

Dù vậy, anh không biết là giá trị `X` nhỏ nhất để có chiến thuật thắng là gì. Hãy giúp anh Duy tìm giá trị đó. Cho `N`, hãy tìm giá trị `X` nhỏ nhất sao cho luôn có thể xác định giá trị `Y` bất kể cách đánh số.

## Input

Input gồm nhiều test, mỗi test gồm 1 số `N` (`1 ≤ N ≤ 30`) ghi trên một dòng.

## Output

Với mỗi test, in trên 1 dòng 1 số duy nhất là giá trị cần tìm.

## Sample

### Input
```
1
2
```

### Output
```
1
2
```
