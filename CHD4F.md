Sau khi trả một ít tiền cho Đát-vê-đà, Thanh Hải Vương đã mượn được Đét-sì-ta và quyết định dùng nó để tiêu diệt trái đất. 0069 và 0071 biết được tin này liền nhờ Dương Sì-ke-oắc-cờ, một phi công xuất chúng đến từ Vành Đai Ngòai đến tiêu diệt Đét-sì-ta. Đét-sì-ta có một lỗ thông hơi dẫn thẳng đến lò phản ứng, chỉ cần một quả ngư lôi proton, thả một cách chính xác, có thể làm nổ được Đét-sì-ta.

Dương Sì-ke-oắc-cờ đã tiếp cận được Đét-sì-ta và quyết định khai hỏa. Mỗi quả ngư lôi có 2 thông số `A` và `B`, mỗi giây `A` và `B` thay đổi theo quy tắc:

```c++
if (A < b) A = 2 * A, B = B - A;
else B = 2 * B, A = A - B;
```

Dương Sì-ke-oắc-cờ phải tính toán `A` và `B` ở thời điểm `T` để dẫn đường cho ngư lôi bằng Thần lực đi thẳng vào lò phản ứng của Đét-sì-ta và tiêu diệt nó.

## Input

Bài có nhiều test, mỗi test gồm 3 số `A`, `B` và `T` (`0 ≤ A, B ≤ 2 * 10 ^ 9`; `0 ≤ T ≤ 10^18`).

## Output

Với mỗi test in trên 1 dòng 2 số `A` và `B` sau `T` lượt.

## Sample

### Input
```
4 7 2
```

### Output
```
5 6
```
