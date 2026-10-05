## Báo cáo giải quyết xung đột

1. Tạo nhánh `feature-update` từ `main`.
2. Chỉnh sửa file `README.md` trên nhánh `feature-update` và commit.
3. Chuyển về `main`, chỉnh sửa cùng nội dung trong `README.md` và commit.
4. Merge `feature-update` vào `main`, Git phát sinh Merge Conflict.
5. Mở `README.md` và xử lý thủ công các ký hiệu `<<<<<<<`, `=======`, `>>>>>>>`.
6. Giữ lại nội dung cần thiết và xóa các ký hiệu conflict.
7. Thực hiện `git add README.md` và tạo Merge Commit.
8. Kiểm tra lịch sử bằng `git log --graph --oneline`.