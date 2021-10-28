================================================
*******_CÁC BƯỚC PUSH DỮ LIỆU LÊN GITHUB_*******
================================================
------------------------------------------------
STEP 1: KHỞI TẠO REPO DƯỚI LOCAL
-> git init
------------------------------------------------
STEP 2: TẠO NHÁNH
-> git checkout -b <tên nhánh>
------------------------------------------------
STEP 3: COMMIT CODE
a) Tạo file
	git add <fileName>
		-> add từng file một
	git add .
		-> add tất cả các file
b) commit
	git commit -m "<ghi chú>"
------------------------------------------------
STEP 4: ADD REMOTE
-> git remote add origin <đường link của repo>
------------------------------------------------
STEP 5: PUSH CODE
-> git push origin

=> XONG TASK

================================================
================================================
*****_NHỮNG CÂU LỆNH THƯỜNG DÙNG TRONG GIT_*****
================================================
git status 
	-> kiểm tra trạng thái
git branch 
	-> xem danh sách nhánh
git branch -d
	-> xoá nhánh
git checkout -b <tên nhánh>
	-> tạo mới một nhánh
git checkout <tên nhánh>
	-> chuyển nhánh
git commit -m "message"
	-> commit code
git log --oneline
	-> kiểm tra đường dẫn
git push origin <tên nhánh> 
	-> đẩy code lên nhánh, origin là tên remote ta tự đặt
git pull origin <tên nhánh>
	-> kéo code mới nhất từ nhánh về local
------------------------------------------------
================================================
CÁCH TẠO SSH KEY: 
Mở terminate (trên Linux, macOS hoặc cmd trên Windows) rồi gõ dòng lệnh: 
ssh-keygen -t rsa
_______________________________________________
Developer's hack (shortcode):
git remote set-url origin https://<githubtoken>@github.com/<username>/<repositoryname>.git
