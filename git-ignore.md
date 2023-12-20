# 1. ĐỊNH NGHĨA
- Gitignore là file có tên là .gitignore do Git quy định.
- Nhiệm vụ của nó là liệt kê những file mà mình không mong muốn cho vào git.

# 2. CÁCH THỨC HOẠT ĐỘNG
- Gitignore sẽ bỏ qua file hoặc một tập các file trong project khi commit và push lên repository
- Khi add 1 file mới vào git, git sẽ kiểm tra danh sách những file sẽ bỏ qua trong file .gitignore và không add chúng vào git.

# 3. CÚ PHÁP 
- Dấu "/" ở sau tên thư mục để nhận biết đó là thư mục
- Dấu “!” có nghĩa là phủ định. Do vậy nên nếu bạn thêm ! vào trước một file, nó sẽ không bị bỏ qua nữa mà được thêm vào lại.
- Sử dụng "*" để "ignore" tất cả các file có cùng định dạng trong project.
- Sử dụng "#" để chú thích và có thể để cách dòng cho dễ đọc.

# 4. TẠI SAO NÊN SỬ DỤNG:
- Giảm dung lượng kho lưu trữ
- Tăng tốc quá trình đồng bộ hóa 
- Giữ cho lịch sử phiên bản của dự án trở nên sạch sẽ và dễ đọc

