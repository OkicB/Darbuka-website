# Darbuka-website
Website about musical instrument Darbuka

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" 
integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" 
crossorigin="anonymous">

<style>
* {
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  background: #333;
  color: #fff;
  height: 100vh;
  line-height: 1.6;
  overflow: hidden;
}

.container {
  width: 100%;
  height: 100%;
  /* CSS Smooth Scroll */
  overflow-y: scroll; 
  scroll-behavior: smooth;
  scroll-snap-type: y mandatory;
}

.lead {
  font-size: 1.3rem;
}

.navbar {
  position: fixed;
  top: 0;
  z-index: 1;
  display: flex;
  width: 100%;
  height: 60px;
  background: rgba(0,0,0,0.7);
}

.navbar ul {
  display: flex;
  list-style: none;
  width: 100%;
  justify-content: center;
}

.navbar ul li {
  margin: 0 1rem;
  padding: 1rem;
}

.navbar ul li a {
  text-decoration: none;
  text-transform: uppercase;
  color: #f4f4f4;
}

.navbar ul li a:hover {
  color: skyblue;
}

.s1 {
display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  width: 100%;
  height: 100vh;
 
  /* Scroll Snap */
  scroll-snap-align: center;
}

.s2{
display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: top;
  top: 20%;
  text-align: center;
  width: 100%;
  height: 100vh;
 
  /* Scroll Snap */
  scroll-snap-align: center;
}
.s3 {
  bottom: 90%;
  font-size: 1.3rem;
  font-family: Arial, Helvetica, sans-serif;
  color: #fff;
  height: 100vh;
}

section h1 {
  font-size: 4rem;
}

/* Section Images */
section#home {
  background: url('https://st3.depositphotos.com/2353269/12953/i/950/depositphotos_129537438-stock-photo-decorated-colorful-pottery-goblet-drum.jpg/1600x900') no-repeat center center/cover;;
}

section#darbuka {
  background: url('https://images.unsplash.com/photo-1523689119443-df96632084a1?ixlib=rb-1.2.1&w=1000&q=80/1600x900') no-repeat center center/cover;;
}

section#technique {
  background: url('https://static1.squarespace.com/static/52112897e4b0717200296d2d/t/52120b23e4b030489dbd1350/1376914212418/abstract-bg-tutorial.jpg/1600x900') no-repeat center center/cover;;
}

section#about {
  background: url('https://motionarray.imgix.net/preview-82967-gZ6ArOJAiM-low_0011.jpg?w=660&q=60&fit=max&auto=format/1600x900') no-repeat center center/cover;;
}

section#contact {
  background: url('https://d117h1jjiq768j.cloudfront.net/images/default-source/services/services-contact-background.jpg?sfvrsn=244e016e_3/1600x900') no-repeat center center/cover;;
}

.contact-method{
float: left;
  width: 220px;
  height: 140px;
  display: inline-block;
  background: #3498db;
  margin: 10px;
  color: #fff;
  position: relative;
  cursor: pointer;
  display: flex;
}
.contact-method i {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  font-size: 30px;
  line-height: 140px;
  background: #34495e;
  z-index: 1;
  transition: transform 0.6s;
  flex-direction: column;
}
.contact-method span{
  position: absolute;
  width: 100%;
  left: 0;
  bottom: 0;
  padding: 10px 0;
  flex-direction: column;
}

.contact-method:hover i{
  transform: translateY(-40px);
}

</style>=/

</head>
<body>
<div class="container">
  <nav class="navbar">
      <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#darbuka">Darbuka</a></li>
          <li><a href="#technique">Technique</a></li>
          <li><a href="#about">About</a></li>
		  <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
  
  <section class="s1" id="home">
    <h1>Welcome To Darbuka World</h1> 
    <p class="lead"></p>
  </section>
  <section class="s2" id="darbuka">
      <h1 style="text-align:top;">Darbuka</h1>
      <p class="lead">Darbuka is a single head membranophone with a goblet 
shaped body used mostly in Egypt, also in parts of the Middle East, 
North Africa, South Asia,and Eastern Europe.[2] The African djembe-wassolou 
is also a goblet membranophone.[3] This article focuses on the Eastern and 
North-African goblet drum.</p>
<br>
<br>
      <h2>History</h2>
	  <p class="lead">The origin of the Egyptian Arabic term darabukka probably lies in the 
Arabic word "darab" ("to strike"). They have been around for thousands of 
years, used in Mesopotamian and Ancient Egyptian cultures. Goblet drums 
were seen in Babylonia and Sumer, from as early as 1100 
<abbr title="Before the Common Era">BCE</abbr>. On Celebes, 
one large form serves as a temple instrument, set on the floor when 
performed, which could be a survival of the ancient use of the drum.</p>
  </section>
  <section class="s2" id="technique">
      <h1>Technique</h1>
      <p class="lead">The Eastern and North-African goblet drums are played under the arm or 
resting on the player's leg, with a much lighter touch and quite different 
strokes (sometimes including rolls or quick rhythms articulated with the 
fingertips) to hand drums such as the djembe, found in West Africa.
There are two main types of goblet drums. The Egyptian style, Darabuka; 
also known as Tabla and is very popular, it has rounded edges around the 
head, whereas the Turkish style exposes the edge of the head. The exposed 
edge allows closer access to the head so finger-snapping techniques can be
done, but the hard edge discourages the rapid rolls possible with the 
Egyptian style. </p>
<p> Darbuka musicians:</p>
<ul class="ul2">
<li>Misirli Ahmet</li>
<li>Abdullah Hakawati</li>
<li>Setrak Sarkissian</li>
<li>Said El Artist</li>
<li>Hossam Ramzy</li>
<li>Rony Barrak</li>
<li>Alberto Christodoulou</li>
<li>Miguel Crespo</li>
<li>Amir Sofi</li>
<ul>
  </section>
  <section class="s2" id="about">
      <h1>About</h1>
      <p class="lead">Hello everyone who visit my website 

I am Bekir Okić, i am 20 years old and i live in Tuzla (Bosnia and Herzegovina)
I am student of informaation technology in Tuzla. I finish first year where I pass
programming language C. In upcoming study I will acquire knowledge about other 
programming languages at college and learn at home.

I decide to make this website to have some portfolio and to show employers my knowledge
that I acquire in web development learn by myself.
I take this topic because I love music and this instrument that i play professionaly

Thank You for read and visit my website.

For any kinds of information and questions You can contact me through any contact
that is located at the bottom of the page.</p>
  </section>
  <section class="s1" id="contact">
      <h1>Contact</h1>
	<div class="klasa">
      <div class="contact-method">
		<i class="fas fa-envelope"></i>
        <span>okicbekir@gmail.com</span>
      </div>
      <div class="contact-method">
        <i class="fab fa-linkedin"></i>
        <span>Bekir Okic</span>
      </div>
      <div class="contact-method">
        <i class="fas fa-globe-europe"></i>
        <span>Tuzla, BiH</span>
      </div>
	  <div class="contact-method">
        <i class="fab fa-github"></i>
        <span>OkicB</span>
      </div>
    </div>
  </section>
</div>
</body>
</html>
