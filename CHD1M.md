*Liệu một tương lai vĩnh viễn có MNF là một tương lai có hậu?*

Việc chơi MNF cần phải cực kỳ bí mật và Thanh biết rõ điều đó. Thanh cũng biết rằng đám bạn bè xung quanh cũng sẽ hay mò lục lịch sử hay các file văn bản, vid,… trong máy tính của Thanh để có thể đem bằng chứng ra đưa thầy Phương.

Vì vậy mà Thanh cần có một cái gì đó để đảm bảo điều này không thể xảy ra, nhưng nếu Thanh xóa dữ liệu thì dĩ nhiên, công cày cuốc của Thanh cũng sẽ tan thành mây khói… Sao nhỉ?? Đúng rồi!! Đơn giản là khóa máy tính lại bằng mật khẩu để hội bạn và thầy Phương không thể mò vào máy của Thanh. Nhưng thật đau lòng, máy của trường cũng đã bị khóa bằng mật khẩu riêng. Nhưng nhờ trộm được một dãy mã khóa từ ngăn bàn thầy Phương, Thanh có thể dùng nó để xóa mã và tạo mã mới cho mình. Hãy xác định tuổi của Thanh… à nhầm, mật khẩu của máy nhà trường.

Cách hoạt động của mã khóa: Mã khóa là một dãy gồm 26 ký tự biểu trưng cho 26 chữ cái Latinh từ ‘a’ đến ‘z’. Từ mật khẩu ban đầu gồm toàn các chữ cái Latinh từ `a` đến `z`, tạo ra 1 mật khẩu mới bằng cách thay thế các chữ cái ở mật khẩu ban đầu thành ký tự tương ứng trên mã khóa. Nếu mã khóa có ký tự ‘\*’ ở ô nào thì mã khóa của chữ cái đó thầy Phương đã nhớ sẵn và sẽ không cần phải ghi lại, vì vậy nếu cần dùng đến ký tự ô đó thì Thanh sẽ không thể phá khóa được.

## Input

Dòng đầu tiên ghi số `T` (`T ≤ 40`) là số test. `2T` dòng tiếp theo, mỗi dòng là một dãy ký tự. Dòng thứ `2i` là mã khóa của mật khẩu, dòng thứ `2i + 1` là mật khẩu ban đầu mà thầy Phương định đặt.

## Output

Với mỗi test, in ra trên 1 dòng là mã khóa của thầy Phương nếu Thanh có thể mở được khóa, còn không thì in ra `EXPOSED`.

## Sample

### Input
```
2
abcde@ghijklmnopqrstuvwxyz
thanhlikemnf
```

### Output
```
thanhlikemn@
EXPOSED
```
