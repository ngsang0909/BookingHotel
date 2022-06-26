# Booking

#### How to use the app

    1) Tạo file .env trong thư mục api
	Thêm 2 dòng: MONGO = mongodb+srv://<username>:<password>@cluster0.nfaku.mongodb.net/<DatabaseName>?retryWrites=true&w=majority
		     JWT =lkjjlqakjr43j43ouAaklsejklejkljklsjeklsjeks
	<username>: là username mongoDB Atlas
	<password>: là password mongoDB Atlas
	<DatabaseName>: là tên DB

       Mở terminal 1 -> Vào api -> Run 'npm start' -> Connected with DB
    2) Mở terminal 2 -> Vào admin -> Run 'npm start' -> Đăng nhập bằng account {username: Admin, password: 123456} -> login
       - Tạo mới user, hotel, room
       - Delete, edit
    3) Vì Admin và Client sử dụng chung port 3000 -> Ctrl + C ở terminal 2 để dừng Admin
    4) Mở terminal 3 -> Vào Client -> Run 'npm start' -> Đăng nhập bằng account {username: Admin, password: 123456} (Nếu cần)
        -> Tìm kiếm khách sạn theo Thành phố, ngày checkin, số phòng, giá,....


### Booking with admin panel using

- MongoDB
- Express
- React
- Node
- React Router V6\*
- axios
- Cloudinary
- bcryptJs
- cookie-parser
- jsonwebtoken
- Sass
- Material Ui Icons - Table - Data-grid
- Recharts

### Preview :

#### Booking clone home page

![preview1](https://i.ibb.co/xXZFdxj/Screenshot-3.png)

#### Hotel admin page

![preview2](https://i.ibb.co/QHdMw2S/Untitled.png)

#### Hotel admin page with Dark mode

![preview3](https://i.ibb.co/kcTfX9y/Admin-Dark-Mode.png)

#### Search Hotel with filter

![preview4](https://i.ibb.co/Jp9y4FT/Searching-Hotel.png)
