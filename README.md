# web-sitem
<!DOCTYPE html>
<html lang="tr">

<head>
    <title>Görkem karaca- Kişisel Web Sitesi</title>
    <meta charset="UTF-8">
    <meta name="description" content="Görkem karaca - Kişisel Web Sitesi">
    <meta name="keywords" content="grkem karaca">
    <meta name="author" content="Görkem karaca">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
    <script src="js/jquery-3.7.1.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>
        body {
            font: 20px Montserrat, sans-serif;
            line-height: 1.8;
            color: #f5f6f7;
        }
        
        p {
            font-size: 16px;
        }
        
        .margin {
            margin-bottom: 45px;
        }
        
        .bg-1 {
            background-color: #156ed4;
            /* Green */
            color: #333333;
            /* black */
            
            
            
        }
        
        .bg-2 {
            background-color: #474e5d;
            /* Dark Blue */
            color: #ffffff;
        }
        
        .bg-3 {
            background-color: #ffffff;
            /* White */
            color: #555555;
        }
        
        .bg-4 {
            background-color: #4C3173;
            /* Blue Diamond */
            color: #fff;
        }
        
        .bg-5 {
            background-color: #ecebe8;
            /* Gray */
            color: #333;
        }
        
        .container-fluid {
            padding-top: 70px;
            padding-bottom: 70px;
        }
        
        .navbar {
            padding-top: 15px;
            padding-bottom: 15px;
            border: 0;
            border-radius: 0;
            margin-bottom: 0;
            font-size: 12px;
            letter-spacing: 5px;
        }
        
        .navbar-nav li a:hover {
            color: #4C3173 !important;
        }
        .img{
            border-radius: 500px;
        }
        
    </style>
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-default">
        <div class="container">
            <div class="navbar-header">
                
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                >
                <a class="navbar-brand" href="#">Görkem karaca</a>
               
            </div>,<nav class="navbar bg-white border-bottom border-body" data-bs-theme="White">
                
                  
                        <li><a href="#kimdir">Kimdir?</a></li>
                        <li><a href="#neyapar">Ne yapar?</a></li>
                        <li><a href="#blog">Blog</a></li>
                        <li><a href="#iletisim">İletişim</a></li>
                  
                </div>
            </div>
              </nav>
            
    </nav>

    <!-- First Container -->
    <div id="kimdir" class="container-fluid bg-1 text-center">
        <h3 class="margin">Merhaba, Ben Görkem!</h3>
        <img src="Yeni bilgisayar/profil2.PNG" class="img" alt="..." >
        <h3>Yazılım Geliştiririm</h3>
    </div>

    <!-- Second Container -->
    <div id="neyapar" class="container-fluid bg-2 text-center">
        <h3 class="margin">Neler Yaparım?</h3>
        
        <p>yazılım geliştirme bölümünde okuyorum genellikle kod yazarım.
            Yeni bişeyler keşfetmeyi severim.
            Spor yapmayı severim.. 
        </p>
    </div>



        

    <!-- Third Container (Grid) -->
    <div id="blog" class="container-fluid bg-3 text-center">
        <h3 class="margin">Blog</h3>
        <br>
        <div class="row">
            <div class="col-sm-4">
                <p>Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, dağıtık çalışan bir sürüm kontrol ve kaynak kod yönetim sistemidir.</p>
                <img src="git.jpg" class="img-responsive margin" style="width:100%" alt="git">
            </div>
            <div class="col-sm-4">
                <p>HTML, Hiper Metin İşaretleme Dili (Hypertext Markup Language) web sayfalarını oluşturmak için kullanılan metin işleme dilidir.</p>
                <img src="html5.jpg" class="img-responsive margin" style="width:100%" alt="html">
            </div>
            <div class="col-sm-4">
                <p>Python bir programlama dilidir. Diğer programlama dillerinde olduğu gibi bilgisayarlara hükmetmeyi sağlar. </p>
                <img src="python.jpg" class="img-responsive margin" style="width:100%" alt="python">
            </div>
            <div class="col-sm-4">
                <p> geliştirme döngüsünün tamamını tek bir yerde tamamlamak için kullanabileceğiniz güçlü bir geliştirici aracıdır. </p>
                <img src="images.png" class="img-responsive margin" style="width:100%" alt="python">
            </div>
            <div class="col-sm-4">
                <p>web tabanlı bir sürüm kontrol sistemi ve kod deposu platformudur. </p>
                <img src="github.png" class="img-responsive margin" style="width:100%" alt="python">
            </div>
            <div class="col-sm-4">
                <p>Android sistemi üzerinden uygulama geliştirmeye yarayan platforma denir. </p>
                <img src="android studio.jpeg" class="img-responsive margin" style="width:100%" alt="python">
            </div>
        </div>
    </div>

    <!-- Contact -->
    <div id="iletisim" class="container-fluid bg-5 text-center">
        <h3 class="margin">İletişim sayfasına hoşgeldiniz</h3>
        <br>
        <div class="row ">
            <div class="col-sm-5 text-left">
                <p>Merhaba demek ister misin?</p>
                <p><span class="glyphicon glyphicon-map-marker"></span> balıkesir, TR</p>
                <p><span class="glyphicon glyphicon-phone"></span> 05370259985</p>
                <p><span class="glyphicon glyphicon-envelope"></span> gorkemkaraca@gmail.com</p>
            </div>
            <form>
                <div class="mb-3">
                  <label for="exampleInputEmail1" class="form-label">Eposta adresi</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                  <div id="emailHelp" class="form-text">Eposta'nızı asla başkasıyla paylaşmayacağız.</div>
                </div>
                <div class="mb-3">
                  <label for="exampleInputPassword1" class="form-label">Şifre</label>
                  <input type="password" class="form-control" id="exampleInputPassword1">
                </div>
                <div class="mb-3 form-check">
                  <input type="checkbox" class="form-check-input" id="exampleCheck1">
                  <label class="form-check-label" for="exampleCheck1">Beni kontrol et</label>
                </div>
                <button type="submit" class="btn btn-primary">Gönder</button>
              </form>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/bootstrap.bundle.js"></script>

</body>

</html>
