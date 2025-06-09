# baitapketthucmonhoc
# Ngô Thị Thùy Linh
#MSSV : k225480106038

#Lop : K58KTP 

#Bài 9. Trình quản lý thư mục GUI

Đầu bài:

Tạo ứng dụng GUI cho phép chọn thư mục, liệt kê file theo từng loại (.txt, .py, .jpg), và cho phép mở file.

Đầu vào – đầu ra:

  Đầu vào: Nút “Chọn thư mục”.
  
  Đầu ra: Treeview hoặc Listbox hiển thị file, nút “Mở”.

Tính năng yêu cầu:
  
  Sử dụng os để scan folder.
  
  Bắt lỗi không tìm thấy đường dẫn.
  
  GUI với Treeview (tkinter.ttk).
  
  Mở file bằng chương trình mặc định.

Kiểm tra & kết quả mẫu:
  
  Chọn thư mục có 3 file → hiển thị 3 dòng.
  
  Click “Mở” file .txt → mở Notepad.

Các bước triển khai:
  
  Frame có nút và Treeview.
  
  Dialog chọn folder (askdirectory).
  
  Hàm show_files() scan và fill Treeview.
  
  Map double-click mở file (os.startfile).
