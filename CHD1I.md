*Khoảng lặng trước cơn bão rất có thể sẽ là khoảng bình yên cuối cùng.*

Một lần nữa, sự rùa lên đến huyền thoại đã cứu sống Thanh. Tuy vậy, Thanh vẫn chưa chừa, phóng sang phòng đội tuyển, tiếp tục cày Ocean Cruise... Đen cho Thanh, một thanh niên nào đó đã nhìn thấy và chạy sang mách với thầy Phương. Với bản tính là một người cực kì ghét những văn hóa phẩm đồi trụy, vì vậy thầy liền phóng sang phòng tin đội tuyển để càn quét thanh ngăn chặn văn hóa phẩm này lan sang tất cả các thành viên trong dự tuyển. Rất không may, vì quá nóng giận nên thầy cũng càn quét luôn tất cả các thành viên ở gần đó trên đường đi.

Giả sử phóng tin của dự truyển là một đồ thị hàm số, chúng ta sẽ chỉ xét đến vùng dương của đồ thị ( vùng phải trên của đồ thị). Thanh đang ngồi ở vị trí (`X,Y`) xem MNF, thầy Phương ở vị trí (`0,0`) và đang lao đến vị trí của Thanh mới vận tốc không đổi là `(Y+M)/h`( mỗi giờ tăng độ cao của `y` lên `m` đơn vị độ dài ) và bán kính càn quét của thầy Phương là `R`. Trong dự tuyển có `N` người, người thứ `i` đang ngồi ở vị trí (`x[i],y[i]`) nếu ai nằm trong bán kính càn quét của thầy Phương cũng sẽ bị càn quét theo. Thầy Phương sẽ có chỉ số tức giận là `T` và giảm dần 1 đơn vị trong mỗi giờ. Thanh niên mách lẻo rất muốn biết rằng thấy có đủ nóng giận để có thể càn quét Thanh không nhưng lại rất ngu học, hãy giúp thanh niên này!

## Input

Dòng đầu tiên nhập vào số test `Tc` (`0 < Tc ≤ 100`). Sau đó là các test. Trong mỗi test:
 - Dòng đầu nhập vào 6 số (R,M,N,X,Y) và `T`.(`0 < R ≤ 1000; 0 < M ≤ 5000; 0 < N ≤ 1000; 0 ≤ X,Y ≤ 5000; 0 < T ≤ 500`).
 - `N` dòng tiếp theo, dòng thứ `i` nhập vào 2 số `x[i]` và `y[i]`. (`0 ≤ x[i],y[i] ≤ 5000`).

## Output

In ra `YES` nếu thầy Phương có thể càn quét được Thanh, sau đó in ra số lượng và vị trí tất cả những người bị thấy Phương càn quét từ vị trí ban đầu cho đến khi càn quét được Thanh từ bé đến lớn. In ra `NO` nếu thấy Phương không thể càn quét được Thanh.

## Sample

### Input
```
1 
3 1 5 6 6 7
2 3
5 10
7 4
2 2
6 1
```

### Output
```
YES 3 2 2 2 3 6 1
```
