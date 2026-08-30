<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MANU FONTS — Free Fonts for Creators</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:Arial,Helvetica,sans-serif;
  background:#080b12;
  color:#f5f5f5;
}

/* HEADER */

header{
  background:#0d111a;
  border-bottom:1px solid #252b38;
  position:sticky;
  top:0;
  z-index:100;
}

.header{
  max-width:1250px;
  margin:auto;
  padding:14px 20px;
  display:flex;
  align-items:center;
  gap:20px;
}

.logo{
  font-size:24px;
  font-weight:800;
  white-space:nowrap;
}

.logo span{
  color:#9b4dff;
}

.search-area{
  flex:1;
  display:flex;
  max-width:550px;
}

.search-area input{
  width:100%;
  background:#151b26;
  color:white;
  border:1px solid #303746;
  padding:11px 14px;
  outline:none;
  border-radius:8px 0 0 8px;
  font-size:14px;
}

.search-btn{
  border:0;
  background:#7c3aed;
  color:white;
  padding:0 18px;
  border-radius:0 8px 8px 0;
  cursor:pointer;
  font-weight:bold;
}

.language{
  background:#151b26;
  color:white;
  border:1px solid #303746;
  border-radius:8px;
  padding:10px;
  cursor:pointer;
}

nav{
  display:flex;
  gap:20px;
  align-items:center;
}

nav a{
  color:#c7cad1;
  text-decoration:none;
  font-size:14px;
}

nav a:hover{
  color:#a855f7;
}

/* HERO */

