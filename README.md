<?php 
  error_reporting(0);
  session_start();	
  include "config/koneksi.php";
	include "config/fungsi_indotgl.php";
	include "config/class_paging.php";
	include "config/fungsi_combobox.php";
	include "config/library.php";
  include "config/fungsi_autolink.php";
  include "config/fungsi_rupiah.php";
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="">
    <title> <?php include "dina_titel.php";?></title>
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/font-awesome.min.css" rel="stylesheet">
    <link href="css/prettyPhoto.css" rel="stylesheet">
    <link href="css/price-range.css" rel="stylesheet">
    <link href="css/animate.css" rel="stylesheet">
	<link href="css/main.css" rel="stylesheet">
	<link href="css/responsive.css" rel="stylesheet">
    <!--[if lt IE 9]>
    <script src="js/html5shiv.js"></script>
    <script src="js/respond.min.js"></script>
    <![endif]-->       
    <link rel="shortcut icon" href="images/ico/favicon.ico">
    <link rel="apple-touch-icon-precomposed" sizes="144x144" href="images/ico/apple-touch-icon-144-precomposed.png">
    <link rel="apple-touch-icon-precomposed" sizes="114x114" href="images/ico/apple-touch-icon-114-precomposed.png">
    <link rel="apple-touch-icon-precomposed" sizes="72x72" href="images/ico/apple-touch-icon-72-precomposed.png">
    <link rel="apple-touch-icon-precomposed" href="images/ico/apple-touch-icon-57-precomposed.png">
</head><!--/head-->

<body>

<div class="header_top">
  <!--header_top-->
  <div class="container">
    <div class="row">
      <div class="col-sm-6">
        <div class="contactinfo">
          <ul class="nav nav-pills">
            <li><a href="#"><i class="fa fa-phone"></i> &nbsp; Telp. (022) 877 98434</a></li>
            <li><a href="#"><i class="fa fa-envelope"></i> &nbsp; Email. info@sabaraya.co.id</a></li>
            <li></li>
          </ul>
        </div>
      </div>
      <div class="col-sm-6">
        <div class="social-icons pull-right">
          <ul class="nav navbar-nav">
          
            <li><a href="#"><i class="fa fa-facebook"></i></a></li>
            <li><a href="#"><i class="fa fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
            <li><a href="#"><i class="fa fa-dribbble"></i></a></li>
            <li><a href="#"><i class="fa fa-google-plus"></i></a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
	    <td height="3" bgcolor="#0066CC"></td>
  </tr>
</table>

<div class="container">
  <div class="row">
    
  </div>
</div>
<div class="header-middle">
  <!--header-middle-->
  <div class="container">
    <div class="row">
      <div class="col-sm-4">
        <div class="logo pull-left"> <a href="index.php"><img src="images/logo.png" alt="" /></a> </div>
      </div>
      <div class="col-sm-8">
        <div class="shop-menu pull-right">
          <ul class="nav navbar-nav">
            <div align="center">
            <div class="panel panel-default">
              <div class="panel-heading">
                              <div class="top_search">
	            <form method='post' action="hasil-pencarian.html" class="searchform">
	              
	                <input type="text" name='kata' placeholder=" Search Products ...." />
           
	              <button type="submit" class="btn btn-default"><i class="fa fa-arrow-circle-o-right"></i></button
				        >
                </form>
            </div>
              </div>
            </div>
          </div>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>

<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td height="70" bgcolor="#e9e7e8"><div class="container">
      <div class="row">
        <div class="col-sm-9">
          <div class="navbar-header">
            <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse"> <span class="sr-only">Toggle navigation</span> <span class="icon-bar"></span> <span class="icon-bar"></span> <span class="icon-bar"></span></button>
          </div>
          <div class="mainmenu pull-left">
            <ul class="nav navbar-nav collapse navbar-collapse">
              <li><a href="index.php" >Home</a></li>
              <li class="dropdown"><a href="#">About Us<i class="fa fa-angle-down"></i></a>
                <ul role="menu" class="sub-menu">
                  <li><a href="profil-kami.html">Company Profile</a></li>
                  <li><a href="kerjasama.php">Business Partners</a></li>
                  

                </ul>
              </li>
              
              <li class="dropdown"><a href="#">Services<i class="fa fa-angle-down"></i></a>
                <ul role="menu" class="sub-menu">
<li><a href="konfirmasi.php">Payment Confirmation</a></li>
                                <li><a href="cara-pembelian.html">How To Buy</a></li>
                                <li><a href="pengiriman.php">Shipping Method</a></li>
                  

                </ul>
              </li>
      <li><a href="semua-produk.html">Products</a></li>
        
              <li><a href="download-katalog.html">Download</a></li>
              <li><a href="hubungi-kami.html">Contact Us</a></li>
              
              
              
            </ul>
          </div>
      </div>
      </div>
    </div></td>
  </tr>
  <tr>
	    <td height="10" bgcolor="#0066CC"></td>
  </tr>
