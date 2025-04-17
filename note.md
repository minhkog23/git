git config --global user.name minhkog23
git config --global user.email nguyenminhcong2302@gmail.com

git config --global --unset user.name
git config --global --unset user.email

# Terms 
Repository (repo) : thư mục
branch
conflict: xung đột

local
remote

# commands
- git init
- git status
- git add 
- git reset 
- git commit -m '{write commit}'

xem lại các thời điểm lưu
- git log
- git log --oneline

trở lại thời điểm nào đó của commit
- git checkout {id commit}

branch mặc định (Master)
- git branch
Tạo branch mới
- git checkout -b {branch name}

Nếu có 2 branch khác nhau (dev) và (master)
để hợp nhất 2 branch ta dùng
- git merge {branch name}

Xóa branch
- git branch -d {branch name}
nếu xảy ra xung đột khi đã fix xong thì chỉ cần 
- git add .
- git commit : chỉ cần git commit không cần -m ''
để thoát ra gõ :q


đẩy từ local lên remote
- git push {Đường dẫn repository} {branch name} 

tạo alias
origin  
- git remote add <name> <url>

đẩy lên 
- git push {name} {branch name}

từ git lấy về 
- git clone {link git}
nếu mà clone về thì chỉ cần sử dụng
- git add .
- git commit -m ''
- git push