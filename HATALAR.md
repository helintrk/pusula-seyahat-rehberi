<!-- css dosyası html dosyasına yanlış bağlanmış.-->
 <link rel="stylesheet" href="css/style.css" /> <!--hatalı--> 
<link rel="stylesheet" href="style.css" />      <!--doğrusu-->

<!-- tırnak işareti kapanmadığı için sonraki html  kısmı bozulmuştur-->
<li><a href="#iletisim>İletişim</a></li>  <!--hatalı-->
<li><a href="#iletisim">İletişim</a></li> <!--doğrusu-->

<!-- img etiketinde alt özelliği var onu bildirmeyince erişme hatası olabilir.-->

<img src="https://images.unsplash.com/photo-1469474968028-56623f02e42e?auto=format&fit=crop&w=1600&q=80" class="hero__bg"> <!--hatalı-->
<img
        src="https://images.unsplash.com/photo-1469474968028-56623f02e42e?auto=format&fit=crop&w=1600&q=80"
        alt="Hero görseli"
        class="hero__bg"
      /> <!--doğrusu-->

<!-- div etiketi kapatılmamış,sayfa düzeni bozulur.-->
<div class="container about__grid"> <!--hatalı-->
<div class="container about__grid"></div> <!--doğrusu>

<!-- etiketler yanlış sorayla kapatılmış-->

<strong><em>gerçekten unutulmaz</strong></em> <!--hatalı-->
<strong><em>gerçekten unutulmaz</em></strong> <!--doğrusu-->

<!--name özelliği eksik-->

<input type="email" id="email" placeholder="ornek@mail.com"> <!--hatalı-->
<input type="email" id="email" name="email" placeholder="ornek@mail.com" /> <!--doğrusu-->

 <!--color kelimesi yanlış yazılmış-->

colr: #fff; <!--hatalı-->
color: lab(4.04% 0.33 0.12); <!--doğrusu-->

  <!-- idnex kelimesi yoktur index olarak düzeltilmeli-->

z-idnex: 10;<!--hatalı-->
z-index: 10; <!--doğrusu-->

   <!--display sözcüğü hatalı yazılmış-->

dispaly: flex; <!--hatalı-->
display: flex; <!--doğrusu-->

 <!-- süslü parentez eksik kapatılmış-->

@media (max-width: 768px) {
.navbar\_\_links {
gap: 16px;
font-size: 13px;
} <!--hatalı>

@media (max-width: 768px) {
.navbar\_\_links {
gap: 16px;
font-size: 13px;
}} <!--doğrusu-->

  <!--ölçü birimsiz verilmiş-->

padding: 20; <!--hatalı-->
padding: 20px; <!--doğrusu-->

  <!--geçersiz renk kodu girilmiş-->

background: #12x45; <!--hatalı-->
background-color: #F7F3EC; <!--doğrusu-->

  <!-- background özelliğinden sonra noktalı virgül unutulmuş-->

.contact { padding: 120px 0; background: var(--forest) color: var(--white); } <!--hatalı-->
.contact { padding: 120px 0; background: var(--forest); color: var(--white); } <!--doğrusu-->
