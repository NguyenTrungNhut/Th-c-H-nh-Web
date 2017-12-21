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

{	

	margin-top:50px;//khoảng cách trên

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

18/12/2017

Process

#process
{

	background:#eeeeee;// màu nền xám
	border-bottom:#dddddd;//đường viền dưới xám nhạt
	border-top: 1px solid #fff;
	box-shadow:0 -3px 5px rgba(0,0,0,0.3);
	position:relative;r
	z-index:10; tạo đường bóng dưới nền
	padding : 60px 0; // chỉnh khoảng không trên và dưới , trái phải ko tăng

}

.h-line
{

	max-height:5px; độ dài tối đa
	background: url(bootstrap/img/line.jpg) repeat-x; hình nền
	-webkit-border-radius:3px; 
	-moz-border-radius:3px;   
	border-radius:3px;       tạo đường tròn phía đầu đường thẳng
	position:relative;
	top:50px;
	z-index:-1;
}
.process-icon
{

	margin-bottom:15px;// mở rộng khoảng không của icon
	display:inline-block;  //hiển thị 1 khối
	width:100px; // chiều rộng
	height:101px;	//chiều cao
	background:transparent url(bootstrap/img/process.png); hình nền
	background-position: left top; vị trí hình  đầu
	
}
.process-icon.idesign
{

	background-position:-100px top; // vi trí hình 2 
}
.process-icon.idevelop
{

	background-position:-200px top; // vi trí hình 3
}
.process-icon.ilaunch
{

	background-position:-300px top; // vi trí hình 4
}
Portfolio

#portfolio
{

	padding: 60px 0;	 // khoảng cách trên dưới
}
.title
{

	margin-bottom:0; // canh chỉnh dưới
}
.category
{

	font-size:12px;  cở chữ 12
	color:#999999; màu chữ	
}

Partners


19/12/2017


#partners
{

	padding:60px 0; kích cở 	
	border-bottom:1px solid #ddd; tạo đường viền phía dưới Partner
}

Widgets

#widgets

{

	padding: 50px 0 60px 0;  // kích thước của widget
	border-bottom:1px solid #ddd;  đường viền				
}
.testimonials blockquote

{

	overflow:hidden;	//text bị tràng sẽ bị dấu đi
}
.testimonials blockquote p

{

	font-family: Grergia , Serif; // định dạnh kiêu chữ trong P
	font-style:italic; chữ in nghiêng
}
.testimonials blockquote cite

{

	color:#333; màu cho chữ trong cite
}
.blog-lists
{

	list-style:none;
	padding:0;
	margin:0;
}
.blog-lists li, .tweet-lists li

{

	border-bottom:1px solid #ddd; // đường viền
	padding: 20px 0;
}
.blog-lists li :first-child, .tweet-lists li :first-child
{

	padding-top:0;
}
.blog-lists li :last-child, .tweet-lists li :last-child

{

	border-bottom:0;
}
.blog-lists h5
{
	
	padding:0;
	margin:0;
}
.blog-lists h5 a 
{

	color:#333;// màu đen
}
.blog-lists h5 a:hover
{

	color:#444;
}
.tweet-lists
{

	list-style:none;
	padding:0;
	margin:0;
}
.tweet-lists li img
{

	margin-right:20px; canh chỉnh hình cách bên phải 20px
}

Footer

Footer
{

	padding:60px 0;
}
.table
{	

	display: table;canh chỉnh giữa trang
	
	margin: 0 auto;
}
.footer-links li
{

	float:left;
	margin-right: 40px;
}
.footer-links li a
{

	color:#666666;
	font-size:12px;
}	
.footer-links
{

	list-style: none; 
  	display: inline-block; chuyển chữ sang giữa
}
} 
social
#social
{

	clear : both;	
	margin-bottom:40px;
}
.twitter
{

	background:#568ccc;
	margin-left:5px;	
}
.twitter:hover , .twitter:focus
{

	background:#4f91bf;	
}
.facebook
{

	background:#2272a9;	
}
.facebook:hover , .facebook:focus
{

	background:#20699c;	
}
.social-spirte
{

	width:16px;
	height:16px; 
	display: inline-block;
	background:transparent url(bootstrap/img/thumbnail/Social-sprite.png) no-repeat; // gắn hình nền
	background-position:left top; vị trí hình	
}
.social-spirte.facebook
{

	background-position:-16px top;	hình 2
}

21/12/2017

Code a Responsive Website Using HTML5 and CSS3
Khung sườn

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title> HTML5/CSS3 Responsive Theme</title>
	
	<link rel="stylesheet" type="text/css" href="style.css">
	<<meta name="viewport" content="width=device-width , initial-scale=1.0">
</head>

<body class="body">
		
	<header  class="mainheader">
		<img src="img/logo.gif">
		
		<nav>
			<ul>
			<li class="active"><a href="#">Home</a></li>	
			<li><a href="#">About</a></li>	
			<li><a href="#">Portfolio</a></li>	
			<li><a href="#">Contact</a></li>	
			</ul>
			
		</nav>

	</header><!-- /header -->	
	<div class="mainContent">
		<div class="content">
			<article class="topcontent">
				<header>
					<h2><a href="#" title="Fist port"> Fist port</a></h2>
				</header>
				<footer>
					<p class="port-info">This port is written by Christan</p>	
				</footer>
				<content>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
				</content>
			</article>
		</div>
	</div>
	<aside class="top-sidebar">
		<article>
			<h2>Top sidebar</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
		</article>
	</aside>

	<aside class="middle-sidebar">
		<article>
			<h2>Middle sidebar</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
		</article>
	</aside>

	<aside class="bottom-sidebar">
		<article>
			<h2>Bottom sidebar</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
		</article>
	</aside>

	<footer class="mainFooter">
		<p>Copyright &copy ; <a href="#" title="1stwebdesigner"> </a>1stwebdesigner.com</p>
		
	</footer>
