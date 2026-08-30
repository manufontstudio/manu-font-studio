<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MANU Fonts - Free Font Library</title>

<style>
*{
  box-sizing:border-box;
}

body{
  margin:0;
  background:#fff;
  color:#111;
  font-family:Arial,"Noto Sans Devanagari",sans-serif;
}

button,input,select{
  font-family:inherit;
}

.top{
  background:#111;
  color:#fff;
  padding:7px 15px;
  font-size:12px;
}

.top-inner,
.header-inner,
.main,
.footer-inner{
  max-width:1100px;
  margin:auto;
}

.top-inner{
  display:flex;
  justify-content:space-between;
}

.header{
  background:#e30613;
  color:#fff;
  padding:15px;
}

.header-inner{
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:20px;
}

.logo{
  display:flex;
  align-items:center;
  gap:10px;
}

.logo-box{
  width:48px;
  height:48px;
  background:#fff;
  color:#e30613;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:21px;
  font-weight:900;
  border-radius:5px;
}

.logo-text{
  font-size:24px;
  font-weight:900;
}

.logo-text span{
  font-weight:400;
}

.search{
  display:flex;
  max-width:430px;
  width:100%;
}

.search input{
  flex:1;
  height:40px;
  border:0;
  padding:0 12px;
  outline:none;
  font-size:15px;
}

.search button{
  width:80px;
  border:0;
  background:#222;
  color:#fff;
  font-weight:bold;
  cursor:pointer;
}

.nav{
  background:#f1f1f1;
  border-bottom:1px solid #ccc;
}

.nav-inner{
  max-width:1100px;
  margin:auto;
  display:flex;
  flex-wrap:wrap;
}

.nav a{
  padding:11px 14px;
  font-size:14px;
  font-weight:bold;
  color:#111;
  text-decoration:none;
}

.nav a:hover{
  background:#ddd;
}

.main{
  padding:15px;
}

.alphabet{
  border:1px solid #ccc;
  background:#fafafa;
  padding:10px;
  margin-bottom:15px;
}

.alphabet-title{
  font-size:13px;
  font-weight:bold;
  margin-bottom:8px;
}

.letters{
  display:flex;
  flex-wrap:wrap;
  gap:4px;
}

.letter{
  border:1px solid #bbb;
  background:white;
  min-width:29px;
  height:28px;
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:12px;
  cursor:pointer;
}

.letter:hover{
  background:#e30613;
  color:white;
}

.controls{
  border:1px solid #ccc;
  padding:12px;
  background:#f7f7f7;
  margin-bottom:15px;
}

.controls-row{
  display:flex;
  flex-wrap:wrap;
  gap:8px;
  align-items:center;
}

.controls input,
.controls select{
  height:36px;
  border:1px solid #bbb;
  background:white;
  padding:0 9px;
}

.preview-input{
  min-width:230px;
  flex:1;
}

.preview-size{
  width:90px;
}

.red-button{
  height:36px;
  border:0;
  background:#e30613;
  color:#fff;
  padding:0 16px;
  font-weight:bold;
  cursor:pointer;
}

.red-button:hover{
  background:#b9000a;
}

.category-box{
  border:1px solid #ccc;
  margin-bottom:18px;
}

.category-title{
  background:#e30613;
  color:#fff;
  font-weight:bold;
  padding:8px 12px;
}

.categories{
  display:grid;
  grid-template-columns:repeat(6,1fr);
}

.categories button{
  border:0;
  border-right:1px solid #ddd;
  border-bottom:1px solid #ddd;
  background:#fff;
  padding:10px 5px;
  cursor:pointer;
  font-size:12px;
}

.categories button:hover{
  background:#eee;
}

.section-title{
  background:#e30613;
  color:#fff;
  padding:8px 12px;
  font-size:15px;
  margin:0;
}

.font-card{
  border:1px solid #ccc;
  border-top:0;
  background:#fff;
  padding:12px;
}

.font-head{
  display:flex;
  justify-content:space-between;
  align-items:center;
  background:#f4f4f4;
  padding:7px 8px;
  margin-bottom:10px;
}

.font-name{
  color:#b00000;
  font-size:15px;
  font-weight:bold;
}

.font-info{
  font-size:11px;
  color:#777;
}

.preview-area{
  min-height:115px;
  display:flex;
  align-items:center;
  overflow:hidden;
  border-bottom:1px solid #eee;
  padding:8px 4px;
}

.font-preview{
  font-family:Georgia,serif;
  font-size:50px;
  white-space:nowrap;
}

