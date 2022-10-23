# Git

1. git-scm là gì?
    git là hệ thống quản lý phân tán dữ liệu,
    git là 1 app cung cấp các dòng lệnh để kết nối từ máy local đến repo
    github, gitlab là một dùng để lưu trưc các đoạn code cá nhân or project...

2. cách lệnh git cơ bản
    + ```git clone```: kéo repo từ nơi lưu trữ online về máy 
    + git commit: thêm comment cho lần push code lên repo
    + git branch: tạo nhánh, xóa, sửa nhánh...
    + git add: thêm 1 hoặc tất cả các file mới tạo và các file đã được sửa
    + git checkout : chuyển nhánh, kết hợp với branch tạo nhánh
    + git pull: pull code mới nhất trên repo về máy local
    + git push: push code mới nhất từ máy local lên repo
    + git fetch: kiểm tra và kéo các nhánh mới được tạo về local
    + origin: là phiên bản mặc định của nhánh chínhvà nó đóng vai trò là bí danh của hệ thống
    để liên lạc với nhánh chính
    + git master: nó là tên nhánh chính, mới được đỏi thành main
    + git merge: merge code mới nhất từ các nhánh về nhánh chính
    + git stash: lưu trữ lại những file thay đổi
    + git status: kiểm tra trạng thái hiện tại của nhánh
    + git remote: giúp giao tiếp ngược dòng từ local vs nhánh chính
    + git repository: là kho lưu trữ code
    + git tag: cung cấp cho các bạn một cách đẻ theo dõi các commit quan trọng
    + git upstream: nó đề cập đến cái nới mà các bạn push code, mặc định là nhánh chính(master)
    + git init: khởi tạo 1 repo tại local
    + git config: cấu hình git tại local(add email, add username...)

3. các bước thực hiện việc commit code từ local lên repo
    B1: git status
    B2: git add
    B3: git commit -m "nội dung cần coomit"
    B4: git push origin master/branch_name

4. các bước clone repo trên internet và local
    B1: vào nơi dùng để lưu trữ repo trên local
    B2: mở git bash here
    B3: copy link repo
    B4: git clone <link từ B3>

5. các bước tạo ra 1 nhánh mới
    B1: vào repo mở git bash here(đang ở nhánh master)
    B2: git checkout -b <branch name> vd: binh_th - huyen_ntm

6. các bước pull code mới nhất từ repo về local
    để lấy code mới nhất từ nhánh master về máy local thì dùng lênh như sau
    - git pull origin master (master luôn là nhánh chính, anh sẽ mer all code)
