<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>figma</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/all.min.css">
    <link rel="stylesheet" href="css/fonts.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    
    
    <header class="header">
        <div class="header__block-nav">
            <div class="container">
                <div class="header__block-ul">
                    <ul class="header__ul">
                        <li><a class="header__ul-a" href="#">рус</a></li>
                        <li><a class="header__ul-a" href="#">eng</a></li>
                        <li><a class="header__ul-a" href="#">fl</a></li>
                    </ul>
                    <a class="header__email" href="#">8 (800) 123-45-67</a>
                    <a class="header__email header__email-madia" href="#">sales@log.ru</a>
                </div>
                
            </div>
            
        </div>
        <div class="header__menu">
            <div class="container">
                <nav class="navbar navbar-expand-lg navbar-light header__navbar">
                    <div class="container-fluid">
                      <a class="header__logo" href="#"><img src="img/logo.png" alt=""> <span class="header__hr"></span> <img src="img/placeholder.png" alt=""> <span class="header__logo-span">Наши офисы</span></a>
                      
                      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="fas fa-caret-down"></span>
                      </button>
                      
                      <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                            
                          <li class="nav-item">
                            <a class="header__nav-link active" aria-current="page" href="#">услуги</a>
                          </li>
                          
                          <li class="nav-item">
                            <a class="header__nav-link" href="#">О компании</a>
                          </li>
                          <li class="nav-item">
                            <a class="header__nav-link" href="#">вакансии</a>
                          </li>
                          <li class="nav-item">
                            <a class="header__nav-link" href="#">контакты</a>
                          </li>
                         
                        </ul>
                    
                      </div>
                    </div>
                  </nav>
            </div>
        </div>
        <div class="header__text">
            <div class="container">
                <div class="row justify-content-center text-center">
                    <div class="col-lg-9">
                        <div class="header__text-box">
                            <h1 class="header__text-title">Грузовые перевозки</h1>
                            <p class="header__text-p">Перевозка крупногабаритных грузов по России и Европе. Полное экспедирование, страхование, упаковка и хранение грузов</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    
    <section class="section__slider">
      <div class="container">
        <div class="row">
          
          <div class="col-lg-10 col-md-10 col-sm-12">
            <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
              <div class="carousel-inner">
                
                <div class="carousel-item active">
                   <div class="row  justify-content-between">
                     
                     <div class="col-lg-5 col-12 d-flex flex-column align-items-start">
                       <h2 class="section__slider-title">грузоперевозки
                        по европе</h2>
                       <p class="section__slider-p">Страны Евросоюза, а также Украина,
                        Белоруссия со всеми документами.</p>
                       <a class="section__slider-link" href="#">ПОДРОБНЕЕ</a>
                     </div>
                     
                     <div class="col-lg-5 col-12">
                       <img class="section__slider-img" src="img/slider-1.png" alt="">
                     </div>
                     
                   </div>
                </div>
                
                <div class="carousel-item">
                  <div class="row justify-content-between">
                     
                    <div class="col-lg-5 d-flex flex-column align-items-start">
                      <h2 class="section__slider-title">грузоперевозки
                       по европе</h2>
                      <p class="section__slider-p">Страны Евросоюза, а также Украина,
                       Белоруссия со всеми документами.</p>
                      <a class="section__slider-link" href="#">ПОДРОБНЕЕ</a>
                    </div>
                    
                    <div class="col-lg-5">
                      <img class="section__slider-img" src="img/slider-1.png" alt="">
                    </div>
                    
                  </div>
                </div>
                
                <div class="carousel-item">
                  <div class="row justify-content-between">
                     
                    <div class="col-lg-5 d-flex flex-column align-items-start">
                      <h2 class="section__slider-title">грузоперевозки
                       по европе</h2>
                      <p class="section__slider-p">Страны Евросоюза, а также Украина,
                       Белоруссия со всеми документами.</p>
                      <a class="section__slider-link" href="#">ПОДРОБНЕЕ</a>
                    </div>
                    
                    <div class="col-lg-5">
                      <img class="section__slider-img" src="img/slider-1.png" alt="">
                    </div>
                    
                  </div>
                </div>
                
              </div>
          
            </div>
          </div>
          
          
          <div class="col-lg-2  col-md-2 col-sm-12 d-flex flex-column justify-content-between">
            
            <button class="section__slider-button" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
              <span class="fal fa-long-arrow-left section__icon" aria-hidden="true"></span>
             
              <span class="visually-hidden">Previous</span>Назад
            </button>
            
            <button class="section__slider-button" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">след
              <span class="fal fa-long-arrow-right  section__icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
            
          </div>
          
          
        </div>
      </div>
    </section>
    
    <section class="section__img"> 
      <div class="container">
        <h3 class="section__img-title">услуги</h3>
        
        <div class="row">
          
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          <div class="col-lg-3 col-md-3 col-6 section-col">
            <a class="section__icons" href="#">
              
              <div class="icon__box">
                <i class="fas fa-fighter-jet"></i>
              </div>
              
              <p class="section__icons-p">Авиаперевозки</p>
              
            </a>
          </div>
          
        </div>
        
      </div>
    </section>
    
    
    <section class="section__about">
      <div class="container">
        <div class="row justify-content-between">
          
          <div class="col-lg-5">
            <h3 class="section__about-title">О компании</h3>
            <p class="section__about-p">Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века. В то время некий безымянный печатник создал большую коллекцию размеров и форм шрифтов, используя Lorem Ipsum для распечатки образцов. Lorem Ipsum не только успешно пережил без заметных изменений пять веков, но и перешагнул в электронный дизайн.</p>
          </div>
          
          <div class="col-lg-6">
            <div class="row">
              <div class="col-lg-4 about__col">
                <div class="about__box">
                  <h4 class="about__box-title">48</h4>
                  <p class="about__box-p1">офисов</p>
                  <p class="about__box-p2">В Европе и СНГ</p>
                </div>
              </div>
              <div class="col-lg-4 about__col">
                <div class="about__box">
                  <h4 class="about__box-title">361</h4>
                  <p class="about__box-p1">грузовиков</p>
                  <p class="about__box-p2">Volvo, Scania</p>
                </div>
              </div>
              <div class="col-lg-4 about__col">
                <div class="about__box about-img">
                 
                </div>
              </div>
              <div class="col-lg-4 about__col">
                <div class="about__box about_img">
                  <h4 class="about__box-title"></h4>
                  <p class="about__box-p1"></p>
                  <p class="about__box-p2"></p>
                </div>
              </div>
              <div class="col-lg-4 about__col">
                <div class="about__box">
                  <h4 class="about__box-title">1500</h4>
                  <p class="about__box-p1">сотрудников</p>
                  <p class="about__box-p2">профессионалов</p>
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </section>

    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d47772.46863012438!2d60.58805427375603!3d41.55237583772626!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x41dfc9284eafb523%3A0xffaf4382f65d7b61!2sUrganch%2C%20O%60zbekiston!5e0!3m2!1suz!2s!4v1616937694128!5m2!1suz!2s" width="100%" height="500" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    

    <footer>
      <div class="container">
        <div class="row justify-content-between">
          <div class="col-lg-3 col-md-6 col-sm-6">
            <img src="img/logo.png" alt="">
          </div>
          
          <div class="col-lg-2 col-md-6 col-sm-6">
            <p>123456, Санкт-Петербург, Невский пр-кт 127</p>
            <p>sales@log.ru</p>
          </div>
          
          <div class="col-lg-4 col-12">
            <div class="row">
              <div class="col-lg-4 col-md-4 col-sm-4">
                <ul>
                  <li><a href="">+7 (812) 344-56-65</a></li>
                  <li><a href="">+7 (812) 355-56-65</a></li>
                  <li><a href="">Разработано - D-E-N.ru</a></li>
                 
                </ul>
              </div>
            </div>
          </div>
          
        </div>
      </div>
    </footer>
    
    <script src="js/bootstrap.esm.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
</body>
</html>