</table>
<section id="slider">
  <!--slider-->
  <div class="container">
    <div class="row">
      <div class="col-sm-12">
        <div id="slider-carousel" class="carousel slide" data-ride="carousel">
          <div class="carousel-inner">
            <div class="item active">
              <div class="col-sm-6">
                <h1><span>Sabaraya</span>&nbsp;Store</h1>
                <h2>BC2800 - Mindray</h2>
                <p>The BC-2800 Vet is a compact, fully automatic hematology analyzer with 19 parameters for CBC testing and micro sampling technology. The user-friendly interface makes for easy and efficient workflow</p>
                <button type="button" class="btn btn-default get">Buy products</button>
              </div>
              <div class="col-sm-6"> <img src="images/home/slide1.jpg" class="girl img-responsive" alt="" /> </div>
            </div>
            <div class="item">
              <div class="col-sm-6">
                <h1><span>Sabaraya</span>&nbsp;Store</h1>
                <h2>RD60 - ReiGed Diagnostics</h2>
                <p>RD-60, is equipped with a photometer Incubator, a high degree of stability. the test program up to 199 different types. </p>
                <button type="button" class="btn btn-default get">Buy Products</button>
              </div>
              <div class="col-sm-6"> <img src="images/home/slide2.jpg" class="girl img-responsive" alt="" /> </div>
            </div>
           
            
            <div class="item">
              <div class="col-sm-6">
                <h1><span>Sabaraya</span>&nbsp;Store</h1>
                <h2>BT1500 - Biotecnica Indonesia</h2>
                <p>Random Access Biochemistry analyzer BT-1500, test speed of 250 tests per hour, equipped with a refrigerator to deposit reagent.Tough, accurate and economical.</p>
                <button type="button" class="btn btn-default get">Buy Products</button>
              </div>
              <div class="col-sm-6"> <img src="images/home/slide3.jpg" class="girl img-responsive" alt="" /> </div>
            </div>
          </div>
          <a href="#slider-carousel" class="left control-carousel hidden-xs" data-slide="prev"> <i class="fa fa-angle-left"></i> </a> <a href="#slider-carousel" class="right control-carousel hidden-xs" data-slide="next"> <i class="fa fa-angle-right"></i> </a> </div>
      </div>
    </div>
  </div>
</section>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
	    <td height="91" background="images/bg.png"><div align="center"><strong><font color="#FFFFFF" ><h3>The Online Medical Devices Exhibition</h3>
	      <p>&nbsp;</p>
    </font></strong></div></td>
  </tr>
</table>
	<!--/slider-->
	<section>
		<div class="container">
			<div class="row"></div>
		</div>
	</section>
	<div class="container">
	  <div class="row">
	    <p>&nbsp;</p>
	    <div class="col-sm-3">
	      <div class="left-sidebar">
         
          <div align="left">
            <h4><img src="images/logo ssm tosada.jpg"></h4>
            <h4><br>
            </h4>
            <p><strong><font color='#0066cc'>HEAD OFFICE</font> </strong><br>
             <p> Kompleks P.U Jl. Sapta Taruna VI<br>
              Blok A.5 No. 8 Cipagalo Buah Batu<br>
            Bandung - Jawa Barat, Indonesia<br><br>
            </p>
            <p><strong><font color='#0066cc'>CUSTOMER SERVICES</font></strong></p>
            <p>Telp. : (022) 877 98434<br>
              Sites : www.sabaraya.co.id<br>
            Email : info@sabaraya.co.id <br>
            </p>
 
<h4>&nbsp;</h4>
<h4>&nbsp;</h4>
<h4><br>       
</h4>
          </div>
          <div class="brands_products">          </div>
	        <!--/brands_products-->
	      
	        <!--/price-range-->
	        <!--/shipping-->
          </div>
        </div>
	    <div class="col-sm-9 padding-right">
	      <div class="features_items">
	        <h4><font color='#0066cc'><b>PT. SABARAYA SAGARA MANDIRI</b></font></h4>
	      </div>

	      <!--features_items-->
	      <div>
	        <div>
	          <p align="justify">&nbsp;</p>
	          <div id="gt-res-content">
	            <div dir="ltr">
	              <div align="justify">
	                <p>CV. Tosada Beta Prima didirikan pada tahun 2010 sebagai sebuah perusahaan swasta di Bandung. Bisnis utamanya adalah penjualan dan pemasaran, terutama pada Patologi Klinik, Patologi Anatomi dan Laboratorium Klinik Produk. Sekarang di tahun 2015, CV. Tosada Beta Prima telah beralih nama menjadi PT. Sabaraya  Sagara Mandiri, yang juga merupakan perusahaan yang bergerak dibidang yang sama yakni melayani kebutuhan pelanggan,   terutama di pusat-pusat penelitian, rumah sakit dan laboratorium,   universitas, dan Bank Darah. Tujuan utama kami adalah kepuasan pelanggan dengan menyediakan   produk-produk berkualitas tinggi, pengiriman yang cepat dan harga yang   kompetitif.<br>
                      <br>
