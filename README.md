LỆNH GIT CƠ BẢN
git init: khởi tạo kho lưu trữ git mới cho 1 dự án mới hoặc đã có sẵn
git add "file": git add index.html(thêm tệp để đưa lên github)
git add .:đưa toàn bộ thay đổi vào stage changes(thêm tất cả các tệp)
git commit -m "Message":git commit -m "Add index.html file"(thêm vào file vào hàng chờ để được đẩy lên github kèm tin nhắn)
git push:đẩy tệp lên github
git push --set-upstream origin master:dùng khi muốn đưa 1 thay đổi của nhánh lên github
git clone "github": git clone https://github.com/QUANG221222/learning_github.git (dùng để copy dự án có thể chỉnh sửa)
git checkout -b "name":tạo nhánh riêng để làm rồi mới gửi vào nhánh chính
git checkout "branch name":truy cập vào 1 nhánh
git branch -D "branch name":xóa nhánh nếu cần thiết
git pull:đưa những thay đổi của nhánh chính về nhánh phụ
create pull request
merge code to branch Master(nhánh chính)
git rebase "branch(nhánh chính)":Lấy source code mới nhất từ nhánh chính
git log --oneline:log ra những commits
git status:Kiểm tra trạng thái của các file
ls: hiển thị các commit
git push origin -d 'nhánh' : xóa nhánh trên remote
Git reset
Lệnh này dùng để reset lại các commit trước đó

git reset --soft HEAD/hash-id: sử dụng khi lỡ commit thiếu thì có thể commit thêm

git reset --mixed HEAD/hash-id: đưa các commit ra khỏi stage changes

git reset --hard:
