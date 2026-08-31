<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MANU Fonts - Free Fonts for Everyone</title>

<meta name="description" content="MANU Fonts - Free Hindi, English and international fonts for video editing, design and creative projects.">
<meta name="keywords" content="free fonts, MANU Fonts, Hindi fonts, English fonts, video editing fonts, typography">

<style>
*{box-sizing:border-box}

body{
  margin:0;
  background:#0b0712;
  color:#fff;
  font-family:Arial,sans-serif;
}

header{
  background:linear-gradient(135deg,#17082b,#35105c,#13091f);
  border-bottom:1px solid #3c1c59;
}

.container{
  width:min(1100px,92%);
  margin:auto;
}

.topbar{
  padding:18px 0;
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:15px;
}

.logo{
  font-size:25px;
  font-weight:900;
  letter-spacing:.5px;
}

.logo span{
  color:#b86cff;
}

.search{
  display:flex;
  width:420px;
  max-width:100%;
}

.search input{
  width:100%;
  padding:13px 15px;
  border:1px solid #5c337d;
  border-radius:9px 0 0 9px;
  outline:none;
  background:#160d20;
  color:#fff;
}

.search button{
  border:0;
  padding:0 18px;
  border-radius:0 9px 9px 0;
  background:#9b4dff;
  color:#fff;
  font-weight:bold;
}

.hero{
  text-align:center;
  padding:70px 10px 75px;
}

.hero h1{
  margin:0;
  font-size:clamp(35px,7vw,65px);
  line-height:1.05;
}

.hero h1 span{
  color:#b96cff;
}

.hero p{
  color:#c7b8d5;
  font-size:17px;
  margin:18px auto 0;
  max-width:650px;
}

.hero-search{
  max-width:650px;
  margin:30px auto 0;
  display:flex;
}

.hero-search input{
  flex:1;
  padding:16px;
  border:1px solid #623683;
  border-radius:10px 0 0 10px;
  background:#100917;
  color:#fff;
  outline:none;
  font-size:15px;
}

.hero-search button{
  border:0;
  padding:0 25px;
  background:#a44cff;
  color:white;
  border-radius:0 10px 10px 0;
  font-weight:bold;
}

section{
  padding:30px 0;
}

.section-title{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-bottom:18px;
}

.section-title h2{
  margin:0;
  font-size:25px;
}

.section-title span{
  color:#a967e8;
  font-size:13px;
}

.categories{
  display:grid;
  grid-template-columns:repeat(5,1fr);
  gap:12px;
}

.category{
  background:#160d20;
  border:1px solid #352043;
  border-radius:12px;
  padding:18px 10px;
  text-align:center;
  cursor:pointer;
  color:#fff;
}

.category:hover{
  border-color:#a44cff;
  transform:translateY(-2px);
}

.category .flag{
  font-size:25px;
  margin-bottom:8px;
}

.category b{
  display:block;
}

.category small{
  color:#927da2;
}

.az{
  display:flex;
  flex-wrap:wrap;
  gap:7px;
}

.az button{
  width:35px;
  height:35px;
  border:1px solid #39244a;
  border-radius:7px;
  background:#160d20;
  color:#fff;
  cursor:pointer;
}

.az button:hover{
  background:#9b4dff;
}

.controls{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  background:#120a19;
  border:1px solid #302039;
  padding:14px;
  border-radius:10px;
  margin-bottom:15px;
}

.controls input,
.controls select{
  padding:10px;
  border:1px solid #49305c;
  background:#0e0813;
  color:#fff;
  border-radius:7px;
}

.controls input{
  flex:1;
  min-width:200px;
}

.font-card{
  background:#120a19;
  border:1px solid #332040;
  border-radius:13px;
  padding:18px;
  margin-bottom:14px;
}

.font-top{
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:10px;
  margin-bottom:14px;
}

.font-name{
  font-size:19px;
  font-weight:bold;
}

.badge{
  color:#c28aff;
  font-size:12px;
}

.preview{
  min-height:110px;
  border-radius:9px;
  background:#0b0710;
  border:1px solid #271832;
  display:flex;
  align-items:center;
  padding:15px;
  overflow:hidden;
}

.preview-text{
  font-size:50px;
  white-space:nowrap;
}

.poppins{
  font-family:Poppins,Arial,sans-serif;
}

.font-actions{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-top:14px;
  gap:10px;
}

.font-actions small{
  color:#806d8d;
}

.buttons{
  display:flex;
  gap:8px;
}

.share,
.download{
  border:0;
  border-radius:7px;
  padding:10px 15px;
  font-weight:bold;
  cursor:pointer;
  text-decoration:none;
}

.share{
  background:#241531;
  color:#fff;
  border:1px solid #53326d;
}

.download{
  background:#9b4dff;
  color:#fff;
}

.download:hover{
  background:#b66dff;
}

.empty{
  display:none;
  text-align:center;
  padding:30px;
  color:#a996b3;
}

footer{
  border-top:1px solid #302039;
  margin-top:30px;
  padding:35px 0;
  text-align:center;
  color:#806d8d;
  font-size:13px;
}

@font-face{
  font-family:"Poppins";
  src:url("Poppins-Regular.ttf") format("truetype");
  font-weight:400;
  font-style:normal;
  font-display:swap;
}

@media(max-width:750px){

  .topbar{
    flex-direction:column;
    align-items:stretch;
  }

  .logo{
    text-align:center;
  }

  .categories{
    grid-template-columns:repeat(2,1fr);
  }

  .hero{
    padding:50px 5px;
  }

  .hero-search{
    display:flex;
  }

  .hero-search input{
    min-width:0;
  }

  .font-top{
    align-items:flex-start;
    flex-direction:column;
  }

  .font-actions{
    flex-direction:column;
    align-items:stretch;
  }

  .buttons{
    width:100%;
  }

  .share,
  .download{
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

<div class="search">
  <input id="topSearch" placeholder="Search fonts..." oninput="searchFonts()">
  <button onclick="searchFonts()">Search</button>
</div>

</div>

<div class="hero">

<h1>
  Free Fonts For <span>Everyone</span>
</h1>

<p>
  Discover free fonts for video editing, design, thumbnails,
  posters and creative projects.
</p>

<div class="hero-search">

<input
  id="mainSearch"
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

<div class="section-title">

<h2>Browse Fonts by Language</h2>

<span>More languages coming soon</span>

</div>


<div class="categories">

<div class="category" onclick="languageFilter('english')">
<div class="flag">🇬🇧</div>
<b>English</b>
<small>International</small>
</div>

<div class="category" onclick="languageFilter('hindi')">
<div class="flag">🇮🇳</div>
<b>Hindi</b>
<small>India</small>
</div>

<div class="category" onclick="languageFilter('spanish')">
<div class="flag">🇪🇸</div>
<b>Spanish</b>
<small>Español</small>
</div>

<div class="category" onclick="languageFilter('french')">
<div class="flag">🇫🇷</div>
<b>French</b>
<small>Français</small>
</div>

<div class="category" onclick="languageFilter('german')">
<div class="flag">🇩🇪</div>
<b>German</b>
<small>Deutsch</small>
</div>

<div class="category" onclick="languageFilter('italian')">
<div class="flag">🇮🇹</div>
<b>Italian</b>
<small>Italiano</small>
</div>

<div class="category" onclick="languageFilter('portuguese')">
<div class="flag">🇵🇹</div>
<b>Portuguese</b>
<small>Português</small>
</div>

<div class="category" onclick="languageFilter('arabic')">
<div class="flag">🇸🇦</div>
<b>Arabic</b>
<small>العربية</small>
</div>

<div class="category" onclick="languageFilter('japanese')">
<div class="flag">🇯🇵</div>
<b>Japanese</b>
<small>日本語</small>
</div>

<div class="category" onclick="languageFilter('korean')">
<div class="flag">🇰🇷</div>
<b>Korean</b>
<small>한국어</small>
</div>

</div>

</section>


<section>

<div class="section-title">

<h2>Browse Fonts A–Z</h2>

<span>All Fonts</span>

</div>


<div class="az">

<button onclick="letterFilter('A')">A</button>
<button onclick="letterFilter('B')">B</button>
<button onclick="letterFilter('C')">C</button>
<button onclick="letterFilter('D')">D</button>
<button onclick="letterFilter('E')">E</button>
<button onclick="letterFilter('F')">F</button>
<button onclick="letterFilter('G')">G</button>
<button onclick="letterFilter('H')">H</button>
<button onclick="letterFilter('I')">I</button>
<button onclick="letterFilter('J')">J</button>
<button onclick="letterFilter('K')">K</button>
<button onclick="letterFilter('L')">L</button>
<button onclick="letterFilter('M')">M</button>
<button onclick="letterFilter('N')">N</button>
<button onclick="letterFilter('O')">O</button>
<button onclick="letterFilter('P')">P</button>
<button onclick="letterFilter('Q')">Q</button>
<button onclick="letterFilter('R')">R</button>
<button onclick="letterFilter('S')">S</button>
<button onclick="letterFilter('T')">T</button>
<button onclick="letterFilter('U')">U</button>
<button onclick="letterFilter('V')">V</button>
<button onclick="letterFilter('W')">W</button>
<button onclick="letterFilter('X')">X</button>
<button onclick="letterFilter('Y')">Y</button>
<button onclick="letterFilter('Z')">Z</button>

</div>

</section>


<section>

<div class="section-title">

<h2>Find Your Font</h2>

</div>


<div class="controls">

<input
  id="customText"
  value="MANU Fonts"
  placeholder="Type your text..."
  oninput="changePreview()"
>

<select id="fontSize" onchange="changePreview()">
<option value="30">30px</option>
<option value="40">40px</option>
<option value="50" selected>50px</option>
<option value="60">60px</option>
<option value="70">70px</option>
<option value="80">80px</option>
</select>

<button class="share" onclick="resetAll()">
Reset
</button>

</div>


<div id="fontList">


<div
class="font-card"
data-name="poppins"
data-language="english"
data-letter="P"
>

<div class="font-top">

<div class="font-name">
Poppins
</div>

<div class="badge">
English • Regular
</div>

</div>


<div class="preview">

<div class="preview-text poppins" id="poppinsPreview">
MANU Fonts
</div>

</div>


<div class="font-actions">

<small>
Poppins-Regular.ttf • Free Font
</small>


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


<div
class="font-card"
data-name="hindi"
data-language="hindi"
data-letter="H"
>

<div class="font-top">

<div class="font-name">
Hindi Font
</div>

<div class="badge">
Hindi • India
</div>

</div>

<div class="preview">

<div class="preview-text">
नमस्ते भारत
</div>

</div>

<div class="font-actions">

<small>
Hindi font coming soon
</small>

<div class="buttons">

<button
class="share"
onclick="shareFont('Hindi Font')"
>
↗ Share
</button>

<button
class="download"
onclick="comingSoon()"
>
↓ Download
</button>

</div>

</div>

</div>


</div>


<div id="empty" class="empty">
No fonts found.
</div>

</section>

</main>


<footer>

<b>MANU Fonts</b>

<br><br>

Free fonts for video editing, design and creative projects.

<br><br>

© 2026 MANU Fonts

</footer>


<script>

function getCards(){
  return document.querySelectorAll(".font-card");
}


function searchFonts(){

  let a=document.getElementById("topSearch").value.toLowerCase().trim();

  let b=document.getElementById("mainSearch").value.toLowerCase().trim();

  let search=b || a;

  let found=0;

  getCards().forEach(function(card){

    let text=card.innerText.toLowerCase();

    if(text.includes(search)){
      card.style.display="block";
      found++;
    }else{
      card.style.display="none";
    }

  });

  document.getElementById("empty").style.display =
    found ? "none" : "block";
}


function languageFilter(language){

  let found=0;

  getCards().forEach(function(card){

    if(card.dataset.language===language){

      card.style.display="block";
      found++;

    }else{

      card.style.display="none";

    }

  });

  document.getElementById("empty").style.display =
    found ? "none" : "block";

}


function letterFilter(letter){

  let found=0;

  getCards().forEach(function(card){

    if(card.dataset.letter===letter){

      card.style.display="block";
      found++;

    }else{

      card.style.display="none";

    }

  });

  document.getElementById("empty").style.display =
    found ? "none" : "block";

}


function changePreview(){

  let text =
    document.getElementById("customText").value ||
    "MANU Fonts";

  let size =
    document.getElementById("fontSize").value;

  document
    .querySelectorAll(".preview-text")
    .forEach(function(el){

      el.innerText=text;
      el.style.fontSize=size+"px";

    });

}


function resetAll(){

  document.getElementById("topSearch").value="";
  document.getElementById("mainSearch").value="";
  document.getElementById("customText").value="MANU Fonts";
  document.getElementById("fontSize").value="50";

  getCards().forEach(function(card){
    card.style.display="block";
  });

  document.getElementById("empty").style.display="none";

  changePreview();

}


function shareFont(font){

  let data={
    title:font+" - MANU Fonts",
    text:"Check out "+font+" on MANU Fonts.",
    url:window.location.href
  };

  if(navigator.share){

    navigator.share(data).catch(function(){});

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


function comingSoon(){

  alert(
    "इस font की असली file अभी MANU Fonts पर उपलब्ध नहीं है।"
  );

}

</script>

</body>
</html>
