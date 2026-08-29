<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MANU Fonts</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

body{
  background:#080808;
  color:#fff;
  font-family:Arial,"Noto Sans Devanagari",sans-serif;
}

header{
  position:sticky;
  top:0;
  z-index:10;
  background:#090909;
  border-bottom:1px solid #242424;
  padding:14px 16px;
}

.nav{
  max-width:1000px;
  margin:auto;
  display:flex;
  align-items:center;
  justify-content:space-between;
}

.brand{
  display:flex;
  align-items:center;
  gap:10px;
}

.logo{
  width:38px;
  height:38px;
  border-radius:11px;
  background:#e50914;
  display:flex;
  align-items:center;
  justify-content:center;
  font-weight:900;
  font-size:15px;
  box-shadow:0 0 20px rgba(229,9,20,.3);
}

.brand-name{
  font-size:19px;
  font-weight:800;
}

.brand-name span{
  color:#e50914;
}

.menu{
  font-size:24px;
}

.hero{
  padding:45px 18px 35px;
  text-align:center;
  background:
    radial-gradient(circle at 50% 0%,#3b0b0b 0%,#080808 55%);
}

.hero h1{
  font-size:38px;
  line-height:1.1;
  margin-bottom:12px;
}

.hero h1 span{
  color:#e50914;
}

.hero p{
  color:#aaa;
  max-width:600px;
  margin:auto;
  line-height:1.6;
}

.search{
  max-width:650px;
  margin:25px auto 0;
  display:flex;
  background:#151515;
  border:1px solid #333;
  border-radius:14px;
  padding:6px;
}

.search input{
  flex:1;
  border:0;
  outline:0;
  background:transparent;
  color:#fff;
  padding:13px;
  font-size:16px;
}

.search button{
  border:0;
  background:#e50914;
  color:white;
  padding:0 18px;
  border-radius:10px;
  font-weight:bold;
}

.container{
  max-width:1000px;
  margin:auto;
  padding:25px 16px;
}

.section-title{
  font-size:23px;
  margin-bottom:15px;
}

.section-title span{
  color:#e50914;
}

.categories{
  display:flex;
  gap:9px;
  overflow-x:auto;
  padding-bottom:8px;
  margin-bottom:28px;
}

.categories::-webkit-scrollbar{
  display:none;
}

.category{
  white-space:nowrap;
  padding:9px 15px;
  border-radius:30px;
  border:1px solid #333;
  background:#121212;
  color:#ccc;
  cursor:pointer;
}

.category.active{
  background:#e50914;
  border-color:#e50914;
  color:#fff;
}

.alphabet{
  display:flex;
  gap:7px;
  overflow-x:auto;
  margin-bottom:28px;
}

.alphabet::-webkit-scrollbar{
  display:none;
}

.letter{
  min-width:35px;
  height:35px;
  display:flex;
  align-items:center;
  justify-content:center;
  border:1px solid #333;
  border-radius:8px;
  color:#bbb;
  background:#111;
}

.font-card{
  background:#111;
  border:1px solid #252525;
  border-radius:18px;
  padding:18px;
  margin-bottom:16px;
  transition:.2s;
}

.font-card:hover{
  border-color:#e50914;
}

.card-top{
  display:flex;
  align-items:center;
  justify-content:space-between;
  margin-bottom:14px;
}

.font-name{
  font-size:18px;
  font-weight:800;
}

.badge{
  font-size:11px;
  background:#241010;
  color:#ff5555;
  padding:6px 9px;
  border-radius:20px;
}

.preview{
  min-height:90px;
  background:#080808;
  border:1px solid #222;
  border-radius:13px;
  padding:20px 15px;
  display:flex;
  align-items:center;
  font-size:29px;
  margin-bottom:14px;
}

.info{
  color:#777;
  font-size:12px;
  margin-bottom:15px;
}

.actions{
  display:flex;
  gap:9px;
}

.btn{
  flex:1;
  border:0;
  border-radius:10px;
  padding:12px;
  font-weight:bold;
  cursor:pointer;
}

.preview-btn{
  background:#252525;
  color:#fff;
}

.download-btn{
  background:#e50914;
  color:#fff;
}

.custom{
  background:#111;
  border:1px solid #252525;
  border-radius:18px;
  padding:20px;
  margin-top:30px;
  margin-bottom:30px;
}

.custom input{
  width:100%;
  background:#080808;
  border:1px solid #333;
  color:#fff;
  padding:14px;
  border-radius:10px;
  outline:none;
  margin-top:12px;
}

.custom-preview{
  font-size:30px;
  margin-top:18px;
  padding:15px 0;
}

footer{
  text-align:center;
  padding:35px 15px;
  border-top:1px solid #222;
  color:#777;
  font-size:13px;
}

footer strong{
  color:#fff;
}

@media(max-width:600px){
  .hero h1{
    font-size:31px;
  }

  .search button{
    padding:0 13px;
  }

  .preview{
    font-size:24px;
  }
}
</style>
</head>

<body>

<header>
  <div class="nav">
    <div class="brand">
      <div class="logo">MF</div>
      <div class="brand-name">MANU <span>Fonts</span></div>
    </div>
    <div class="menu">☰</div>
  </div>
</header>

<section class="hero">

  <h1>Find Your <span>Perfect Font</span></h1>

  <p>
    Hindi, English और Editing के लिए शानदार fonts खोजें,
    preview करें और डाउनलोड करें।
  </p>

  <div class="search">
    <input
      id="search"
      type="text"
      placeholder="Search fonts..."
      oninput="searchFonts()"
    >
    <button onclick="searchFonts()">Search</button>
  </div>

</section>

<main class="container">

  <h2 class="section-title">
    <span>Font</span> Categories
  </h2>

  <div class="categories">

    <div class="category active" onclick="filterFonts('all',this)">
      All
    </div>

    <div class="category" onclick="filterFonts('hindi',this)">
      Hindi
    </div>

    <div class="category" onclick="filterFonts('english',this)">
      English
    </div>

    <div class="category" onclick="filterFonts('editing',this)">
      Editing
    </div>

    <div class="category" onclick="filterFonts('stylish',this)">
      Stylish
    </div>

    <div class="category" onclick="filterFonts('bold',this)">
      Bold
    </div>

  </div>

  <h2 class="section-title">
    Browse <span>Fonts</span>
  </h2>

  <div class="alphabet">
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
  </div>

  <div id="fontList">

    <div class="font-card" data-category="hindi">

      <div class="card-top">
        <div class="font-name">Hindi Stylish Font</div>
        <div class="badge">NEW</div>
      </div>

      <div class="preview">
        नमस्ते भारत
      </div>

      <div class="info">
        Hindi • Devanagari • Free Preview
      </div>

      <div class="actions">
        <button class="btn preview-btn"
          onclick="changePreview(this)">
          Custom Preview
        </button>

        <button class="btn download-btn"
          onclick="downloadFont()">
          Download
        </button>
      </div>

    </div>


    <div class="font-card" data-category="english">

      <div class="card-top">
        <div class="font-name">Modern Creator</div>
        <div class="badge">POPULAR</div>
      </div>

      <div class="preview">
        MANU FONTS
      </div>

      <div class="info">
        English • Modern • Creator
      </div>

      <div class="actions">
        <button class="btn preview-btn"
          onclick="changePreview(this)">
          Custom Preview
        </button>

        <button class="btn download-btn"
          onclick="downloadFont()">
          Download
        </button>
      </div>

    </div>


    <div class="font-card" data-category="editing">

      <div class="card-top">
        <div class="font-name">Editing Bold</div>
        <div class="badge">TRENDING</div>
      </div>

      <div class="preview">
        EDIT LIKE A PRO
      </div>

      <div class="info">
        Editing • YouTube • Shorts • Reels
      </div>

      <div class="actions">
        <button class="btn preview-btn"
          onclick="changePreview(this)">
          Custom Preview
        </button>

        <button class="btn download-btn"
          onclick="downloadFont()">
          Download
        </button>
      </div>

    </div>

  </div>


  <div class="custom">

    <h2 class="section-title">
      Try <span>Your Text</span>
    </h2>

    <p style="color:#888;font-size:13px;">
      अपना text लिखकर preview देखें।
    </p>

    <input
      id="customText"
      type="text"
      value="MANU Fonts"
      oninput="livePreview()"
    >

    <div id="livePreview" class="custom-preview">
      MANU Fonts
    </div>

  </div>

</main>

<footer>

  <strong>MANU Fonts</strong>

  <br><br>

  Premium Hindi & English Fonts

  <br><br>

  © 2026 MANU Fonts

</footer>


<script>

function searchFonts(){

  const value =
    document.getElementById("search")
    .value
    .toLowerCase();

  document.querySelectorAll(".font-card")
  .forEach(card => {

    const text =
      card.innerText.toLowerCase();

    card.style.display =
      text.includes(value) ? "block" : "none";

  });

}


function filterFonts(category,button){

  document.querySelectorAll(".category")
  .forEach(x =>
    x.classList.remove("active")
  );

  button.classList.add("active");

  document.querySelectorAll(".font-card")
  .forEach(card => {

    if(
      category === "all" ||
      card.dataset.category === category
    ){
      card.style.display="block";
    }else{
      card.style.display="none";
    }

  });

}


function changePreview(button){

  const text =
    prompt(
      "अपना Preview Text लिखें:",
      "MANU Fonts"
    );

  if(text){

    const card =
      button.closest(".font-card");

    card.querySelector(".preview")
    .innerText=text;

  }

}


function livePreview(){

  const text =
    document.getElementById("customText").value;

  document.getElementById("livePreview")
  .innerText=text;

}


function downloadFont(){

  alert(
    "असली font file जोड़ने के बाद यह Download button काम करेगा।"
  );

}

</script>

</body>
</html>
