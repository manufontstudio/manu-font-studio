<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MANU Fonts - Free Fonts for Video Editing</title>

<meta name="description"
content="MANU Fonts - Free fonts for video editing, design, thumbnails and creative projects.">

<style>
*{
  box-sizing:border-box;
}

body{
  margin:0;
  background:#08070d;
  color:#fff;
  font-family:Arial,sans-serif;
}

.container{
  width:92%;
  max-width:1100px;
  margin:auto;
}

/* HEADER */

header{
  background:linear-gradient(135deg,#100a1d,#24103c,#12091d);
  border-bottom:1px solid #35204b;
}

.topbar{
  padding:18px 0;
  display:flex;
  align-items:center;
  gap:18px;
}

.logo{
  font-size:24px;
  font-weight:900;
  white-space:nowrap;
}

.logo span{
  color:#a855f7;
}

/* SEARCH */

.search-box{
  flex:1;
  display:flex;
}

.search-box input{
  flex:1;
  min-width:0;
  padding:13px 15px;
  border:1px solid #49305d;
  background:#100b18;
  color:white;
  outline:none;
  border-radius:8px 0 0 8px;
}

.search-box button{
  border:0;
  padding:0 20px;
  background:#9333ea;
  color:white;
  font-weight:bold;
  border-radius:0 8px 8px 0;
}

/* HERO */

.hero{
  padding:65px 0 70px;
}

.hero h1{
  margin:0;
  font-size:clamp(38px,7vw,68px);
  line-height:1.05;
}

.hero h1 span{
  color:#a855f7;
}

.hero p{
  color:#b8a8c6;
  max-width:650px;
  font-size:17px;
  line-height:1.6;
}

/* MAIN SEARCH */

.main-search{
  display:flex;
  max-width:650px;
  margin-top:28px;
}

.main-search input{
  flex:1;
  min-width:0;
  padding:16px;
  border:1px solid #51336a;
  background:#0e0915;
  color:white;
  outline:none;
  border-radius:9px 0 0 9px;
  font-size:15px;
}

.main-search button{
  border:0;
  padding:0 25px;
  background:#9333ea;
  color:white;
  font-weight:bold;
  border-radius:0 9px 9px 0;
}

/* SECTIONS */

section{
  padding:32px 0;
}

.title{
  font-size:25px;
  font-weight:bold;
  margin-bottom:16px;
}

/* LANGUAGE */

.languages{
  display:grid;
  grid-template-columns:repeat(5,1fr);
  gap:12px;
}

.language{
  background:#11101a;
  border:1px solid #292033;
  border-radius:10px;
  padding:18px 10px;
  text-align:center;
  cursor:pointer;
}

.language:hover{
  border-color:#9333ea;
}

.language .flag{
  font-size:25px;
  margin-bottom:8px;
}

.language small{
  display:block;
  margin-top:5px;
  color:#887892;
}

/* A-Z */

.az{
  display:flex;
  flex-wrap:wrap;
  gap:7px;
}

.az button{
  width:36px;
  height:36px;
  border:1px solid #30243b;
  background:#11101a;
  color:#fff;
  border-radius:7px;
  cursor:pointer;
}

.az button:hover{
  background:#9333ea;
}

/* FONT CARD */

.font-card{
  background:#11101a;
  border:1px solid #292033;
  border-radius:13px;
  padding:18px;
  margin-bottom:15px;
}

.font-card.hidden{
  display:none;
}

.font-head{
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:10px;
  margin-bottom:15px;
}

.font-name{
  font-size:22px;
  font-weight:bold;
}

.font-info{
  color:#a855f7;
  font-size:13px;
}

.preview{
  background:#09080d;
  border:1px solid #241a2d;
  border-radius:9px;
  min-height:110px;
  display:flex;
  align-items:center;
  padding:18px;
  overflow:hidden;
}

.preview-text{
  font-size:48px;
  white-space:nowrap;
}

/* ACTIONS */

.actions{
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:10px;
  margin-top:15px;
}

.file-name{
  color:#82728d;
  font-size:12px;
}

.buttons{
  display:flex;
  gap:8px;
}

.download,
.share{
  padding:10px 16px;
  border-radius:7px;
  text-decoration:none;
  font-weight:bold;
  cursor:pointer;
}

.download{
  background:#9333ea;
  color:white;
}

.download:hover{
  background:#a855f7;
}

.share{
  background:#19131f;
  border:1px solid #49305d;
  color:white;
}

/* NO RESULT */

.no-result{
  display:none;
  text-align:center;
  padding:35px;
  color:#96869e;
}

/* FOOTER */

footer{
  margin-top:35px;
  padding:35px 0;
  text-align:center;
  color:#77677f;
  border-top:1px solid #292033;
}

/* POPPINS */

@font-face{
  font-family:"Poppins";
  src:url("Poppins-Regular.ttf") format("truetype");
  font-weight:400;
  font-style:normal;
  font-display:swap;
}

/* MOBILE */

@media(max-width:700px){

  .topbar{
    flex-direction:column;
    align-items:stretch;
  }

  .logo{
    text-align:center;
  }

  .languages{
    grid-template-columns:repeat(2,1fr);
  }

  .hero{
    padding:45px 0 50px;
  }

  .actions{
    flex-direction:column;
    align-items:stretch;
  }

  .buttons{
    width:100%;
  }

  .download,
  .share{
    flex:1;
    text-align:center;
  }

  .preview-text{
    font-size:35px;
  }
}
</style>
</head>

<body>

<header>

<div class="container">

<div class="topbar">

<div class="logo">
MANU <span>Fonts</span>
</div>

<div class="search-box">

<input
id="topSearch"
type="search"
placeholder="Search fonts..."
oninput="searchFonts()"
>

<button onclick="searchFonts()">Search</button>

</div>

</div>


<div class="hero">

<h1>
Free Fonts For <span>Video Editing</span>
</h1>

<p>
High-quality fonts for YouTube videos, Reels, Shorts,
thumbnails and creative projects.
</p>


<div class="main-search">

<input
id="mainSearch"
type="search"
placeholder="Find your font..."
oninput="searchFonts()"
>

<button onclick="searchFonts()">
Find Font
</button>

</div>

</div>

</div>

</header>


<main class="container">


<section>

<div class="title">
Browse Fonts by Language
</div>

<div class="languages">

<div class="language" onclick="filterLanguage('English')">
<div class="flag">🇬🇧</div>
<b>English</b>
<small>International</small>
</div>

<div class="language" onclick="filterLanguage('Hindi')">
<div class="flag">🇮🇳</div>
<b>Hindi</b>
<small>India</small>
</div>

<div class="language">
<div class="flag">🇪🇸</div>
<b>Spanish</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇫🇷</div>
<b>French</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇩🇪</div>
<b>German</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇮🇹</div>
<b>Italian</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇯🇵</div>
<b>Japanese</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇰🇷</div>
<b>Korean</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇸🇦</div>
<b>Arabic</b>
<small>Coming Soon</small>
</div>

<div class="language">
<div class="flag">🇷🇺</div>
<b>Russian</b>
<small>Coming Soon</small>
</div>

</div>

</section>


<section>

<div class="title">
Browse Fonts A–Z
</div>

<div class="az">

<button onclick="filterLetter('A')">A</button>
<button onclick="filterLetter('B')">B</button>
<button onclick="filterLetter('C')">C</button>
<button onclick="filterLetter('D')">D</button>
<button onclick="filterLetter('E')">E</button>
<button onclick="filterLetter('F')">F</button>
<button onclick="filterLetter('G')">G</button>
<button onclick="filterLetter('H')">H</button>
<button onclick="filterLetter('I')">I</button>
<button onclick="filterLetter('J')">J</button>
<button onclick="filterLetter('K')">K</button>
<button onclick="filterLetter('L')">L</button>
<button onclick="filterLetter('M')">M</button>
<button onclick="filterLetter('N')">N</button>
<button onclick="filterLetter('O')">O</button>
<button onclick="filterLetter('P')">P</button>
<button onclick="filterLetter('Q')">Q</button>
<button onclick="filterLetter('R')">R</button>
<button onclick="filterLetter('S')">S</button>
<button onclick="filterLetter('T')">T</button>
<button onclick="filterLetter('U')">U</button>
<button onclick="filterLetter('V')">V</button>
<button onclick="filterLetter('W')">W</button>
<button onclick="filterLetter('X')">X</button>
<button onclick="filterLetter('Y')">Y</button>
<button onclick="filterLetter('Z')">Z</button>

</div>

</section>


<section>

<div class="title">
Find Your Font
</div>


<div id="fontList">


<!-- POPPINS -->

<div
class="font-card"
data-name="Poppins"
data-language="English"
data-letter="P"
>

<div class="font-head">

<div class="font-name">
Poppins
</div>

<div class="font-info">
English • Regular
</div>

</div>


<div class="preview">

<div
class="preview-text"
style="font-family:Poppins,Arial,sans-serif"
>
MANU Fonts
</div>

</div>


<div class="actions">

<div class="file-name">
Poppins-Regular.ttf • Free Font
</div>

<div class="buttons">

<button
class="share"
onclick="shareFont('Poppins')"
>
↗ Share
</button>

<a
class="download"
href="Poppins-Regular.ttf"
download="Poppins-Regular.ttf"
>
↓ Download
</a>

</div>

</div>

</div>


<!-- INTER -->

<div
class="font-card"
data-name="Inter"
data-language="English"
data-letter="I"
>

<div class="font-head">

<div class="font-name">
Inter
</div>

<div class="font-info">
English • Regular
</div>

</div>


<div class="preview">

<div class="preview-text">
MANU Fonts
</div>

</div>


<div class="actions">

<div class="file-name">
Inter-Regular.ttf • Add file to GitHub
</div>

<div class="buttons">

<button
class="share"
onclick="shareFont('Inter')"
>
↗ Share
</button>

<a
class="download"
href="Inter-Regular.ttf"
download="Inter-Regular.ttf"
>
↓ Download
</a>

</div>

</div>

</div>


<!-- ROBOTO -->

<div
class="font-card"
data-name="Roboto"
data-language="English"
data-letter="R"
>

<div class="font-head">

<div class="font-name">
Roboto
</div>

<div class="font-info">
English • Regular
</div>

</div>


<div class="preview">

<div class="preview-text">
MANU Fonts
</div>

</div>


<div class="actions">

<div class="file-name">
Roboto-Regular.ttf • Add file to GitHub
</div>

<div class="buttons">

<button
class="share"
onclick="shareFont('Roboto')"
>
↗ Share
</button>

<a
class="download"
href="Roboto-Regular.ttf"
download="Roboto-Regular.ttf"
>
↓ Download
</a>

</div>

</div>

</div>


<!-- HINDI -->

<div
class="font-card"
data-name="Hindi Font"
data-language="Hindi"
data-letter="H"
>

<div class="font-head">

<div class="font-name">
Hindi Font
</div>

<div class="font-info">
Hindi • India
</div>

</div>


<div class="preview">

<div class="preview-text">
नमस्ते भारत
</div>

</div>


<div class="actions">

<div class="file-name">
Hindi font • Coming Soon
</div>

<div class="buttons">

<button
class="share"
onclick="shareFont('Hindi Font')"
>
↗ Share
</button>

<button
class="download"
onclick="alert('Hindi font की file अभी upload नहीं हुई है।')"
>
↓ Download
</button>

</div>

</div>

</div>


</div>


<div
id="noResult"
class="no-result"
>
कोई font नहीं मिला।
</div>

</section>

</main>


<footer>

<b>MANU Fonts</b>

<br><br>

Free Fonts for Video Editing, Design & Creative Projects.

<br><br>

© 2026 MANU Fonts

</footer>


<script>

/* SEARCH */

function searchFonts(){

let top =
document.getElementById("topSearch").value
.toLowerCase()
.trim();

let main =
document.getElementById("mainSearch").value
.toLowerCase()
.trim();

let query = main || top;

let cards =
document.querySelectorAll(".font-card");

let found = 0;

cards.forEach(function(card){

let name =
card.dataset.name.toLowerCase();

let language =
card.dataset.language.toLowerCase();

if(
query === "" ||
name.includes(query) ||
language.includes(query)
){

card.classList.remove("hidden");
found++;

}else{

card.classList.add("hidden");

}

});

document.getElementById("noResult").style.display =
found === 0 ? "block" : "none";

}


/* LANGUAGE FILTER */

function filterLanguage(language){

let cards =
document.querySelectorAll(".font-card");

let found=0;

cards.forEach(function(card){

if(card.dataset.language === language){

card.classList.remove("hidden");
found++;

}else{

card.classList.add("hidden");

}

});

document.getElementById("noResult").style.display =
found === 0 ? "block" : "none";

window.scrollTo({
top:document.getElementById("fontList").offsetTop-50,
behavior:"smooth"
});

}


/* A-Z FILTER */

function filterLetter(letter){

let cards =
document.querySelectorAll(".font-card");

let found=0;

cards.forEach(function(card){

if(card.dataset.letter === letter){

card.classList.remove("hidden");
found++;

}else{

card.classList.add("hidden");

}

});

document.getElementById("noResult").style.display =
found === 0 ? "block" : "none";

window.scrollTo({
top:document.getElementById("fontList").offsetTop-50,
behavior:"smooth"
});

}


/* SHARE */

function shareFont(font){

let shareData={
title:font+" - MANU Fonts",
text:"Download "+font+" from MANU Fonts.",
url:window.location.href
};

if(navigator.share){

navigator.share(shareData)
.catch(function(){});

}else{

navigator.clipboard.writeText(window.location.href)
.then(function(){

alert("MANU Fonts का link copy हो गया।");

})
.catch(function(){

alert("Share इस browser में उपलब्ध नहीं है।");

});

}

}

</script>

</body>
</html>
