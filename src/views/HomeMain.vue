<template>
  <div class='homemain'>
    <!-- Navigation -->
    <nav class='navbar navbar-expand-md navbar-light bg-light sticky-top'>
      <div class='container-fluid'>
        <a class='navbar-brand' href='#'>
          <img src='../assets/softTechVVVSM.jpg' />
        </a>
        <button
          class='navbar-toggler'
          type='button'
          data-toggle='collapse'
          data-target='#navbarResponsive'
        >
        <span class='navbar-toggler-icon'></span>
        </button>
        <div class='collapse navbar-collapse' id='navbarResponsive'>
          <ul class='navbar-nav ml-auto'>
            <li class='nav-item'>
              <a class='nav-link' href='#'>نسيان كلمة المرور</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#'>دخول</a>
            </li>

            <li class='nav-item'>
              <a class='nav-link' href='#'>لوحة العرض</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#'>الطلبات</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#'>تسجيل شركات</a>
            </li>
            <li class='nav-item'>
              <a class='nav-link' href='#'>تسجيل صيدليات</a>
            </li>
            <li class='nav-item active'>
              <a class='nav-link' href='#'>الرئيسية</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Image  -->
    <!--<b-container fluid>
      <img center src='../assets/background1.jpg' class='d-block w-100' alt='Center image' />
      <div class='centered'>
        <h3 class='display-2'>New Products</h3>
        <button type='button' class='btn btn-outline-light btn-lg'>View New Products</button>
      </div>
    </b-container>-->

    <!-- Image Slider -->
  <div id='slides' class='carousel slide' data-ride='carousel'>
    <ul class='carousel-indicators'>
      <li data-target='#slides' data-slide-to='0' class='active'></li>
      <li data-target='#slides' data-slide-to='1'></li>
      <li data-target='#slides' data-slide-to='2'></li>
    </ul>
    <div class='carousel-inner'>
      <div class='carousel-item active'>
        <img src='../assets/background4.jpg' style='width:1300px;height:360px'>
        <div class='carousel-caption'>
          <h1 class='display-2'>New Products</h1>
          <p>أضغط هنا للأإطلاع على أخر المعلومات عن الأدوية المجازة من وزارة الصحة الإتحادية.</p>
          <button type='button' class='btn btn-outline-light btn-lg'>View New Products</button>
        </div>
      </div>
      <div class='carousel-item'>
        <img src='../assets/background5.jpg' style='width:1300px;height:360px'>
        <div class='carousel-caption'>
          <h1 class='display-2'>Second slide label</h1>
          <h3>أضغط هنا للأإطلاع على أخر المعلومات عن الأدوية المجازة من وزارة الصحة الإتحادية.</h3>
        </div>
      </div>
      <div class='carousel-item'>
        <img src='../assets/background6.jpg' style='width:1300px;height:360px'>
        <div class='carousel-caption'>
          <h1 class='display-2'>Third slide label</h1>
          <h3>أضغط هنا للأإطلاع على أخر المعلومات عن الأدوية المجازة من وزارة الصحة الإتحادية.</h3>
        </div>
      </div>
    </div>
    <a class='carousel-control-prev' href='#slides' role='button' data-slide='prev'>
      <span class='carousel-control-prev-icon' aria-hidden='true'></span>
      <span class='sr-only'>Previous</span>
    </a>
    <a class='carousel-control-next' href='#slidess' role='button' data-slide='next'>
      <span class='carousel-control-next-icon' aria-hidden='true'></span>
      <span class='sr-only'>Next</span>
    </a>
  </div>
    <!-- Jumbotron -->
    <div class='container-fluid'>
      <div class='row jumbotron'>
        <div class='col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-2'>
          <a href='#'>
            <button type='button' class='btn btn-outline-light btn-lg'>للتوصيل</button>
          </a>
        </div>
        <div class='col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-10'>
          <p class='lead'>يمكن تقديم خدمة التوصيل فقط عليك الإتصال بنا لعمل اللازم</p>
        </div>
      </div>
    </div>
    <!-- Welcome Section -->
    <b-container fluid padding>
      <div class='row welcome text-center'>
        <div class='col-12'>
          <h1 class='display-4'>Built For Your Business</h1>
        </div>
        <hr />
        <div class='col-12'>
          <p class='lead'>مرحب بك في هذا الموقع لتسيل عملك</p>
        </div>
      </div>
    </b-container>
    <!-- Three Column Section -->
    <b-container fluid padding>
      <div class='row text-center padding'>
        <div class='col-xs-12 col-sm-6 col-md-4'>
          <i class='fas fa-code'></i>
          <h3>HTML</h3>
          <p>Built with the lates technology HTML5</p>
        </div>
        <div class='col-xs-12 col-sm-6 col-md-4'>
          <i class='fas fa-bold'></i>
          <h3>BOOTSTRAP</h3>
          <p>Built with the lates technology Bootstrap</p>
        </div>
        <div class='col-sm-12 col-md-4'>
          <i class='fab fa-css3'></i>
          <h3>CSS3</h3>
          <p>Built with the lates technology HTML5</p>
        </div>
      </div>
      <hr class='my-4' />
    </b-container>
    <!-- Two Column Section -->
    <b-container fluid padding>
      <div class='row padding'>
        <div class='col-lg-6'>
          <h2>If you need us...</h2>
          <p>
            اكد عدد من اصحاب المصانع الدوائية ان صناعة الدواء في السودان تواجه تحديات كبيرة في الحصول على العملات الأجنبية لاستيراد مدخلات الإنتاج التي تقدر بستين مليون دولار سنويا.
            التفاصيل هنا
          </p>
          <p>
            وقالو إن صناعة الدواء في السودان تعاني من مشكلات طال أمدها وحالت دون توفير احتياجات البلاد الدوائية، ومن أبرز تلك المشكلات: قدرة المصانع على مواكبة تطورات الصناعة الدوائية
            التفاصيل هنا
          </p>
          <p>
            وقال مدير أحد المصانع- إن تكلفة صناعة شراب البنادول على سبيل المثال أعلى من سعر بيعه في السوق، مما جعلنا نوقف إنتاجه. وأوضح أن المزعج في الأمر -بحسب قوله- حصول شركات الدواء على الدولار من الجهات الرسمية
            التفاصيل هنا
          </p>
          <br />
          <a href='#' class='btn btn-primary'>لمزيد من المعلومات</a>
        </div>
        <div class='col-lg-6'>
          <br />
          <img src='../assets/background3.jpg' class='img-fluid' />
        </div>
      </div>
    </b-container>
    <hr class='my-4' />
    <!-- Fixed Background -->
    <figure>
      <div class='fixed-wrap'>
        <div id='fixed'>

        </div>
      </div>
    </figure>
    <!-- Emoji Section -->
    <button class='fun' data-toggle='collapse' data-target='#emoji'>cilck for fun</button>
    <div id='emoji' clss='collapse'>
      <div class='container fluid padding'>
        <div class='row text-center'>
          <div class='col-sm-6 col-md-3'>
            <img class='gif' src='../assets/smiling.gif' />
          </div>
          <div class='col-sm-6 col-md-3'>
            <img class='gif' src='../assets/smiling.gif' />
          </div>
          <div class='col-sm-6 col-md-3'>
            <img class='gif' src='../assets/smiling.gif' />
          </div>
          <div class='col-sm-6 col-md-3'>
            <img class='gif' src='../assets/smiling.gif' />
          </div>
        </div>
      </div>
    </div>
    <!-- Meet the Team -->
    <b-container fluid padding>
      <div class='row welcome text-center'>
        <div class='col-12'>
          <h1 class='display-4'>Meet the Team</h1>
        </div>
      </div>
    </b-container>
    <hr />
    <!-- Cards -->
    <b-container fluid padding>
      <div class='row padding'>

        <div class='col-md-4'>
          <div class='card'>
            <img class='card-img-top' src='../assets/employ1.png' />
            <div class='card-body'>
              <h4 class='card-title'>John Doe</h4>
              <p class='card-text'>John is an Vue JS developer for more than 20 years.</p>
              <a href='#' class='btn btn-outline-light'>See Profile</a>
            </div>
          </div>
        </div>

        <div class='col-md-4'>
          <div class='card'>
            <img class='card-img-top' src='../assets/employ2.png' />
            <div class='card-body'>
              <h4 class='card-title'>Mary Joy</h4>
              <p class='card-text'>Mary is an Vue JS developer for more than 20 years.</p>
              <a href='#' class='btn btn-outline-light'>See Profile</a>
            </div>
          </div>
        </div>

        <div class='col-md-4'>
          <div class='card'>
            <img class='card-img-top' src='../assets/employ3.png' />
            <div class='card-body'>
              <h4 class='card-title'>Tim Merrigan</h4>
              <p class='card-text'>Tim is an Vue JS developer for more than 20 years.</p>
              <a href='#' class='btn btn-outline-light'>See Profile</a>
            </div>
          </div>
        </div>

      </div>
    </b-container>

    <!-- Two Column Section -->
    <b-container fluid padding>
      <div class='row padding'>
        <div class='col-lg-6'>
          <h2>Our Philosophy...</h2>
          <p>
            اكد عدد من اصحاب المصانع الدوائية ان صناعة الدواء في السودان تواجه تحديات كبيرة في الحصول على العملات الأجنبية لاستيراد مدخلات الإنتاج التي تقدر بستين مليون دولار سنويا.
            التفاصيل هنا
          </p>
          <p>
            وقالو إن صناعة الدواء في السودان تعاني من مشكلات طال أمدها وحالت دون توفير احتياجات البلاد الدوائية، ومن أبرز تلك المشكلات: قدرة المصانع على مواكبة تطورات الصناعة الدوائية
            التفاصيل هنا
          </p>
          <br>
        </div>
        <div class='col-lg-6'>
          <br>
          <img src='../assets/pholisophy.jpg' class='img-fluid' />
        </div>
      </div>
    </b-container>
    <hr class='my-4' />

    <!-- Connect -->
    <b-container fluid padding>
      <div class='row text-center padding'>
        <div class='col-12'>
          <h2>Connect</h2>
        </div>
        <div class='col-12 social padding'>
          <a href='#'><i class='fab fa-facebook'></i></a>
          <a href='#'><i class='fab fa-twitter'></i></a>
          <a href='#'><i class='fab fa-google-plus-g'></i></a>
          <a href='#'><i class='fab fa-instagram'></i></a>
          <a href='#'><i class='fab fa-youtube'></i></a>
        </div>
      </div>
    </b-container>
    <!-- Footer -->
    <footer class='footer-main'>
        <b-container fluid padding>
          <div class='row text-center'>
            <div class='col-md-4'>
              <img src='../assets/softTechVVVSM.jpg' />
              <hr class='light'>
              <a>+249 9 123 55 555</a>
              <p>info@softTech.com</p>
              <p>100 Kafori Street</p>
              <p>Khartoum, Sudan</p>
            </div>
            <div class='col-md-4'>
              <hr class='light'>
              <h4>Our hours</h4>
              <hr class='light'>
              <p>Monday:   9am - 4pm</p>
              <p>Saturday: 10am - 3pm</p>
              <p>Firday: Closed</p>
            </div>
            <div class='col-md-4'>
              <hr class='light'>
              <h4>Our Services</h4>
              <hr class='light'>
              <p>Training</p>
              <p>Software Solutions</p>
              <p>Software Custom Solutions</p>
            </div>
            <div class='col-12'>
              <hr class='light-100'>
              <h4><i class='fas fa-copyright'></i> www.softtech.com </h4>
            </div>
          </div>
        </b-container>

    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomeMain',
  data () {
    return {
      slide: 0,
      sliding: null
    }
  },
  methods: {
    // onSlideStart(slide) {
    //   this.sliding = true;
    // },
    // onSlideEnd(slide) {
    //   this.sliding = false;
    // }
  },

  components: {}
}
</script>

