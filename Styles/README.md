- _git add "file"_: git add index.html(thêm tệp để đưa lên github)
- _git add ._:đưa toàn bộ thay đổi vào stage changes(thêm tất cả các tệp)
- _git commit -m "Message"_:git commit -m "Add index.html file"(thêm vào file vào hàng chờ để được đẩy lên github kèm tin nhắn)
- _git push_:đẩy tệp lên github
- _git push --set-upstream origin master_:dùng khi muốn đưa 1 thay đổi của nhánh lên github
- _git clone "github"_: git clone https://github.com/QUANG221222/learning_github.git (dùng để copy dự án có thể chỉnh sửa)
- _git checkout -b "name"_:tạo nhánh riêng để làm rồi mới gửi vào nhánh chính
- _git checkout "branch name"_:truy cập vào 1 nhánh
- _git branch -D "branch name"_:xóa nhánh nếu cần thiết
- _git pull_:đưa những thay đổi của nhánh chính về nhánh phụ
- _create pull request_
- _merge code to branch Master(nhánh chính)_
- _git rebase "branch(nhánh chính)"_:Lấy source code mới nhất từ nhánh chính
- _git log --oneline_:log ra những commits
- _git status_:Kiểm tra trạng thái của các file
- _ls_: hiển thị các commit

# Git reset
- Lệnh này dùng để reset lại các commit trước đó

- _git reset --soft HEAD/hash-id_: sử dụng khi lỡ commit thiếu thì có thể commit thêm
- _git reset --mixed HEAD/hash-id_: đưa các commit ra khỏi stage changes
- _git reset --hard_: 
