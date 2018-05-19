file-manager
============

Tên SV : Nguyễn Vũ

MÃ SV : 17it120

ĐỀ số 13 :

Câu 1 :Giao diện FileExplore ;

Câu 2 : Chức năng Paste folder;

Chức năng làm thêm Copy File và Open File.

CHỨC NĂNG Chính: COPYFILE
Dùng Files.copy(path SrcFile , path DesFile);

Hàm được sử dụng để copy với 2 đối số là đường dẫn đến thư mục chứa file và đường dẫn mới đến thư mục cần copy .

vd :

     sourcepath :   D:\newfolder:\File.java  
     
     DesPath :  D:\File.java 
     
     Thì File.java sẽ được copy từ sourcepath đến desPath (từ thư mục newfolder -> ổ D )
Bắt sự kiện mouseClicked cho btnCopy ;

Step 1 : Lấy Đường dẫn hiện tại của File và cộng chuỗi là tên File để có được đường dẫn hiện tại .

Step 2 : Trỏ đến đường dẫn mới , lưu đường dẫn mới vào Paths và cộng chuổi vs tên File để có được đường dẫn đến thư mục muốn copy đến

Step 3 : Thức hiện copy với 2 đường dẫn đã lấy được ở 2 bước trước bằng hàm Copy đã nói trên .