<style scoped>
.homemain{
  height: 100%;
  width: 100%;
  font-family: 'Cairo';
  color: rgb(22, 20, 20)
}
.navbar{
  padding: .8rem;
}
.navbar-nav{
  padding-right: 20px;
}
.nav-item{
  font-family: 'Cairo';
  font-size: 1.1em;
}
.nav-link{
  font-family: 'Cairo';
  font-size: 1.1em;
}
.d-block{
  width: 100%;
  height: 100%
}
.centered {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.centered h3{
  font-size: 600%;
  color:cyan;
  text-shadow: 1px 1px 10px #000;
  padding-bottom: 1rem
}
.btn{
  background-color: #6648b1;
  border: 1px solid rgb(190, 22, 212);
}
.btn:hover{
  background-color: #563d7c;
  border: 1px solid #563d7c;
}
.carsousel-inner img{
  width: 100%;
  height: 100%;
}
.carousel-caption{
  position: absolute;
  top: 50%;
  transform: translateY(-50%)
}
.carousel-caption h1{
  font-size: 500%;
  text-shadow: 1px 1px 15px #000;
}
.carousel-caption h3{
  font-size: 200%;
  font-weight: 500;
  text-shadow: 1px 1px 15px #000;
  padding-bottom: 1rem;
}
.jumbotron{
  padding: 1rem;
  border-radius: 0;
  font-family: 'Cairo';
  font-size: 1.1em;
  text-align: right
}
.jumbotron btn{
  background-color: #6648b1;
  border: 1px solid rgb(190, 22, 212);
}
.jumbotron btn:hover{
  background-color: #563d7c;
  border: 1px solid #563d7c;
}
.padding{
  padding-bottom: 2rem;
}
.welcome{
  width: 75%;
  margin: 0 auto;
  padding-top: 2rem;
}
.welcome hr{
  border-top: 2px solid #b4b4b4;
  width: 95%;
  margin-top: .3rem;
  margin-bottom: 1rem;
}
.fa-code{
  color: #e54d26
}
.fa-bold{
  color: #563d7c;
}
.fa-css3{
  color: #2163af
}
.fa-code, .fa-bold, .fa-css3{
  font-size: 4em;
  margin: 1rem;
}
.fun{
  width: 100%;
  margin-bottom: 2rem;
}
.gif{
  max-width: 100%;
}
.social a {
  font-size: 4.5em;
  padding: 2rem;
}
.fa-facebook{
  color: #3b5998;
}
.fa-twitter{
  color: #00aced;
}
.fa-google-plus-g{
  color: #dd4b39;
}
.fa-instagram{
  color: #517fa4;
}
.fa-youtube{
  color: #bb0000;
}
.fa-facebook:hover,
.fa-twitter:hover,
.fa-google-plus-g:hover,
.fa-instagram:hover,
.fa-youtube:hover{
  color: #d5d5d5;
}
.footer-main{
  background-color: #3f3f3f;
  color: #d5d5d5;
  padding-top: 2rem;
}
hr.light{
  border-top: 1px solid #d5d5d5;
  width: 75%;
  margin-top: .8rem;
  margin-bottom: 1rem;
}
footer-main a {
  color: #d5d5d5;
}
hr.light-100{
  border-top: 1px solid #d5d5d5;
  width: 100%;
  margin-top: .8rem;
  margin-bottom: 1rem;
}
figure{
  position: relative;
  width: 100%;
  height: 60%;
  margin: 0!important;
}
.fixed-wrap{
  clip: rect(0,auto,auto,0);
  position: absolute;
  top: 0;
  left: 0;
  widows: 100;
  height: 100%;
}
#fixed{
  background-image: uri('../assets/background-fixed.jpg');
  position: fixed;
  display: block;
  top: 0;
  left: 0;
  widows: 100%;
  height: 100%;
  background-size: cover;
  background-position: center center;
  -webkit-transform: translateX(0);
          transform: translateZ(0);
  will-change: transform;
}
/*-------Media Queries-------*/
@media(max-width: 992px) {
  .social a {
    font-size: 4em;
    padding: 2rem;
  }
}

@media(max-width: 768px) {
.carousel-caption{
  top: 25%;
}
.carousel-caption h1{
  font-size: 250%;
}
.carousel-caption h3{
  font-size: 100%;
  font-weight: 300;
  padding-bottom: .2rem;
}
.carousel-caption .btn{
  font-size: 95%;
  font-weight: 300;
  padding: 8px 14px;
}
.display-4{
  font-size: 200%;
}
.social a{
  font-size: 2.5em;
  padding: 1.2rem;
}

}
@media(max-width: 576px) {
.carousel-caption{
  top: 40%;
}
.carousel-caption h1{
  font-size: 250%;
}
.carousel-caption h3{
  font-size: 110%;
}
.carousel-caption .btn{
  font-size: 90%;
  padding: 4px 8px;
}
.carousel-indicators{
  display: none;
}
.display-4{
  font-size: 160%;
}
.social a{
  font-size: 2em;
  padding: .7rem;
}

}
</style>
