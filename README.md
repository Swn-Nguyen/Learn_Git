* Khi bắt đầu tạo một git sử dụng: "git init"
* Sử dụng "git add + tên file/folder" hoặc "git add ." để thêm những thay đổi trên folder chứa .git

  * Red = untracked
  * Green = staged
  * Blue = modified but not staged
* Sau khi cập nhật file/folder trong project, sử dụng "git commit "

  * git commit -m "message": commit với message
  * git commit -ma "message": git add tất cả các file đã được tracked và commit
  * git commit --amend: sửa đổi nội dung của commit cuối
* Sử dụng git log để xem lịch sử các commit.

  * git log --oneline: hiển thị 7 ký tự đầu mã hash và tiêu đề commit
  * git log --oneline --graph --all: sơ đồ hình cây trực quan thể hiện các nhánh đang tách và gộp
  * git log -p: xem cụ thể từng dòng code bị xóa hoặc thêm trong mỗi commit
* Khi muốn xem sự khác nhau giữa 2 lần commit: git diff hashCode1 hashCode2
* .gitignore dùng để không track các file cụ thể

  * Các file nhạy cảm như password.txt, secrets.txt, ...
  * Virtual enviroments (NameFolder/)



