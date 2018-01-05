Lại nói về 0069 và 0071, sau khi không giải được câu đố dành cho đặc vụ, họ đành lang thang ngoài cổng. Bỗng nhiên, 69 phát hiện ra một điếu thuốc lá màu cháo lòng. Cảm thấy bất thường, anh rạch thử ra thì thấy phía trong điếu thuốc có hai dòng chữ. Bằng óc suy luận tuyệt vời của mình, anh nhận ra ngay đây chính là nhiệm vụ mà Boss giao cho, còn câu đố chỉ là câu bait vớ vẩn.

Tuy nhiên, vì trước đó trót rạch điếu thuốc ra nên một số chữ không thể đọc được. Thông tin duy nhất 69 còn nhớ được là lúc đầu hai dòng chữ chỉ gồm các kí tự Latin thường, giống hệt nhau và có độ dài `N`. 0069 muốn biết có bao nhiêu dòng chữ có thể là mật lệnh.

Nói cách khác, có bao nhiêu xâu độ dài `N` nhận cả 2 xâu trên điếu thuốc là xâu con (không nhất thiết liên tiếp). Vì 0069 và 0071 chỉ có thể thử `10^9+6` xâu trước khi điếu thuốc phát nổ (?), nên hãy in ra kết quả modulo `10^9+7`.

## Input
Dòng đầu tiên là `T`, số test (`T ≤ 10`) Mỗi test bao gồm 3 dòng ghi số `N` (`1 ≤ N ≤ 1000`) và hai xâu `S` và `T` (`1 ≤ |S|, |T| ≤ 100`).

## Output
Với mỗi test in trên một dòng kết quả của bài toán, modulo `10^9+7`.

## Sample
### Input
```
2
2
a b
1
a b
```
### Output
```
2 0
```