.hero{
  max-width:1250px;
  margin:20px auto;
  padding:55px 35px;
  border:1px solid #45206b;
  border-radius:16px;
  background:
  radial-gradient(circle at 80% 40%,#5b21b655,transparent 35%),
  linear-gradient(135deg,#111827,#170d28);
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:30px;
}

.hero-text{
  max-width:650px;
}

.hero h1{
  font-size:52px;
  line-height:1.08;
  margin-bottom:18px;
}

.hero h1 span{
  color:#a855f7;
}

.hero p{
  color:#b8bdc8;
  font-size:17px;
  line-height:1.6;
  margin-bottom:25px;
}

.hero-buttons{
  display:flex;
  gap:12px;
}

.primary-btn,
.secondary-btn{
  padding:12px 19px;
  border-radius:8px;
  text-decoration:none;
  font-weight:bold;
  cursor:pointer;
}

.primary-btn{
  background:#7c3aed;
  color:white;
}

.secondary-btn{
  background:#151b26;
  color:white;
  border:1px solid #394150;
}

.hero-font{
  font-size:130px;
  font-weight:900;
  color:#b65cff;
  text-shadow:
  0 0 20px #8b5cf6,
  0 0 60px #7c3aed;
}

/* MAIN */

.container{
  max-width:1250px;
  margin:auto;
  padding:0 20px;
}

.section-title{
  font-size:22px;
  margin:28px 0 15px;
}

/* CATEGORIES */

.categories{
  display:grid;
  grid-template-columns:repeat(6,1fr);
  gap:10px;
}

.category{
  background:#101620;
  border:1px solid #293140;
  border-radius:10px;
  padding:18px 10px;
  text-align:center;
  cursor:pointer;
  transition:.2s;
}

.category:hover{
  border-color:#9146ff;
  transform:translateY(-2px);
}

.category strong{
  display:block;
  margin-bottom:7px;
}

.category small{
  color:#8f96a3;
}

/* A-Z */

.az{
  display:flex;
  flex-wrap:wrap;
  gap:7px;
}

.letter{
  width:38px;
  height:38px;
  display:flex;
  align-items:center;
  justify-content:center;
  background:#101620;
  border:1px solid #293140;
  border-radius:7px;
  cursor:pointer;
}

.letter:hover{
  background:#7c3aed;
  border-color:#7c3aed;
}

/* FIND FONT */

.find-box{
  background:#0e141e;
  border:1px solid #282f3c;
  padding:18px;
  border-radius:12px;
  margin-top:20px;
  display:flex;
  gap:10px;
}

.find-box input{
  flex:1;
  background:#151b26;
  color:white;
  border:1px solid #343b48;
  border-radius:8px;
  padding:13px;
  outline:none;
}

.find-font-btn{
  background:#7c3aed;
  border:0;
  color:white;
  border-radius:8px;
  padding:0 22px;
  cursor:pointer;
  font-weight:bold;
}

/* FONT AREA */

.font-layout{
  display:grid;
  grid-template-columns:220px 1fr;
  gap:18px;
}

.sidebar{
  background:#101620;
  border:1px solid #293140;
  border-radius:12px;
  padding:18px;
  height:max-content;
}

.sidebar h3{
  margin-bottom:18px;
}

.filter{
  margin-bottom:20px;
}

.filter-title{
  color:#aeb4bf;
  margin-bottom:10px;
  font-size:14px;
}

.filter label{
  display:block;
  color:#bfc4ce;
  margin:9px 0;
  font-size:14px;
}

.font-list{
  min-width:0;
}

.total{
  color:#8f96a3;
  font-size:13px;
  margin-bottom:10px;
}

.font-card{
  background:#101620;
  border:1px solid #293140;
  border-radius:12px;
  padding:18px;
  margin-bottom:12px;
}

.font-top{
  display:flex;
  justify-content:space-between;
  align-items:center;
}

.badge{
  background:#34206a;
  color:#c084fc;
  padding:4px 8px;
  border-radius:5px;
  font-size:11px;
}

.font-preview{
  font-size:50px;
  margin:18px 0;
  word-break:break-word;
}

.font-bottom{
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:15px;
}

.font-details{
  color:#8f96a3;
  font-size:13px;
}

.actions{
  display:flex;
  gap:8px;
}

.download,
.share{
  border-radius:7px;
  padding:10px 15px;
  cursor:pointer;
  color:white;
  font-weight:bold;
}

.download{
  background:#7c3aed;
  border:0;
}

.share{
  background:#151b26;
  border:1px solid #394150;
}

/* FEATURES */

.features{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:12px;
  margin:30px 0;
}

.feature{
  background:#101620;
  border:1px solid #293140;
  border-radius:10px;
  padding:22px;
}

.feature h3{
  margin-bottom:8px;
}

.feature p{
  color:#9299a6;
  font-size:13px;
  line-height:1.5;
}

/* FOOTER */

footer{
  background:#0b1018;
  border-top:1px solid #252c38;
  margin-top:40px;
}

.footer{
  max-width:1250px;
  margin:auto;
  padding:40px 20px;
  display:grid;
  grid-template-columns:2fr 1fr 1fr 1fr;
  gap:30px;
}

.footer h2{
  margin-bottom:10px;
}

.footer h2 span{
  color:#9b4dff;
}

.footer p,
.footer a{
  color:#8f96a3;
  font-size:13px;
  line-height:1.8;
  text-decoration:none;
  display:block;
}

.copyright{
  border-top:1px solid #252c38;
  text-align:center;
  padding:15px;
  color:#6f7682;
  font-size:12px;
}

/* MOBILE */

@media(max-width:900px){

  .header{
    flex-wrap:wrap;
  }

  nav{
    display:none;
  }

  .search-area{
    order:3;
    max-width:none;
    width:100%;
  }

  .hero{
    margin:15px;
    padding:35px 22px;
  }

  .hero h1{
    font-size:38px;
  }

  .hero-font{
    display:none;
  }

  .categories{
    grid-template-columns:repeat(3,1fr);
  }

  .font-layout{
    grid-template-columns:1fr;
  }

  .sidebar{
    display:none;
  }

  .features{
    grid-template-columns:repeat(2,1fr);
  }

  .footer{
    grid-template-columns:1fr 1fr;
  }
}

@media(max-width:550px){

  .logo{
    font-size:20px;
  }

  .language{
    margin-left:auto;
  }

  .hero h1{
    font-size:32px;
  }

  .hero p{
    font-size:14px;
  }

  .categories{
    grid-template-columns:repeat(2,1fr);
  }

  .font-preview{
    font-size:36px;
  }

  .font-bottom{
    align-items:flex-start;
    flex-direction:column;
  }

  .actions{
    width:100%;
  }

  .download,
  .share{
    flex:1;
  }

  .features{
    grid-template-columns:1fr;
  }

  .footer{
    grid-template-columns:1fr;
  }
}
</style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="header">

<div class="logo">
MANU <span>FONTS</span>
</div>

<div class="search-area">

<input
id="mainSearch"
type="text"
placeholder="Search fonts, styles or authors..."
>

<button class="search-btn" onclick="searchFonts()">
Search
</button>

</div>

<select class="language" onchange="changeLanguage(this.value)">
<option value="en">English</option>
<option value="hi">हिन्दी</option>
<option value="es">Español</option>
<option value="fr">Français</option>
<option value="de">Deutsch</option>
<option value="it">Italiano</option>
<option value="pt">Português</option>
</select>

<nav>
<a href="#">Home</a>
<a href="#categories">Categories</a>
<a href="#fonts">New Fonts</a>
<a href="#tools">Tools</a>
</nav>

</div>

</header>


<!-- HERO -->

<section class="hero">

<div class="hero-text">

<h1>
Free <span>Fonts</span><br>
For Video Editing
</h1>

<p>
High-quality fonts for YouTube videos,
Reels, Shorts, thumbnails and creative projects.
</p>

<div class="hero-buttons">

<a href="#fonts" class="primary-btn">
Browse Fonts
</a>

<a href="#find" class="secondary-btn">
Find a Font
</a>

</div>

</div>

<div class="hero-font">
Aa
</div>

</section>


<main class="container">


<!-- CATEGORIES -->

<h2 class="section-title" id="categories">
Browse Fonts by Categories
</h2>

<div class="categories">

<div class="category">
<strong>Bold</strong>
<small>120 Fonts</small>
</div>

<div class="category">
<strong>Script</strong>
<small>90 Fonts</small>
</div>

<div class="category">
<strong>Display</strong>
<small>150 Fonts</small>
</div>

<div class="category">
<strong>Sans Serif</strong>
<small>110 Fonts</small>
</div>

<div class="category">
<strong>Handwritten</strong>
<small>70 Fonts</small>
</div>

<div class="category">
<strong>Modern</strong>
<small>95 Fonts</small>
</div>

</div>


<!-- A-Z -->

<h2 class="section-title">
Browse Fonts A–Z
</h2>

<div class="az">

<div class="letter">A</div>
<div class="letter">B</div>
<div class="letter">C</div>
<div class="letter">D</div>
<div class="letter">E</div>
<div class="letter">F</div>
<div class="letter">G</div>
<div class="letter">H</div>
<div class="letter">I</div>
<div class="letter">J</div>
<div class="letter">K</div>
<div class="letter">L</div>
<div class="letter">M</div>
<div class="letter">N</div>
<div class="letter">O</div>
<div class="letter">P</div>
<div class="letter">Q</div>
<div class="letter">R</div>
<div class="letter">S</div>
<div class="letter">T</div>
<div class="letter">U</div>
<div class="letter">V</div>
<div class="letter">W</div>
<div class="letter">X</div>
<div class="letter">Y</div>
<div class="letter">Z</div>

</div>


<!-- FIND -->

<h2 class="section-title" id="find">
Find Your Font
</h2>

<div class="find-box">

<input
id="findInput"
type="text"
placeholder="Type font name..."
>

<button
class="find-font-btn"
onclick="findFont()">
Find Font
</button>

</div>


<!-- FONTS -->

<h2 class="section-title" id="fonts">
Recently Added Fonts
</h2>

<div class="font-layout">


<!-- SIDEBAR -->

<aside class="sidebar">

<h3>Quick Filters</h3>

<div class="filter">

<div class="filter-title">
Font Types
</div>

<label>
<input type="checkbox">
Free Fonts
</label>

<label>
<input type="checkbox">
Personal Use
</label>

<label>
<input type="checkbox">
Commercial Use
</label>

</div>


<div class="filter">

<div class="filter-title">
Font Styles
</div>

<label>
<input type="checkbox">
Regular
</label>

<label>
<input type="checkbox">
Bold
</label>

<label>
<input type="checkbox">
Italic
</label>

<label>
<input type="checkbox">
Handwritten
</label>

</div>

</aside>


<!-- FONT LIST -->

<div class="font-list">

<div class="total">
Showing Free Fonts
</div>


<!-- FONT 1 -->

<div class="font-card">

<div class="font-top">

<span class="badge">
NEW
</span>

<span class="font-details">
Free Font
</span>

</div>

<div class="font-preview">
Milky Cream
</div>

<div class="font-bottom">

<div class="font-details">
Script Font · Free for personal use
</div>

<div class="actions">

<button
class="download"
onclick="downloadMessage('Milky Cream')">
Download
</button>

<button
class="share"
onclick="shareFont('Milky Cream')">
Share
</button>

</div>

</div>

</div>


<!-- FONT 2 -->

<div class="font-card">

<div class="font-top">

<span class="badge">
NEW
</span>

<span class="font-details">
Free Font
</span>

</div>

<div class="font-preview">
Dunker
</div>

<div class="font-bottom">

<div class="font-details">
Display Font · Free for personal use
</div>

<div class="actions">

<button
class="download"
onclick="downloadMessage('Dunker')">
Download
</button>

<button
class="share"
onclick="shareFont('Dunker')">
Share
</button>

</div>

</div>

</div>


<!-- FONT 3 -->

<div class="font-card">

<div class="font-top">

<span class="badge">
NEW
</span>

<span class="font-details">
Free Font
</span>

</div>

<div class="font-preview">
Coconut Island
</div>

<div class="font-bottom">

<div class="font-details">
Handwritten · Free for personal use
</div>

<div class="actions">

<button
class="download"
onclick="downloadMessage('Coconut Island')">
Download
</button>

<button
class="share"
onclick="shareFont('Coconut Island')">
Share
</button>

</div>

</div>

</div>


<!-- FONT 4 -->

<div class="font-card">

<div class="font-top">

<span class="badge">
NEW
</span>

<span class="font-details">
Free Font
</span>

</div>

<div class="font-preview">
Housemail Script
</div>

<div class="font-bottom">

<div class="font-details">
Script · Free for personal use
</div>

<div class="actions">

<button
class="download"
onclick="downloadMessage('Housemail Script')">
Download
</button>

<button
class="share"
onclick="shareFont('Housemail Script')">
Share
</button>

</div>

</div>

</div>


<!-- FONT 5 -->

<div class="font-card">

<div class="font-top">

<span class="badge">
NEW
</span>

<span class="font-details">
Free Font
</span>

</div>

<div class="font-preview">
Londrevida
</div>

<div class="font-bottom">

<div class="font-details">
Display Font · Free for personal use
</div>

<div class="actions">

<button
class="download"
onclick="downloadMessage('Londrevida')">
Download
</button>

<button
class="share"
onclick="shareFont('Londrevida')">
Share
</button>

</div>

</div>

</div>

</div>

</div>


<!-- FEATURES -->

<div class="features">

<div class="feature">
<h3>Free Fonts</h3>
<p>
A collection of free fonts for creative projects.
</p>
</div>

<div class="feature">
<h3>Easy Download</h3>
<p>
Download your selected font with one click.
</p>
</div>

<div class="feature">
<h3>Creator Friendly</h3>
<p>
Fonts selected for video editors and content creators.
</p>
</div>

<div class="feature">
<h3>Regular Updates</h3>
<p>
New fonts can be added regularly.
</p>
</div>

</div>

</main>


<!-- FOOTER -->

<footer>

<div class="footer">

<div>

<h2>
MANU <span>FONTS</span>
</h2>

<p>
Free fonts for video editors,
designers and content creators.
</p>

</div>


<div>

<h3>Quick Links</h3>

<a href="#">Home</a>
<a href="#categories">Categories</a>
<a href="#fonts">New Fonts</a>
<a href="#find">Find Font</a>

</div>


<div>

<h3>Categories</h3>

<a href="#">Bold</a>
<a href="#">Script</a>
<a href="#">Display</a>
<a href="#">Handwritten</a>

</div>


<div>

<h3>Support</h3>

<a href="#">FAQ</a>
<a href="#">Privacy Policy</a>
<a href="#">Terms of Use</a>
<a href="#">Contact</a>

</div>

</div>


<div class="copyright">
© 2026 MANU FONTS. All Rights Reserved.
</div>

</footer>


<script>

/* SEARCH */

function searchFonts(){

const value =
document.getElementById("mainSearch").value
.trim();

if(value === ""){
alert("Please enter a font name.");
return;
}

document.getElementById("fonts")
.scrollIntoView({
behavior:"smooth"
});

}


/* FIND FONT */

function findFont(){

const value =
document.getElementById("findInput").value
.trim();

if(value === ""){
alert("Please type a font name.");
return;
}

alert(
'Searching for "' +
value +
'" fonts...'
);

}


/* SHARE */

function shareFont(fontName){

if(navigator.share){

navigator.share({
title:fontName + " — MANU FONTS",
text:"Check out this free font on MANU FONTS.",
url:window.location.href
});

}else{

navigator.clipboard.writeText(
window.location.href
);

alert("Font link copied.");

}

}


/* DOWNLOAD DEMO */

function downloadMessage(fontName){

alert(
fontName +
" का असली Font File अभी जोड़ना बाकी है।"
);

}


/* LANGUAGE */

function changeLanguage(language){

if(language === "hi"){

alert(
"हिन्दी भाषा का इंटरफेस अगले चरण में पूरी तरह लागू करेंगे।"
);

}else{

alert(
"Language selected: " +
language
);

}

}

</script>

</body>
</html>
