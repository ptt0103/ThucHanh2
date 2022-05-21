# ThucHanh2

Mô tả:
 - Kết nối project với CSDL trên MySQL
 - Tạo lớp thực thể tương ứng với table CSDL
 - Sử dụng Spring Data JDBC tạo repository (productDB)
 - Viết các lớp Controller và trang view(html)
  
Phân chia công việc:
  - Phạm Tường Thụy: làm 2 chức năng xem và thêm product gòm các Controller ViewProducts, AddProductController, HomeController, các trang html: home, addProduct
                    displayProducts;
  - Vũ Thị Quỳnh : Làm chức năng edit product gồm Controller EditController và trang html: edit
  - Trần Đình Hoan: làm chức năng remove product gồm Controller RemoveController và trang html: remove
  - Mỗi người tự viết Repository trong file ProductDB để cập nhật kết quả trên csdl
  
