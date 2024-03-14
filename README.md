## Lớp Item
- Là một lớp trừu tượng
- Có thuộc tính chứa tên name (public) kiểu String
- Có thuộc tính mô tả description (private) kiểu String có phương thức get set tương ứng
- Có thuộc tính chứa ID (protected) kiểu String
- Có thuộc tính giá price (default) kiểu float hoặc int
- Có 1 phương thức trừu tượng void showInfo()
- Có phương thức khởi tạo với tham số là các thuộc tính nói trên
## Lớp MP3
- Kế thừa (extend) lớp Item
- Có thêm thuộc tính duration
- Có phương thức khởi tạo với đầy đủ thuộc tính
## Lớp Book
- Tạo lớp Book kế thừa lớp Item
- Có thêm các thuộc tính author (String), numberOfPages(int), genre (String).
- Có phương thức khởi tạo với đầy đủ thuộc tính
## Lớp Main
- Trong phương thức main() tạo ra 1 đối tượng MP3 và 1 đối tượng Book
- Gọi phương thức showInfo() của mỗi đối tượng để hiện thị thông tin thuộc tính của đối tượng