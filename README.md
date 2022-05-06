# Dart
- runTimeType: kiểm tra kiểu dữ liệu của biến
- 
1 Variable:
- dynamic: nhận mọi kiểu dữ liệu và có thể không cần gán giá trị liền (value default = null).
- để khai báo biến mà không cần gán giá trị liền thì ta có thể thêm ? sau kiểu: VD: int? a; (default value = null)
- var:  không cần chỉ định kiểu dữ liệu của biến. Nhưng nếu từ đầu ta gán giá trị cho biến thì nó sẽ xác định kiểu của biến đó là kiểu của giá trị mà ta gán luôn. Và nếu về sau chúng ta lại gán giá trị với kiểu khác thì nó sẽ lỗi
          VD: var a = 4;
              var a = "Github" -> error
2 Number:
- int: số nguyên
- double: số lẻ
- int và double có kiểu con là num
3 String:
- phép nội suy trong String: ký tự $ trong chuỗi biểu thị sự bắt đầu của một biểu thức nội suy
- Multiple line
4 Booleans:
- có 2 giá trị true và false
5 final và const: để tạo ra những biến mà giá trị của chúng không thay đổi
- const phải có giá trị khi biên dịch code, trong khi final cần có giá trị trước lần sử dụng đầu tiên
6 Toán Tử
- Toán tử số học: + - * / ~/ %
      " + " phép toán cộng
      " - " phép toán trừ
      " * " phép toán nhân
      " / " phép chia giá trị trả về cả phần nguyên và dư luôn (VD: 10/7 = 1.4285714285714286)
      " ~/ " phép chia lấy phần nguyên
      " % " phép chia lấy phần dư
- Toán tử so sánh: == != < > >= <=
          + toán tử so sánh trả về kết quả kiểu booleans
- Toán tử kiểm tra kiểu: as is is!
- Toán tử gán: += -= *= /= %=
- Toán tử logic: ! || &&
7 Collections in dart: List, Set, Map
- List:
          + khai báo: var list = [1,2,3]
          + var list = List()
          + var list = List<DataType>()
   + thêm 1 phần tử: add
   + thêm nhiều phần tử addAll
   + Xóa 1 phần tử: removeAt(int)
   + xóa tất cả các phần tử: clear
          ---- tới phần map()-----



