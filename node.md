# Terms
Repository(Repo)
# Commands
- git init (tạo dự án thành repository)
- git status (trạng thái dự án)
- git add (chuẩn bị file để lưu lại dự án)
    git add . -> chuẩn bị lưu lại tất cả file
- git reset (không chuẩn bị lưu nữa)
- git commit (chính thức lưu)
    git commit -m 'Đây là đoạn ghi chú'
- git log (xem nhật ký)
    git log --oneline (gọn hơn, lấy ra {id} để quay lại)
- git checkout {id} (quay lại id đó)
- git checkout {branch name}
    Ví du: git checkout master(mặc định)
- git branch: xem branch name
- git checkout -b {branch name}: tạo 1 branch mới (cành mới)
- git merge {tên cần tổng hợp}: tổng hợp các branch lại với nhau
- git branch -d {tên branch}: xóa branch
# Conflict: xung đột
# Git Hub
- git push {đường dẫn github} {tên branch}: đẩy lên git hub
- git remote add {tên thay thế} {đường dẫn}
    lần sau push: git push {tên thay thế} {branch name}
- git clone {đường dẫn}: lấy code từ github về
- Dạng:
    git add .
    git commit -m 'remote clone'
    git push: không cần ghi đường dẫn sẽ tự đẩy lên git hub
- git push -u {tên thay thế} {branch name}: thêm branch lên github
- git pull: sau khi merge pull trên github thì sẽ thay đổi trên project local