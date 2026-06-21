# learn_PY
This is where I learn python

Code Anaconda:
conda env list
conda create --name ten_moi_truong
conda create --name my_env python=3.10
conda activate ten_moi_truong
conda deactivate
conda env remove --name ten_moi_truong

conda install numpy
conda install pandas matplotlib scikit-learn

conda list
conda update numpy
conda update numpy
conda remove numpy

# code git
git remote add origin https://github.com/ten-user/ten-repo.git
git push -u origin main
git clone https://github.com/ten-user/ten-repo.git

git status	Kiểm tra trạng thái các file (file nào đã sửa, file nào chưa lưu...).
git add <tên_file>	Đưa một file cụ thể vào vùng chờ (Staging Area).
git add . hoặc git add -A	Đưa tất cả các file có thay đổi vào vùng chờ.
git commit -m "Lời nhắn"	

git branch	Liệt kê tất cả các nhánh hiện có dưới máy.
git branch <tên_nhánh>	Tạo một nhánh mới (nhưng chưa chuyển qua).
git checkout <tên_nhánh>	Chuyển sang làm việc trên nhánh khác.
git checkout -b <tên_nhánh>	Tạo mới và chuyển sang nhánh đó luôn (Lệnh tắt).
git merge <tên_nhánh>	Hợp nhất code từ nhánh được chỉ định vào nhánh hiện tại.
git branch -d <tên_nhánh>	Xóa một nhánh dưới máy (khi đã merge xong).


git remote add origin <url>	Liên kết kho chứa dưới máy với kho chứa trên mạng.
git remote -v	Xem danh sách các Remote Repo đã liên kết.
git push origin <tên_nhánh>	Đẩy code từ nhánh ở máy local lên remote.
git fetch	Tải về các thay đổi mới nhất từ remote nhưng chưa gộp vào code của bạn.
git pull	Tải về các thay đổi mới nhất và gộp luôn vào code hiện tại (git pull = git fetch + git merge).