</body>

</html>

Style
Body
{

	background-image:url('img/bg.png'); //hình nền
	color:#000305; màu nền
	font-size:87.5% ;/* Base font size 14px*/ cở chữ
	font-family: Asenal,'Lucida San Unicode'; kiểu chữ
	line-height: 1.5;
	text-align:left;  canh lề trái
}
.body
{
	
	margin:0 auto;  canh chỉnh
	width:70%;	độ dài
	clear:both; trái phải của web ko đc float
	
}
a
{

	text-decoration:none;
}
a:link,a:visited

{

	color:#CF5C3F; // chữ first và second thành màu đỏ
	
}
a:hover,a:active

{

	background-color:#CF5C3F;  nền đỏ
	color:#fff; chữ trắng khi trỏ chuột vào
	
}
.mainheader img canh chỉnh hình

{

	width:30%; độ dài 		
	height:auto;
	margin:2% 0; khoảng cách trên dưới
	
}
.mainheader nav khung

{

	background-color:#666; màu khung
	height:40px;	 độ cao khung
 	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px;   2 đầu khung
	
}
.mainheader nav ul 

{

	list-style:none; bỏ dấu chấm
	margin:0 auto; canh chỉnh
	
}
.mainheader nav ul li trong khung

{

	float: left; hiển thị bên trái 
	display: inline; 
	
}
.mainheader nav a:link, .mainheader nav a:visited

{

	color:#fff; chữ màu trắng
	display:inline-block;  hiển thị bên trong khung
	padding: 10px 25px; khoảng cách mỗi chữ 
	height: 20px; độ cao
	
}
.mainheader nav a:hover, .mainheader nav a:active,.mainheader nav .active a:link chữ home, .mainheader nav .active a:visited

{

	background-color:#CF5C3F;
	text-shadow:none;
	
}
.mainheader nav ul li a tạo viền khung cong 4 góc

{

	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	
}
.mainContent

{

	line-height:25px;độ cao của chữ
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	
}
.content

{

	width:70%;  độ dài 
	float:left;
	
}
.topcontent khung chữ

{

	background-color:#fff; màu nền 
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	padding: 3% 5%; khoảng cách khung
	margin-top:2% canh chỉnh khung
	
}
.bottomcontent

{

	background-color:#fff;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	
}
.top-sidebar

{

	width:21%;
	float:left; 
	background-color:#fff; nền trắng
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	margin: 1% 0 2% 3%; cách lề top 1  dưới 2 trái 3 phải 0
	padding: 2% 3%;  tăng khoảng không trên dưới 2 trái phải 3%
	
}
.port-info

{

	font-size:85%; cở chữ
	color:#999; màu chữ 
	font-style:italic; in nghiêng
	
}
.middle-sidebar

{

	width:21%;
	float:left;
	background-color:#fff;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	margin-left:3%;
	margin-bottom:2%;
	padding: 2% 3%;
	
}

.bottom-sidebar

{

	width:21%;
	float:left;
	background-color:#fff;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	margin-left:3%;
	margin-bottom:2%; 
	padding: 2% 3%;
	
}
.mainFooter

{

	width:100%;
	height:40px;
	float:left;
	-webkit-border-radius:5px;
	-moz-border-radius:5px;
	border-radius:5px; 
	background-color:#666;
	margin-top:2% 0; 
	
}
.mainFooter p

{

	width:92%;
	margin:1% auto; canh chỉnh
	color:#fff; màu chữ
	
}

Canh chỉnh khi thu nhỏ

@media only screen and (min-width: 150px) and (max-width: 600px)  

{

	.body   canh giữa 
	{
	width:90%;
	font-size:95%;
	}
	.mainheader img canh hình
	{
		width:100%; độ lớn full
	}
	.mainheader nav
	{
		height:160px; khung của các nút Home .... cao
	}
	.mainheader nav ul
	{
		padding-left:0;  khoảng không bên trái 0;
	}
	.mainheader nav ul li
	{
		width: 100%;	 độ rộng 100%
		text-align:center; canh chỉnh chữ ở giữa hàng dọc
	}
	.mainheader nav a:link, .mainheader nav a:visited nền chữ home ...
	{
	
		padding:10px 25px;	 thêm khoảng không 2 trên dưới và 2 bên trái phải
		height:20px; 
		display:block; phủ đầy khung theo tững hàng
	}

	.content
	{
		width:100%;
		float:left;
		margin-top:2%; canh chỉnh chữ cách khung chọn
	}
	.port-info
	{
		display:none; ẩn dòng chữ trong port-info
	}
	.topcontent
	{
		background-color:#fff;
		-webkit-border-radius:5px;
		-moz-border-radius:5px;
		border-radius:5px; 
		padding: 3% 5%;
		margin-top:2%;
		margin-bottom:4%;
	}
	.bottomcontent
	{
		margin-top:3%;
	}
	.top-sidebar,.middle-sidebar,.bottom-sidebar
	{
		width:94%;
		margin: 1% 0 2% 0%;
		padding: 2% 3%;
		
	}

}

