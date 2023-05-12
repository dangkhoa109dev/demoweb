

<html>
<head runat="server">
    <title>Trang Chủ - Bàn ghế văn phòng giá rẻ</title>
    <asp:ContentPlaceHolder ID="head" runat="server">
    </asp:ContentPlaceHolder>
    <link rel="shortcut icon" href="img/table.jpg" type="image/x-icon" />
    <link href="main-style/main.css" rel="stylesheet" />
    <link href="main-style/themify-icons/themify-icons.css" rel="stylesheet" />
</head>
<body>
    <form id="form1" runat="server">
        <div class="header">
            <img href="Default.html" id="logo" src="img/logo.png"/><a id="brand" href="Default.html">K.T</a>
            <div id="search">
                <input type="text" style="width:250px; height:30px;" placeholder="Tìm kiếm sản phẩm" />
            </div>
            <div id="find">
               <i class="ti-search" style="font-size: 30px;"></i>
            </div>
            <div id="cart">
                <i class="ti-shopping-cart"></i><a> 0đ</a>
            </div>
        </div>
        <div class="nav">
            <ul>
                <li><i class="ti-menu nav_menuicon"
                    style="padding: 0 10px;"></i>DANH MỤC SẢN PHẨM<i class="ti-angle-down"
                    style="padding: 0 10px;"></i>
                    <ul class="sub_nav">
                        <li>Bàn ăn</li>
                        <li>Bàn học</li>
                        <li>Nội thất gia đình</li>
                        <li>Ghế sofa</li>
                        <li>Giường</li>
                    </ul>
                </li>
                <li><a href="Default.html" style="text-decoration: none;
        color:#fff;">TRANG CHỦ</a></li>
                <li><a href="GioiThieu.html" style="text-decoration: none;
        color:#fff;">GIỚI THIỆU</a></li>
                <li><a href="TinTuc.html" style="text-decoration: none;
        color:#fff;">TIN TỨC</a></li>
                <li><a href="LienHe.html" style="text-decoration: none;
        color:#fff;">LIÊN HỆ</a></li>
            </ul>
        </div>
        <div>
            <div class="banner">
                <img src="img/BANNER-5.jpg" height="640px" width="100%" />
            </div>
            <div class="content_1">
                <h1>BÀN GHẾ VĂN PHÒNG K.T</h1>
                <a><br /></a>
                <a style="font-size:18px;">Chúng tôi đã hoạt động từ năm 2006 dưới tên gọi khác và chính thức thành lập Công Ty từ năm 2018.<br /> Bàn Ghế Văn Phòng K.T tiên phong trong lĩnh vực nội thất văn phòng và hoạt động liên tục tại thị trường Tp. Đà Nẵng<br />với tư cách là một trong những nhà sản xuất và phân phối hàng đầu trong ngành nội thất văn phòng.</a>
            </div>
            
            <div class="content_2">
                <ul>
                    <li><img src="img/table.jpg" height="205px" width="250px" /><br /><a>BÀN VĂN PHÒNG</a></li>
                    <li><img src="img/chair.jpg" height="205px" width="250px" /><br /><a>GHẾ VĂN PHÒNG</a></li>
                    <li><img src="img/cabinet.jpg" height="205px" width="250px" /><br /><a>TỦ QUẦN ÁO</a></li>
                    <li><img src="img/funiture.jpg" height="205px" width="250px" /><br /><a>NỘI THẤT GIA ĐÌNH</a></li>
                    <li><img src="img/quay.jpg" height="205px" width="250px" /><br /><a>QUẦY LỄ TÂN</a></li>
                </ul>
            </div>
            
            <div class="content_3">
                <h1 style="text-align:center;">VÌ SAO BẠN NÊN CHỌN CHÚNG TÔI</h1>
                    <ul>
                        <li><img src="img/doingutuvan.jpg" height="170px" width="240px" /><br /><a><h3>Đội ngũ tư vấn tận tình</h3><br />
            Nhân viên lâu năm, nhiều kinh nghiệm, nhiệt huyết, tận tụy. Vui vẻ, hòa đồng.</a></li>
                        <li><img src="img/taynghecao.jpg" height="170px" width="240px" /><br /><a><h3>Đội ngũ kỹ thuật giỏi</h3><br />
            Đội ngũ kỹ thuật đều là những người thợ lành nghề, có nhiều năm kinh nghiệm .</a></li>
                        <li><img src="img/sanphamdadang.jpg" height="170px" width="240px" /><br /><a><h3>Sản phẩm đa dạng</h3><br />
            Nhiều kích thước, màu sắc, chất liệu đáp ứng mọi nhu cầu của khách hàng.</a></li>
                        <li><img src="img/giaohangnhanh.jpg" height="170px" width="240px" /><br /><a><h3>Giao hàng nhanh chóng</h3><br />
            Giao đến khách hàng một cách nhanh chóng - đúng giờ kiểm tra khi nhận.</a></li>
                    </ul>
            </div>
            
            <div class="content_4">
                <div class="sub_ban">
                    <h1>KHUYẾN MÃI HÀNG TUẦN</h1>
                </div>
                <ul>
                    <li><img src="img/chair.jpg" height="170px" width="240px" /><br /><a id="name_pro">Ghế Xoay Lưới KGM-330</a><br /><a id="price_pro">555.000</a><a id="new_price">510.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                    <li><img src="img/table.jpg" height="170px" width="240px" /><br /><a id="name_pro">Bàn ăn cao cấp</a><br /><a id="price_pro">10.500.000</a><a id="new_price">10.300.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                    <li><img src="img/cabinet.jpg" height="170px" width="240px" /><br /><a id="name_pro">Tủ quần áo cao cấp</a><br /><a id="price_pro">555.000</a><a id="new_price">510.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                    <li><img src="img/funiture.jpg" height="170px" width="240px" /><br /><a id="name_pro">Nội thất gia đình</a><br /><a id="price_pro">555.000</a><a id="new_price">510.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                </ul>
            </div>
            <div class="content_4">
                <ul>
                    <li><img src="img/chair.jpg" height="170px" width="240px" /><br /><a id="name_pro">Ghế Xoay Lưới KGM-330</a><br /><a id="price_pro">555.000</a><a id="new_price">510.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                    <li><img src="img/table.jpg" height="170px" width="240px" /><br /><a id="name_pro">Bàn ăn cao cấp</a><br /><a id="price_pro">10.500.000</a><a id="new_price">10.300.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                    <li><img src="img/cabinet.jpg" height="170px" width="240px" /><br /><a id="name_pro">Tủ quần áo cao cấp</a><br /><a id="price_pro">555.000</a><a id="new_price">510.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                    <li><img src="img/funiture.jpg" height="170px" width="240px" /><br /><a id="name_pro">Nội thất gia đình</a><br /><a id="price_pro">555.000</a><a id="new_price">510.000đ</a><br />
                        <button class="btn_mua">Thêm vào giỏ hàng</button>
                    </li>
                </ul>
            </div>
            <div class="content_5">
                <div id="con5_text">
                    <i class="ti-pin-alt"></i><h4>Đăng ký để nhận được ưu đãi nhé</h4>
                </div>
                <div id="con5_box">
                        <input style="Width:300px; Height:30px;" placeholder="Liên hệ ngay..."/><button style="Height:34px; Width:60px; BackColor:DarkGray;">Gửi</button>
                </div>
            </div>
        </div>
        <div class="footer">
            <ul>
                <li><h4>KHU VỰC CÔNG TY</h4><hr /><br /><a>CÔNG TY CỔ PHẦN ĐẦU TƯ THƯƠNG MẠI KHÔNG GIAN MỚI<br />