.font-card:nth-of-type(2) .font-preview{
  font-family:"Trebuchet MS",sans-serif;
  font-weight:bold;
}

.font-card:nth-of-type(3) .font-preview{
  font-family:cursive;
}

.font-card:nth-of-type(4) .font-preview{
  font-family:Impact,Arial,sans-serif;
}

.font-card:nth-of-type(5) .font-preview{
  font-family:Georgia,serif;
  font-style:italic;
}

.font-bottom{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding-top:9px;
  gap:8px;
}

.actions{
  display:flex;
  gap:7px;
}

.license{
  font-size:11px;
  color:#777;
}

.share{
  background:#eee;
  color:#111;
  border:1px solid #bbb;
  padding:8px 14px;
  font-weight:bold;
  cursor:pointer;
}

.share:hover{
  background:#ddd;
}

.download{
  background:#e30613;
  color:#fff;
  border:1px solid #b00000;
  padding:8px 16px;
  font-weight:bold;
  cursor:pointer;
}

.download:hover{
  background:#b00000;
}

.more{
  text-align:center;
  padding:18px;
}

.more button{
  background:#e30613;
  color:#fff;
  border:0;
  padding:12px 25px;
  font-weight:bold;
  cursor:pointer;
}

.footer{
  margin-top:30px;
  background:#eee;
  border-top:1px solid #ccc;
  padding:25px 15px;
  color:#666;
  font-size:12px;
  text-align:center;
}

@media(max-width:700px){

  .header-inner{
    flex-direction:column;
    align-items:stretch;
  }

  .search{
    max-width:none;
  }

  .categories{
    grid-template-columns:repeat(3,1fr);
  }

  .font-preview{
    font-size:35px;
  }

  .font-bottom{
    align-items:flex-start;
    flex-direction:column;
  }

  .actions{
    width:100%;
  }

  .share,
  .download{
    flex:1;
  }

  .top-inner{
    display:none;
  }

  .logo-text{
    font-size:21px;
  }
}
</style>
</head>

<body>

<div class="top">
  <div class="top-inner">
    <span>MANU Fonts - Free Font Library</span>
    <span>Hindi | English | Editing</span>
  </div>
</div>

<header class="header">
  <div class="header-inner">

    <div class="logo">
      <div class="logo-box">MF</div>
      <div class="logo-text">
        MANU <span>Fonts</span>
      </div>
    </div>

    <div class="search">
      <input
        id="searchInput"
        type="text"
        placeholder="Search fonts..."
        oninput="searchFonts()"
      >
      <button onclick="searchFonts()">Search</button>
    </div>

  </div>
</header>

<nav class="nav">
  <div class="nav-inner">
    <a href="#">Home</a>
    <a href="#new">New Fonts</a>
    <a href="#popular">Popular</a>
    <a href="#hindi">Hindi</a>
    <a href="#english">English</a>
    <a href="#editing">Editing</a>
    <a href="#faq">FAQ</a>
  </div>
</nav>

<main class="main">

<div class="alphabet">

  <div class="alphabet-title">
    Browse Fonts A-Z
  </div>

  <div class="letters">
    <button class="letter" onclick="letterFilter('A')">A</button>
    <button class="letter" onclick="letterFilter('B')">B</button>
    <button class="letter" onclick="letterFilter('C')">C</button>
    <button class="letter" onclick="letterFilter('D')">D</button>
    <button class="letter" onclick="letterFilter('E')">E</button>
    <button class="letter" onclick="letterFilter('F')">F</button>
    <button class="letter" onclick="letterFilter('G')">G</button>
    <button class="letter" onclick="letterFilter('H')">H</button>
    <button class="letter" onclick="letterFilter('I')">I</button>
    <button class="letter" onclick="letterFilter('J')">J</button>
    <button class="letter" onclick="letterFilter('K')">K</button>
    <button class="letter" onclick="letterFilter('L')">L</button>
    <button class="letter" onclick="letterFilter('M')">M</button>
    <button class="letter" onclick="letterFilter('N')">N</button>
    <button class="letter" onclick="letterFilter('O')">O</button>
    <button class="letter" onclick="letterFilter('P')">P</button>
    <button class="letter" onclick="letterFilter('Q')">Q</button>
    <button class="letter" onclick="letterFilter('R')">R</button>
    <button class="letter" onclick="letterFilter('S')">S</button>
    <button class="letter" onclick="letterFilter('T')">T</button>
    <button class="letter" onclick="letterFilter('U')">U</button>
    <button class="letter" onclick="letterFilter('V')">V</button>
    <button class="letter" onclick="letterFilter('W')">W</button>
    <button class="letter" onclick="letterFilter('X')">X</button>
    <button class="letter" onclick="letterFilter('Y')">Y</button>
    <button class="letter" onclick="letterFilter('Z')">Z</button>
  </div>

