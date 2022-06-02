Sao chép (clone) một repository : 

    Để clone 1 repository có sẵn ở trên máy cục bộ, bạn hãy sử dụng dòng lệnh sau:
    + git clone <Đường dẫn>

    Nếu repository đó ở máy chủ khác thì bạn hãy gõ dòng lệnh sau:
    + git clone tênusername@địachỉmáychủ: <Đường dẫn>

Thêm (add) & commit : 

    + git add <Tên file> hoặc <.> để thêm tất cả các file

    Để thật sự commit những thay đổi, bạn sử dụng : 
    + git commit -m "Ghi chú Commit"

Đẩy (push) các thay đổi : 
    
    Để gửi những thay đổi đó đến repository remote, bạn thực thi : 
    + git push origin master
    Thay đổi "master" bằng bất cứ nhánh nào mà bạn muốn đầy những thay đổi đến.


    Nếu bạn chưa clone một repository hiện có và muốn kết nối repository của bạn đến máy chủ remote, bạn phải thêm nó với : 
    + git remote add origin <máy-chủ>


Nhánh (branch) : 

    Tạo một nhánh mới và đặt tên là "lession_a" và chuyển qua nhánh đó (từ master) bằng cách : 
    + git checkout -b lession_a

    Trở lại nhánh master : 
    + git checkout master

    Xóa nhánh lession_a đó : 
    + git branch -d lession_a

    Một nhánh không có giá trị với các nhánh khác trừ khi bạn đẩy nhánh đó đến remote repository : 
    + git push origin <nhánh>

Cập nhật & trộn (update & merge) : 

    Để cập nhật repository cục bộ của bạn và commit mới nhất, thực thi : 
    + git pull

    Để trộn một nhánh khác vào nhánh đang hoạt động (vd: master), sử dụng : 
    + git merge <nhánh>

    
