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
--------------- hết bài Tự học ngôn ngữ Dart: Type Inference, Type Annotation, Dynamic Types, Constants-----------------
