# oop-exercise Abastract & Interface

Lưu ý: tuân thủ <a href="https://github.com/sang-hv/oop-coding-convention/blob/main/README.md" target="_blank">coding covention</a>

## Bài tập Abstract:

1. Tạo một class trừu tượng "Shape" (Hình dạng) có một phương thức trừu tượng là "calculateArea". Tạo các lớp con "Circle" (Hình tròn) và "Rectangle" (Hình chữ nhật) kế thừa từ lớp Shape và triển khai phương thức calculateArea cho từng hình.

2. Tạo một abstract class "Animal" (Động vật) với một phương thức trừu tượng là "makeSound". Tạo các lớp con "Dog" (Chó) và "Cat" (Mèo) kế thừa từ lớp Animal và triển khai phương thức makeSound theo cách riêng của từng loại động vật.

3. Tạo một abstract class "Employee" (Nhân viên) với các thuộc tính trừu tượng như "name" (tên) và "salary" (mức lương). Tạo các lớp con "Manager" (Quản lý) và "Staff" (Nhân viên) kế thừa từ lớp Employee và triển khai các thuộc tính và phương thức theo cách riêng của từng lớp.

4. Tạo một abstract class "Vehicle" (Phương tiện) với một phương thức trừu tượng là "start". Tạo các lớp con "Car" (Xe hơi) và "Motorcycle" (Xe máy) kế thừa từ lớp Vehicle và triển khai phương thức start theo cách riêng của từng loại phương tiện.

5. Tạo một abstract class "Database" (Cơ sở dữ liệu) với các phương thức trừu tượng như "connect", "query" và "disconnect". Tạo các lớp con "MySQLDatabase" và "PostgreSQLDatabase" kế thừa từ lớp Database và triển khai các phương thức theo cách riêng của từng loại cơ sở dữ liệu.

## Bài tập Interface:

1. Tạo một interface "Resizable" (Có thể điều chỉnh kích thước) với một phương thức là "resize". Tạo một lớp "Rectangle" (Hình chữ nhật) và triển khai interface Resizable để thay đổi kích thước của hình chữ nhật.

2. Tạo một interface "Logger" với các phương thức "logInfo", "logWarning" và "logError". Tạo một lớp "FileLogger" (Ghi log vào file) và một lớp "DatabaseLogger" (Ghi log vào cơ sở dữ liệu) và triển khai interface Logger cho cả hai lớp.

3. Tạo một interface "Drawable" (Có thể vẽ) với phương thức "draw". Tạo một lớp "Circle" (Hình tròn) và một lớp "Square" (Hình vuông) kế thừa từ interface Drawable và triển khai phương thức draw cho mỗi hình.

4. Tạo một interface "Sortable" với phương thức "sort". Tạo một lớp "ArraySorter" (Sắp xếp mảng) và một lớp "LinkedListSorter" (Sắp xếp danh sách liên kết) và triển khai interface Sortable cho cả hai lớp.

5. Tạo một interface "Encryptable" (Có thể mã hóa) với phương thức "encrypt" và "decrypt". Tạo một lớp "AES" và một lớp "DES" kế thừa từ interface Encryptable và triển khai các phương thức theo thuật toán mã hóa tương ứng.