Trụ sở công ty: Hòa Minh, Liên Chiểu, Đà Nẵng
MST: 03******* do Sở Kế Hoạch và Đầu Tư Đà Nẵng cấp ngày 21/03/2023
Xưởng sản xuất: 7/10 Đường Hòa Minh, Liên Chiểu, Đà Nẵng
Thời gian làm việc: Thứ 2 - Thứ 7
Giờ làm việc: 08h00 - 18h00
Hotline: 090.000.0000 - 097.234.5678
Email: khoa1092002@gmail.com
Website: *************.com<br /><br /><br /></a></li>
                <li><h4>DANH MỤC SẢN PHẨM CHÍNH</h4><hr /><br /><a>CÔNG TY CỔ PHẦN ĐẦU TƯ THƯƠNG MẠI KHÔNG GIAN MỚI<br />
Bàn Làm Việc<br />
Bàn Giám Đôc<br />
Bàn Chân Sắt<br />
Bàn Họp<br />
Ghế Nhân Viên<br />
Ghế Phòng Họp<br />
Ghế Giám Đốc<br />
Tủ Hồ Sơ<br />
Quầy Lễ Tân
<br /><br /><br /><br /> <br /><br />
</a></li>
                <li><h4>CHÍNH SÁCH KHÁCH HÀNG</h4><hr /><br /><a>Chính sách bảo hành<br />
Chính sách đổi trả - hoàn tiền<br />
Chính sách thanh toán<br />
Chính sách vận chuyển<br />
Chính sách bảo mật<br />
Chính sách kiểm hàng<br />
<br /><br /><br /><br /> <br /><br /><br /><br /><br /><br /><br />
</a></li>
                <li><h4>LIKE FANPAGE CHÚNG TÔI</h4><hr /><br /><i class="ti-facebook"></i><a style="margin-left:10px;text-decoration:none; color:#000; font-weight:600;" href="https://www.facebook.com/profile.php?id=100055252343456">Nguyễn Đăng Khoa</a><br /><br /><br /><br /><br /><br /><br />
<br /><br /><br /><br /> <br /><br /><br /><br /><br /><br /></li>
            </ul>
            <div style="text-align:center; font-size:13px; margin-top:40px;">Công ty cổ phần công ty trách nhiệm hữu hạn 1 thành viên @</div>
        </div>
    </form>
</body>
</html>

