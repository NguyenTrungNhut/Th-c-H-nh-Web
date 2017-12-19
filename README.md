# Th-c-H-nh-Web
14/12/2017
Ctrt+g : group nhóm 

Chuột phải smart object rùi quăng qua 

Tạo 1 pattem

Sau khi tô xong, nhấn Ctrl + A hoặc vào Selection > Select all để chọn tất cả. Vào menu Edit > Define pattern. Trong cửa sổ mới hiện ra, đặt tên cho pattern vừa tạo.

Cắt hinh
M rùi edit -> copy merged

Thêm hinh
 chọn Image -> Image Size hoặc dùng tổ hợp phím tắt Ctrl + Alt + I.
 
Copy hình và lấy size hình
M rùi Ctrl + Shift + C

Thay đổi kích thước hình
M rùi Ctrl + Alt + C

Tắt mở đường thước rule
Ctrl + :

Tắt mở ổ vuông 
Ctrl + “

Đổi màu background
G

Tham khảo code bootstrap
http://getbootstrap.com/2.3.2/ 

Khung sườn
<div class="hero-unit">
			<div class="container">
				<div class="navbar">//chuyển khung nằm ngăng
					<div class="navbar-inner">
						<nav class="pull-right ">
							<ul class="nav">
								<li class="active"><a href="#">Home</a></li>
								<li><a href="#">About Us</a></li>
								<li><a href="#">Services</a></li>
								<li><a href="#">Blog</a></li>
								<li><a href="#">Contact Us</a></li>
							</ul>
						</nav>
					</div>
				</div>	
			</div>
		</div>
		
15/12/2017

Code

Chỉnh font chữ cho những hinh

@font-face
{
	font-family:'Museo';
	src: url('bootstrap/js/exljbris - Museo-700.otf') format('truetype');
}

h1,h2,h3,h4,h5,h6
{
	font-family:'Museo', Rockwell,Serif;
}

a
{
	color:#fb2f3a;// màu chữ
}

a:hover, a:focus
{
	color:#eb2f39;	
	
	text-decoration:none;   
	
	border-bottom:1px solid;
}


Button

.btn
{
        -webkit-border-radius:3px;
	
	-moz-border-radius:3px;
	
	border-radius:3px;   //kích thước
	
	background:#9a9c9f; // màu nền
	
	font-size:12px; cở chữ
	
	font-weight:bold; chữ đậm
	
	color:#fff; màu chữ
	
	text-shadow:none; // bóng chữ
	
	box-shadow:inset 0 1px 0 rgba(255,255,255,0.2); bóng khung
	
	border:1px solid rgba(0,0,0,0.2); khung giữa bao ngoài chữ
	
}

.btn:hover, .btn:focus
{
	background:#8e9093; // nền xám
	
	color:#fff; chữ trăng
	
	border:1px solid rgba(0,0,0,0.2);khung giữa
	
	margin-top:30px;


}

.heading
{

	margin-bottom:20px;	// h4
	
}

Navbar

.hero-unit khung đầu
{
	padding:0px; 	
	
	background: #222  url(bootstrap/img/hero-unit.jpg) no-repeat 50% top ; chèn hình
	//#222  những khoảng trắng 2 bên sẽ được tô đen
	
	border-radius:0;
	
	margin-bottom:0;// khoảng cách dưới 0
	
} 
 
.navbar-inner // khung 
{
	//(padding : 40px 0; khung cách đầu web 1 khoảng)
	
	background:transparent; //trong suốt
	
	border:none; // ko hộp
	
	box-shadow:none;//ko có bóng
	
}

.navbar
{
	margin-top: 30px;//cách top 1 khoảng

	border-bottom:1px solid rgba(255,255,255,0.2) tạo đường kẻ ngang màu xám
	
}

.navbar .brand // dipped
{
	text-indent:-9999px;
	
	width:127px; //độ dài
	
	height:50px;//chiều cao
	
	background:url(bootstrap/img/bracd.png) no-repeat; đường dẫn hình ko lập 
	
}

.navbar .nav
 {
	padding:0; canh chỉnh vị trí
	
	margin:0;
	
}

.navbar .nav > li > a // đinh dạng kiểu chử Home About Us ....
{
	font-weight:bold;//chữ đậm
	
	font-size:14px;// cở chữ
	
	text-shadow:none;// chữ ko có bóng
	
	color:#ffff; màu chữ màu trắng
	
	padding:3px 10px ; /khung cho chữ 
	
}

.navbar .nav > li > a:focus, .navbar .nav > li > a:hover
{

	color:rgba(255,255,255,0.7);// trỏ chuột sẽ chuyển màu màu xám
	
}

.navbar .nav > .active > a, .navbar .nav > .active > a:hover, .navbar .nav > .active > a:focus

{
	box-shadow:none; //khung ko có bóng
	
	background:rgba(0,0,0,0.7);//đổ màu nút Home khung màu đen
	
}

Hero-unit-inner

.hero-unit-inner h1

{	margin-top:50px;//khoảng cách trên

	margin-bottom:20px; //khoảng cách dưới
	
	font-size:48px;//cở chữ
	
	color:#fff;	//màu chữ
	
	text-shadow: 0 1px 0 //tạo bong  rgba(0,0,0,0.3) hiển thị độ bóng ;
	
}

.hero-unit-inner h4
{
	color:#cccccc;	chữ màu xám
	
	text-shadow: 0 1px 0 rgba(0,0,0,0.3); tạo bóng cho chữ
	
	margin-bottom:20px;// khoảng cách dưới
	
}

.hero-unit-inner  a
{
	margin-left:10px ;  // khoảng cách giữa 2 chữ
	
	color : #fff;	//màu chữ sám
	
	border-bottom:1px solid #ddd;  độ lớn cho đường viền dưới và màu cho chữ LearnMore
	
}

.hero-unit-inner img
{

	margin-top:30px;	khoảng cách từ botton tới hình
	
}

.hero-unit-inner .btn-primary
{
	background:#fb2f3a; màu nút
	
	border:none; đường viền 0
	
	box-shadow:0 2px 1px rgba(0,0,0,0.3); bóng
	
	font-size:16px; cở chữ
	
	font-weight:bold; kiểu đậm
	
	text-shadow:none; bóng chữ
	
}