</div>

<div class="controls">

  <div class="controls-row">

    <input
      id="customText"
      class="preview-input"
      value="MANU Fonts"
      placeholder="Type your text here..."
      oninput="changeAllPreview()"
    >

    <select id="fontSize" class="preview-size" onchange="changeSize()">
      <option value="30">30px</option>
      <option value="40">40px</option>
      <option value="50" selected>50px</option>
      <option value="60">60px</option>
      <option value="70">70px</option>
      <option value="80">80px</option>
    </select>

    <button class="red-button" onclick="changeAllPreview()">
      Submit
    </button>

    <button class="red-button" onclick="resetFonts()">
      Reset
    </button>

  </div>

</div>

<div class="category-box">

  <div class="category-title">
    Font Categories
  </div>

  <div class="categories">

    <button onclick="filterCategory('all')">All Fonts</button>
    <button onclick="filterCategory('fancy')">Fancy</button>
    <button onclick="filterCategory('retro')">Retro</button>
    <button onclick="filterCategory('techno')">Techno</button>
    <button onclick="filterCategory('basic')">Basic</button>
    <button onclick="filterCategory('script')">Script</button>

    <button onclick="filterCategory('hindi')">Hindi</button>
    <button onclick="filterCategory('english')">English</button>
    <button onclick="filterCategory('editing')">Editing</button>
    <button onclick="filterCategory('bold')">Bold</button>
    <button onclick="filterCategory('handwritten')">Handwritten</button>
    <button onclick="filterCategory('stylish')">Stylish</button>

  </div>

</div>

<section id="new">

<h2 class="section-title">
  Recently Added Fonts
</h2>

<div class="font-card" data-category="script stylish" data-letter="M">

  <div class="font-head">
    <div class="font-name">Miracle History</div>
    <div class="font-info">Script • Stylish</div>
  </div>

  <div class="preview-area">
    <div class="font-preview">Miracle History</div>
  </div>

  <div class="font-bottom">

    <div class="license">
      Free Preview • MANU Fonts
    </div>

    <div class="actions">

      <button class="share"
        onclick="shareFont('Miracle History')">
        ↗ Share
      </button>

      <button class="download"
        onclick="downloadMessage('Miracle History')">
        ↓ Download
      </button>

    </div>

  </div>

</div>


<div class="font-card" data-category="handwritten stylish" data-letter="M">

  <div class="font-head">
    <div class="font-name">Milky Cream</div>
    <div class="font-info">Handwritten • Stylish</div>
  </div>

  <div class="preview-area">
    <div class="font-preview">Milky Cream</div>
  </div>

  <div class="font-bottom">

    <div class="license">
      Free Preview • MANU Fonts
    </div>

    <div class="actions">

      <button class="share"
        onclick="shareFont('Milky Cream')">
        ↗ Share
      </button>

      <button class="download"
        onclick="downloadMessage('Milky Cream')">
        ↓ Download
      </button>

    </div>

  </div>

</div>


<div class="font-card" data-category="fancy" data-letter="T">

  <div class="font-head">
    <div class="font-name">Taste Bread</div>
    <div class="font-info">Fancy</div>
  </div>

  <div class="preview-area">
    <div class="font-preview">Taste Bread</div>
  </div>

  <div class="font-bottom">

    <div class="license">
      Free Preview • MANU Fonts
    </div>

    <div class="actions">

      <button class="share"
        onclick="shareFont('Taste Bread')">
        ↗ Share
      </button>

      <button class="download"
        onclick="downloadMessage('Taste Bread')">
        ↓ Download
      </button>

    </div>

  </div>

</div>


<div class="font-card" data-category="bold editing" data-letter="S">

  <div class="font-head">
    <div class="font-name">Snowball</div>
    <div class="font-info">Editing • Bold</div>
  </div>

  <div class="preview-area">
    <div class="font-preview">Snowball</div>
  </div>

  <div class="font-bottom">

    <div class="license">
      Free Preview • MANU Fonts
    </div>

    <div class="actions">

      <button class="share"
        onclick="shareFont('Snowball')">
        ↗ Share
      </button>

      <button class="download"
        onclick="downloadMessage('Snowball')">
        ↓ Download
      </button>

    </div>

  </div>

</div>


