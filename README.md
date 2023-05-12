<!DOCTYPE html>

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
* {
    padding: 0;
    margin: 0;
}

html {
    font-family: Arial, Helvetica, sans-serif;
}

/*-------------Header-----------------------*/
.header {
    height: 80px;
    width: 100%;
    background-color: #f1f1f1;
    display: flex;
}

#logo {
    width: 120px;
    height: 80px;
    line-height: 80px;
    cursor: pointer;
}

#brand {
    color: navy;
    margin-left: -20px;
    font-family: VNI-Dom;
    padding-top: 15px;
    font-size: 35px;
    text-decoration: none;
}

    #brand:hover {
        color: crimson;
        cursor: pointer;
    }

#search {
    line-height: 80px;
    margin-left: 400px;
}

#find {
    line-height: 100px;
    margin-left: 10px;
}

#find:hover{
    cursor: pointer;
}

#cart {
    font-weight: 550;
    font-size: 20px;
    line-height: 90px;
    margin-left: 350px;
}

#cart:hover{
    color: grey;
    cursor: pointer;
}

.nav {
    height: 40px;
    width: 100%;
    background-color: #09ACB5;
}

    .nav li {
        display: inline-block;
        line-height: 40px;
        margin-left: 20px;
        margin-right: 20px;
        color: #fff;
        font-weight: 600;
        position: relative;
    }

        .nav li:hover {
            color: darkslategray;
            border-bottom: solid;
            border-bottom-color: darkslategrey;
            cursor: pointer;
        }

        .nav li:first-child {
            background-color: darkslategray;
        }

            .nav li:first-child:hover {
                color: #fff;
            }

    .nav .sub_nav li:first-child {
        background-color: grey;
    }


    .nav .sub_nav li:hover {
        color: moccasin;
    }

    .nav .nav_menuicon {
        padding-left: 10px;
        padding-right: 10px;
    }

    .nav .sub_nav li {
        display: block;
    }

    .nav li:hover .sub_nav { /* Từ thẻ li: cha hover cho nav con */
        display: block;
    }

    .nav .sub_nav {
        min-width: 248px;
        display: none;
        position: absolute; /*Là con của thẻ li: "More" */
        background-color: gray;
        color: #000;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); /* Tạo bóng cho box con*/
    }

/*-------------Trang chủ page----------------*/
.content_1 {
    background-color: #f1f1f1;
    height: 150px;
    margin-top: -20px;
    padding-top: 80px;
    text-align: center;
    word-spacing: 1.5px;
}

.content_2 {
    margin: 50px 0px;
}

    .content_2 li {
        height: 205px;
        text-align: center;
        margin-top: 30px;
        display: inline-block;
        font-weight: 500;
        font-size: 18px;
    }

        .content_2 li:first-child {
            margin-left: 10px;
        }

        .content_2 li:hover {
            border-color: #f1f1;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        }

.content_3 {
    margin: 50px 0px;
    height: 350px;
    background-color: #f1f1f1;
    padding: 20px 40px;
}

    .content_3 li {
        height: 300px;
        margin: 30px 30px;
        width: 240px;
        display: inline-block;
    }

    .content_3 ul:hover li:not(:hover) {
        filter: blur(5px);
    }

    .content_3 a {
        padding: 10px 10px;
        margin-top: -5px;
    }

    .content_3 a {
        display: block;
        color: aliceblue;
        background-color: darkslategrey;
    }

.content_4 {
    width: 100%;
    padding-top: 50px;
    margin-top: -50px;
    height: 500px;
    background-color: #f1f1f1;
    text-align: center;
}


    .content_4 li {
        padding: 10px 10px;
        text-align: left;
        display: inline-block;
        margin: 30px 20px;
    }

        .content_4 li:hover{
            background-color: #fff;
            scale: 250px;
            border-color: #ccc;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        }

    .content_4 .sub_ban {
        margin-left: 20px;
        width: 40%;
        background-color: cyan;
        border-bottom-right-radius: 80px 50px;
    }


    .content_4 #name_pro {
        font-weight: 550;
        font-size: 18px;
    }

    .content_4 #price_pro {
        text-decoration-line: line-through;
    }

    .content_4 #new_price {
        margin: 0px 10px;
        color: red;
        font-size: 17px;
        font-weight: 550;
    }

    .content_4 .btn_mua {
        text-transform: uppercase;
        font-weight: 400;
        font-size: 18px;
        word-spacing: 0.5px;
        color: #fff;
        border: 0;
        background-color: darkslategray;
        height: 40px;
        margin-top: 30px;
        width: 100%;
    }

        .content_4 .btn_mua:hover {
            font-size: 15px;
            background-color: #09ACB5;
        }

.content_5 {
    height: 80px;
    background-color: #09ACB5;
    display: flex;
}

    .content_5 #con5_text {
        display: flex;
        margin: 30px 50px;
        font-size: 19px;
        color: #fff;
    }

        .content_5 #con5_text h4 {
            margin-left: 10px;
        }

    .content_5 #con5_box {
        margin-top: 20px;
        margin-left: 400px;
        border: none;
    }
/*---------------Giới thiệu page---------------------*/
.tieude_gioithieu{
    margin: 30px 40px;
}

.gt_ct1 img{
    width: 100%;
}

.gt_ct2 {
    height: 100px;
}
    

/*---------------Tin tức page------------------------*/
.tieude_lienhe{
    margin: 30px 40px;
}

.tt_ct1{
    width: 100%;
    background-color: #fff;
    text-align: center;
}
.tt_ct1 li {
        text-align: left;
        width: 390px;
        margin: 15px 10px;
        display: inline-block;
    }

.tt_ct1 li h4{
    margin-top: 5px;
}
.tt_ct1 li h4:hover{
    color:grey;
    cursor:pointer;
}
.tt_ct1 li a{
    font-size:18px;
}

.list_page{
    margin:30px 0;
    font-size: 25px;
    text-align:center;
}

    .list_page a {
        color:grey;
        font-weight:530;
        margin: 0 20px;
    }

    .list_page a:first-child{
        color:#fff;
        background-color: grey;
    }

    .list_page a:hover{
        color: #fff;
        background-color: grey;
        cursor: pointer;
    }
/*---------------Liên hệ page------------------------*/

.lh_ct{
    height: 400px;
    display:flex;
}

.lh_ct1{
    margin-top: 50px;
    margin-left: 50px;
}

.lh_ct1 a{
    font-size: 18px;
}
.lh_icon {
    color: #09ACB5;
    font-weight: 550;
    font-size: 18px;
}

.lh_ct2 {
    margin-top: 70px;
    margin-left: 80px;
}

.lh_ct2 .lh_tenbox{
    margin: 10px 0;
    width: 100%;
    height: 30px;
}

    .lh_ct2 .lh_sdtbox {
        margin: 10px 0;
        width: 100%;
        height: 30px;
    }

    .lh_ct2 .lh_quesbox {
        
        margin: 10px 0;
        width: 100%;
        height: 100px;
    }

    .lh_ct2 .lh_btngui {
        border: 0;
        background-color: #09ACB5;
        color: #fff;
        width: 70px;
        height: 40px;
    }

    .lh_ct2 .lh_btngui:hover{
        background-color: grey;
    }
        /*---------------Danh mục sản phẩm-------------------*/
        
        /*---------------Footer------------------------------*/
        .footer {
            background-color: #f1f1f1;
            height: 600px;
        }

    .footer li {
        line-height: 22px;
        margin: 40px 40px;
        width: 240px;
        display: inline-block;
    }
