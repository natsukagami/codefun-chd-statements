*GodIsAGirl là tên bài hát mà Minh rất thích, anh cũng thường dùng nó thay cho tên của mình.*

GodIsAGirl là 1 camper khá khủng của dự tuyển, vậy nên ai cũng muốn được chung team với anh. GodIsAGirl cũng rất hiếu thắng, anh muốn đảm bảo cho chiến thắng của mình trong mỗi ván đấu, nên đội của GodIsAGirl cũng được anh chọn lọc rất cẩn thận.

Có `N` người muốn chơi chung team với GodIsAGirl(`0 < N < 1e5+1`). Mỗi người chơi có 1 chỉ số trình độ gọi là Ability. `Ability[i]` (`|Ability[i]| < 1e9+1`) biểu diễn trình độ bắn CS của người chơi thứ `i` (`0 < i < N+1`). GodIsAGirl muốn chọn càng nhiều người vào đội của mình càng tốt (quân số càng đông thì sự chú ý vào anh sẽ bị giảm, nhờ đó mà có thể ngồi camp ung dung hơn), nhưng người thứ `i` lại chỉ muốn chơi chung với người `i – 1` và người `i + 1`.

Đương nhiên là GodIsAGirl không muốn gây bất hòa trong team của mình(lỡ mà bị spoil ra vị trí camp thì hỏng bét). Vậy nên GodIsAGirl sẽ chỉ lấy những người muốn chơi với nhau vào team của mình. (Lưu ý rằng người 1 chỉ muốn chơi với người 2 và người thứ `N` chỉ muốn chơi với người thứ `N-1`).

GodIsAGirl còn muốn rằng trong đội của mình, người thứ `i` phải có `Ability[i] <= Ability[j]` với `i < j`. (Do anh muốn dễ dàng phân chia vị trí cho các thành viên trong team, để có thể tiện camp nhất có thể. Và GodIsAGirl cũng cực kì dốt thuật toán sort, nên anh không thể tự tay sort lại độ bá đạo của các thành viên trong team). Cho số lượng người chơi, cùng với chỉ số kĩ năng của mỗi người.

Hãy giúp GodIsAGirl, xác định xem số lượng thành viên lớn nhất anh có thể tuyển vào team là bao nhiêu. Và trong các cách tuyển, giúp GodIsAGirl quyết định xem dùng cách nào sẽ có được thành viên kém nhất có chỉ số bé nhất, cách nào sẽ có được thành viên bá đạo nhất có chỉ số hư cấu nhất.

À quên, còn nữa. GodIsAGirl sắp phải đi đấu giải Chung kết Tổng Hợp bộ môn CS 1.6 Cataclysm. Anh sẽ phải đấu với `M` team khác nhằm nuôi ước mơ vô định TH. Mỗi đội có 1 chỉ số sức mạnh của toàn đội, chỉ số này được tính bằng trung bình cộng chỉ số trình độ của các thành viên trong team. Giúp anh kiểm tra xem với mỗi đội phải đấu, anh có cơ hội chiến thắng hay không.

## Input

Bài gồm nhiều bộ test, mỗi bộ test có dạng như sau:

 - Dòng đầu tiên là số `N` - Số người chơi.
 
 - Dòng tiếp theo gồm `N` số, số thứ `i` biểu diễn `Ability[i]`.
 
 - Dòng thứ 3 gồm số `M` (`0 < M < 1e5+1`).
 
 - `M` dòng tiếp theo, mỗi dòng gồm 1 số là chỉ số sức mạnh của đội thứ `i` mà đội của GodIsAGirl sẽ đấu cùng.

## Output

 - Dòng đầu tiên in ra `K` - là số lượng thành viên GodIsAGirl sẽ tuyển.
 - Dòng tiếp theo in ra `K` số, là dãy chỉ số thỏa mãn yêu cầu đầu tiên của GodIsAGirl.
 - Dòng tiếp theo in ra `K` số, là dãy chỉ số thỏa mãn yêu cầu thứ hai của GodIsAGirl.
 - `M` dòng tiếp theo, in ra `GodIsAGirl da best camper` nếu GodIsAGirl có cơ hội thắng, nếu không in ra `GodIsAGirl got rekt`.

## Sample

### Input
```
6
4 5 6 1 2 3
1
4
```

### Output
```
3
1 2 3
4 5 6
GodIsAGirl da best camper
```
