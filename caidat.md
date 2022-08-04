## tạo một kho lưu trữ mới

# tạo kho lưu trữ dưới local: lệnh 1

git init

# xem trạng thái khởi tạo file

git status

# chuyển file khởi tạo sang Staging Area

// chọn 1 file, sau đó chạy lệnh git status để xem thử
git add caidat.md

// chọn tất cả, sau đó chạy lệnh git status để xem thử
git add .

# chuyển file từ Staging Area sang commited,sau đó xem lại bằng lện git log

git commit -m "add index.html file"
git commit -m "add caidat.md file"

# khi thay đổi trên file, muốn updated lại dùng lệnh

git commit -m "updated caidat.md file"

# nut Q để thoát

git branch -M main
git remote add origin https://github.com/huynhvanhoa/Hoc_git.git
git push -u origin main

## đẩy một kho lưu trữ hiện có

git remote add origin https://github.com/huynhvanhoa/Hoc_git.git
git branch -M main
git push -u origin main
