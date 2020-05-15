## khai báo thư viện
```
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="shortcut icon" type="image/png" href="https://i.imgur.com/ImB3e8A.png"/>
```
## định dạng style
```
<style>
  .fakeimg {
      height: 200px;
      background: #aaa;}
  .container{font-size:15px;}
  .container a{color:red;}
  .container p{font-size:15px;}
  .container p {margin-left:-20px;}
  .navbar-brand{margin-top:-20px;}
  .bg-danger {background-color: #772953!important;}
  .btn-group-lg>.btn, .btn-lg {
    padding: 10px 10px;
    font-size: 10px;
    line-height: 1.3333333;
    border-radius: 3px;
  }
  .navbar-dark .navbar-nav .nav-link {
    font-size: 15px;
    padding: 8px;
    color: rgba(255,255,255,.5);
}
.btn-info {
    color: #fff;
    background-color: #777;
    border-color: #6c757d;
  }
  .form-inline i {
    display: inline-block;
    width: auto;
    vertical-align: middle;
}
.form-inline .form-control {
    margin-left: 10px;
}
.glyphicon {
    FONT-VARIANT: JIS04;
    position: relative;
    top: 6px;
    display: inline-block;
    font-family: 'Glyphicons Halflings';
    line-height: 0px;
    font-size: 20px;
    -moz-osx-font-smoothing: grayscale;
}
.fa, .fas {
    font-weight: 520;
}
.btn-primary {
    color: #fff;
    background-color: #772953;
    border-color: #f8f9fa;
    margin-left: 500px;
}
.btn {
    padding: 8px;
    margin-bottom: 0px;
    border-radius: 4px;
}

.form-control{margin: 10px 0px 10px;}
.btn-success {
    color: #fff;
    background-color: #e95420;
    border-color: #e95420;
}
p{text-align:justify;}
.col
{
    position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 40px;
    padding-left: 15px;
    margin-left:5px;
}
.col a{color:#e95420;}
.col p{text-align:justify;margin-left:5px;}
</style>
```
## Code
```
<body>
<nav class="navbar navbar-expand-sm bg-danger navbar-dark">
<a class="navbar-brand" href="#"><img src="https://i.imgur.com/vO3tXIM.png" alt="Logo" style="width:40px;"></a>
  <ul class="navbar-nav">
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown"><i class="fas fa-building"></i>Giải pháp</a>
        <div class="dropdown-menu">
            <a class="dropdown-item" href="#"><i class="fas fa-briefcase"></i> Hệ thống thông tin doanh nghiệp</a>
            <a class="dropdown-item" href="#"><i class="fas fa-laptop	"></i> Phần mềm quản lý (SaaS)</a>
            <a class="dropdown-item" href="#"><i class="fas fa-shopping-cart"></i> Thương mại điện tử</a>
            <a class="dropdown-item" href="#"><i class="glyphicon glyphicon-phone"></i> App di động</a>
            <a class="dropdown-item" href="#"><i class="fas fa-bullhorn	"></i> Dịch vụ quảng cáo (Digital marketing)</a>
          </div>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown"><i class="fas fa-users"></i>Khách hàng</a>
      <div class="dropdown-menu">
        <a class="dropdown-item" href="#"><i class="fas fa-hotel"></i> Khách hàng IZHotel</a>
        <a class="dropdown-item" href="#"><i class="fas fa-briefcase"></i> Khách hàng</a>
      </div>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown"><i class="	fas fa-rss"></i>Thông tin</a>
      <div class="dropdown-menu">
        <a class="dropdown-item" href="#"><i class="fas fa-hotel"></i> Công nghệ</a>
        <a class="dropdown-item" href="#"><i class="fas fa-briefcase"></i> Thông tin chung</a>
        <a class="dropdown-item" href="#"><i class="fas fa-users"></i> Tuyển dụng</a>
      </div>
    </li>
    <li class="nav-item">
      <a class="nav-link active" href="#"><i class="fas fa-address-card"></i>Liên hệ</a>
    </li>
  </ul>
  <form class="form-inline" action="/action_page.php">
    <a href="#" class="btn btn-primary">
      <i class='fas fa-language' style='font-size:20px;color:rgba(255, 255, 255, 0.5);'> VI</i>
    </a>
    <input class="form-control mr-sm-2" type="text" placeholder="Search">
    <a href="#" class="btn btn-info btn-lg"><span class="glyphicon glyphicon-search"></span></a>
  </form>
</nav>
<br/>
<div class="container">
    <div class="jumbotron py-3" style="margin-bottom:0;">
        <h2 style="margin-left:-20px;">VNAppMob</h2>
        <p><i class="fas fa-map-marker fa-fw"></i>VietNam</p>
        <p><i class="fas fa-phone"></i>+84965235237</p>
        <p><i class="fas fa-envelope fa-fw"></i><a href="mailto:contact@vnappmob.com">contact@vnappmob.com</a></p>
    </div>
    <br/>
    <div class="row">
        <div class="col-sm-4">
            <form action="/action_page.php">
                <div class="form-group">
                  <div class="col-sm-14">
                    <div class="card bg-light">
                      <div class="card-header"><i class="fas fa-edit"></i>Leave your note</div>
                      <div class="card-body text-center">  
                        <div class="col-sm-6"><input type="text" class="form-control" placeholder="*Name/Company" id="name"></div>
                        <div class="col-sm-6"><input type="number" class="form-control" placeholder="*Phone" id="phone"></div>    
                        <div class="col-sm-12"><input type="text" class="form-control" placeholder="Email" id="email"></div>
                        <div class="col-sm-12"><input type="text" class="form-control" placeholder="Address" id="address"></div>
                        <div class="col-sm-12"><textarea class="form-control" placeholder="*Leave your note here" rows="5"></textarea></div>
                        <div class="col-sm-2"><button type="button" class="btn btn-success">Send</button></div>
                      </div>
                    </div>
                  </div> 
                </div>
            </form>
        </div>
        <div class="col-sm-8">
          <div class="card bg-light">
            <div class="card-header"><i class="fas fa-map"></i>Map to us</div>
            <div class="card-body1">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3918.8575610708003!2d106.68530841411678!3d10.82221066130785!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3174deb3ef536f31%3A0x8b7bb8b7c956157b!2zVHLGsOG7nW5nIMSQ4bqhaSBo4buNYyBDw7RuZyBuZ2hp4buHcCBUUC5IQ00!5e0!3m2!1svi!2s!4v1589526128038!5m2!1svi!2s" width="728" height="357" frameborder="0"  allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
            </div>
          </div>
        </div>
    </div>
    <hr  width="100%" align="center" size="20px" />
    <div class="row">
        <div class="col"><h2>Giới thiệu</h2>
            <p>Tại VNAppMob, chúng tôi sẽ mang đến những giải pháp tiên tiến về phần mềm quản lý, thương mại điện tử, xây dựng hệ thống website doanh nghiệp, ứng dụng di động... giúp doanh nghiệp của bạn sẵn sàng tiến vào cuộc cách mạng công nghệ 4.0</p>
        </div>
        <div class="col"><h2>Liên hệ</h2>
            <strong>VNAppMob</strong>
            <p><i class="fa fa-map-marker fa-fw"></i> VietNam</p>
            <p><i class="fa fa-phone fa-fw"></i> +84965235237</p>
            <p><i class="fa fa-envelope fa-fw"></i> contact@vnappmob.com</p>
        </div>
        <div class="col"><h2>Thông tin</h2>
            <p><a href="#">Tình trạng máy chủ</a></p>
            <p><a href="#">Điều khoản sử dụng</a></p>
            <p><a href="#">Chính sách bảo mật thông tin</a></p>
            <p><a href="#">Thông tin tuyển dụng</a></p>
        </div>
        <div class="col"><h2>Kết nối</h2>
            <p><a href="https://www.facebook.com/vnappmob.co/">VNAppMob</a></p>
            <p>Chỗ này em không biết chèn</p>
        </div>
    </div>
    <hr  width="100%" align="center" size="20px" />
    <p style="text-align:center;">Powered by <a href="https://web.vnappmob.com/">VNAppMob</a></p>
</div>
</body>
```