<div class="font-card" data-category="techno english bold" data-letter="R">

  <div class="font-head">
    <div class="font-name">Relidux</div>
    <div class="font-info">Techno • English • Bold</div>
  </div>

  <div class="preview-area">
    <div class="font-preview">RELIDUX</div>
  </div>

  <div class="font-bottom">

    <div class="license">
      Free Preview • MANU Fonts
    </div>

    <div class="actions">

      <button class="share"
        onclick="shareFont('Relidux')">
        ↗ Share
      </button>

      <button class="download"
        onclick="downloadMessage('Relidux')">
        ↓ Download
      </button>

    </div>

  </div>

</div>


<div class="font-card" data-category="hindi stylish" data-letter="N">

  <div class="font-head">
    <div class="font-name">नमस्ते भारत</div>
    <div class="font-info">Hindi • Devanagari • Stylish</div>
  </div>

  <div class="preview-area">
    <div class="font-preview">नमस्ते भारत</div>
  </div>

  <div class="font-bottom">

    <div class="license">
      Hindi Preview • MANU Fonts
    </div>

    <div class="actions">

      <button class="share"
        onclick="shareFont('Hindi Font')">
        ↗ Share
      </button>

      <button class="download"
        onclick="downloadMessage('Hindi Font')">
        ↓ Download
      </button>

    </div>

  </div>

</div>

</section>


<div class="more">
  <button onclick="loadMore()">
    Load More Fonts
  </button>
</div>


<section id="faq">

<h2 class="section-title">
  About MANU Fonts
</h2>

<div style="padding:15px;border:1px solid #ccc;font-size:14px;line-height:1.7;">

  <b>MANU Fonts</b> एक font library है जहाँ Hindi,
  English और Editing fonts को आसानी से search,
  preview और share किया जा सकेगा।

  <br><br>

  नए fonts समय के साथ यहाँ जोड़े जाएंगे।

</div>

</section>

</main>


<footer class="footer">

  <div class="footer-inner">

    <b>MANU Fonts</b><br><br>

    Hindi • English • Editing Fonts

    <br><br>

    © 2026 MANU Fonts

  </div>

</footer>


<script>

function changeAllPreview(){

  let text =
    document.getElementById("customText").value;

  if(text.trim()===""){
    text="MANU Fonts";
  }

  document.querySelectorAll(".font-preview")
  .forEach(function(el){
    el.innerText=text;
  });

}


function changeSize(){

  let size =
    document.getElementById("fontSize").value;

  document.querySelectorAll(".font-preview")
  .forEach(function(el){
    el.style.fontSize=size+"px";
  });

}


function searchFonts(){

  let search =
    document.getElementById("searchInput")
    .value
    .toLowerCase()
    .trim();

  document.querySelectorAll(".font-card")
  .forEach(function(card){

    let text =
      card.innerText.toLowerCase();

    card.style.display =
      text.includes(search) ? "block" : "none";

  });

}


function filterCategory(category){

  document.querySelectorAll(".font-card")
  .forEach(function(card){

    if(category==="all"){
      card.style.display="block";
      return;
    }

    let categories =
      card.dataset.category || "";

    card.style.display =
      categories.includes(category)
      ? "block"
      : "none";

  });

}


function letterFilter(letter){

  document.querySelectorAll(".font-card")
  .forEach(function(card){

    let first =
      card.dataset.letter || "";

    card.style.display =
      first===letter ? "block" : "none";

  });

}


function resetFonts(){

  document.getElementById("searchInput").value="";
  document.getElementById("customText").value="MANU Fonts";

  document.querySelectorAll(".font-card")
  .forEach(function(card){
    card.style.display="block";
  });

  document.querySelectorAll(".font-preview")
  .forEach(function(el){
    el.innerText="MANU Fonts";
    el.style.fontSize="50px";
  });

}


function shareFont(font){

  let shareData = {
    title: font + " - MANU Fonts",
    text: "Check out " + font + " on MANU Fonts.",
    url: window.location.href
  };

  if(navigator.share){

    navigator.share(shareData)
      .catch(function(){});

  }else{

    navigator.clipboard.writeText(window.location.href);

    alert("Website link copy हो गया। अब आप इसे किसी को भी भेज सकते हैं।");

  }

}


function downloadMessage(font){

  alert(
    font +
    " का असली Download तभी शुरू होगा जब उसकी licensed font file MANU Fonts में जोड़ दी जाएगी।"
  );

}


function loadMore(){

  alert(
    "अगले चरण में यहाँ और fonts की पूरी library जोड़ी जाएगी।"
  );

}

</script>

</body>
</html>