Sejak awal, Sabaraya telah mengabdikan diri untuk penjualan dan pelayanan peralatan medis. Sekarang kita memiliki hak kekayaan intelektual dan produk pengetahuan yang lengkap. Berkat kualitas produk yang sangat baik dan teknologi canggih yang   digunakan dalam semua produk, kami telah mendapat kepercayaan dari   beberapa lembaga seperti rumah sakit, laboratorium, Universitas, dan   lain-lain.<br>
<br>
Demi mewujudkan visi kami, kami akan terus berusaha menjadi perusahaan yang paling profesional dan   dihormati di bidang medis, kami akan bersikeras memberikan layanan   terbaik kepada klien kami dengan produk hemat biaya yang luar biasa.</p>
	              </div>
	            </div>
              </div>
	          <p align="justify">&nbsp;</p>
	          <p align="justify">&nbsp;</p>
	          <p align="justify">&nbsp;</p>
	          <h4 align="center"><font color='#0066cc'><b>BRANDS &amp; PRODUCTS</b></font></h4>
	          <p align="center">Imternational and local brands</p>
	          <p align="center">&nbsp;</p>
	        </div>
          </div>
	      <div class="recommended_items">
	        <!--recommended_items-->
	        <div id="recommended-item-carousel" class="carousel slide" data-ride="carousel">
	          <div class="carousel-inner">
	            <div class="item active">
	              <div align="center"><img src="images/brand/biotecnica.jpg" ><img src="images/brand/rayto.jpg" ><img src="images/brand/reiged.jpg" ><img src="images/brand/Untitled-1.jpg" ></div>
                </div>
	            <div class="item">
	              <div align="center"><img src="images/brand/biogenex.jpg" ><img src="images/brand/biooptica.jpg" ><img src="images/brand/oncoprobe.jpg" ><img src="images/brand/histoline.jpg" ></div>
                </div>
              </div>
            </div>
          </div>
	      <p>&nbsp;</p>
	    </div>
	    <p>&nbsp;</p>
	  </div>
</div>
<div class="container">
	  <div class="row"></div>
</div>
<table width="100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
	    <td height="10" bgcolor="#0066CC"></td>
  </tr>
</table>
<footer id="footer"><!--Footer-->
  <div class="footer-top"></div>
	  <div class="footer-widget">
	    <div class="container">
	      <div class="row">
	        <div class="col-sm-2">
	          <div class="single-widget">
	            <h2>Service</h2>
	            <ul class="nav nav-pills nav-stacked">
	              <li><a href="hubungi-kami.html">Contact Us</a><a href="konfirmasi.php">Payment Confirm</a></li>
	              <li><a href="cara-pembelian.html">How To Buy</a></li>
	              <li><a href="pengiriman.php">Shipping Method</a></li>
                </ul>
              </div>
            </div>
	        <div class="col-sm-2">
	          <div class="single-widget">
	            <h2>COMPANY</h2>
	            <ul class="nav nav-pills nav-stacked">
	              <li><a href="profil-kami.html">About Company</a></li>
	              <li><a href="kerjasama.php">Business Partners</a><a href="map.php">Map Location</a></li>
                </ul>
              </div>
            </div>
	        <div class="col-sm-2">
	          <div class="single-widget">
	            <h2>Policies</h2>
	            <ul class="nav nav-pills nav-stacked">
	              <li><a href="syarat-ketentuan.php">Terms of Use</a></li>
	              <li><a href="kebijakan-privasi.php">Privecy Policy</a></li>
	              <li><a href="keamanan.php">Store Security</a> <a href="jaminan.php">Guarantee </a></li>
                </ul>
              </div>
            </div>
	        <div class="col-sm-2">
	          <div class="single-widget">
	            <h2>NETWORK</h2>
	            <ul class="nav nav-pills nav-stacked">
	              <li><a href="#">Facebook</a></li>
	              <li><a href="#">Twitter</a></li>
	              <li><a href="#">Instagram</a></li>
	              <li><a href="#">Google +</a></li>
                </ul>
              </div>
            </div>
	        <div class="col-sm-2">
	          <div class="single-widget">
	            <h2><img src="images/map.png" alt="" width="295" height="154">                </h2>
              </div>
            </div>
          </div>
        </div>
	  </div>
	  <div class="footer-bottom">
		  <div class="container">
		    <div class="row">
		      <p class="pull-left">   <strong>PT. SABARAYA SAGARA MANDIRI</strong> © 2015. All Rights Reserved |  Developed by.<a href="#"><em> Aurahoster Intermedia</em></a><em></em></p>
		      <p class="pull-right">&nbsp;</p>
	        </div>
        </div>
  </div>
</footer><!--/Footer-->
	

  
    <script src="js/jquery.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="js/jquery.scrollUp.min.js"></script>
	<script src="js/price-range.js"></script>
    <script src="js/jquery.prettyPhoto.js"></script>
    <script src="js/main.js"></script>
</body>
</html>
