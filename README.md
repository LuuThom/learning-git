# learning-git

Git

1. Lien ket thu muc hien tai voi repo github: git remote origin [dia chi repo]
Ex: git remote add origin git@github.com:LuuThom/18_03_Project.git

2.  Cac thao tac cơ bản để đẩy code lên github

- Tạo branch mới: tên branch mô tả ngắn gọn phần task A cần làm.: git chekout -b name-branch
- Code.....
- git add -A 
- git commit -m "...."
- git push origin tên-branch.
- chuyển nhánh: git checkout name-branch (nhớ là phải kiểm tra xem nhánh hiện tại có đang làm file nào, đã commit chưa ? commit rồi thì mới được chuyển nhánh).

- Thao tác để kéo code mới nhất về thư mục lap khi thực hiện 1 chức năng mới. (sau khi chức năng A được merge vào master.): git pull origin master (khi ở nhánh master)
hoặc là git fetch origin 