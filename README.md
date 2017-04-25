<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
</style>
<body class="w3-light-grey w3-content" style="max-width:1600px">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-collapse w3-white w3-animate-left" style="z-index:3;width:300px;" id="mySidebar"><br>
  <div class="w3-container">
    <a href="#" onclick="w3_close()" class="w3-hide-large w3-right w3-jumbo w3-padding w3-hover-grey" title="close menu">
      <i class="fa fa-remove"></i>
    </a>
    <img src="img/selfi.jpg" style="width:45%;" class="w3-round"><br><br>
    <h1><b>林庭瑄</b></h1>
    <p class="w3-text-grey">Lin,Ting-Shaun</p>
	
	<p><i class="fa fa-briefcase fa-fw w3-margin-right w3-large w3-text-teal"></i>Designer</p>
    <p><i class="fa fa-home fa-fw w3-margin-right w3-large w3-text-teal"></i>Tainan, Taiwan</p>
    <p><i class="fa fa-envelope fa-fw w3-margin-right w3-large w3-text-teal"></i>lyfun0202@gmail.com</p>
    <p><i class="fa fa-phone fa-fw w3-margin-right w3-large w3-text-teal"></i>0928051947</p>
    <hr>
  </div>

  
  <div class="w3-bar-block">
    <a href="#portfolio" onclick="w3_close()" class="w3-bar-item w3-button w3-padding w3-text-teal"><i class="fa fa-th-large fa-fw w3-margin-right"></i>PORTFOLIO</a> 
    <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button w3-padding"><i class="fa fa-user fa-fw w3-margin-right"></i>ABOUT</a> 

  </div>
  <div class="w3-panel w3-xlarge">
    <a class="fa fa-facebook-official w3-hover-opacity w3-xlarge" href="https://www.facebook.com/profile.php?id=100001460737533"></a>
    <a class="fa fa-github w3-hover-opacity w3-xlarge" href="https://github.com/Lagrange1994"></a>


  </div>
</nav>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:300px">

  <!-- Header -->
  <header id="portfolio">
    <a href="#"><img src="img/selfi.jpg" style="width:65px;" class="w3-circle w3-right w3-margin w3-hide-large w3-hover-opacity"></a>
    <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-grey" onclick="w3_open()"><i class="fa fa-bars"></i></span>
    <div class="w3-container">
    <h1><b>My Portfolio</b></h1>
    <div class="w3-section w3-bottombar w3-padding-16">
      <button class="w3-button w3-white"></i>Graphic Design</button>
      <button class="w3-button w3-white "></i>UI Design</button>
      <button class="w3-button w3-white "></i>WEB Design</button>
    </div>
    </div>
  </header>
  
  <!-- First Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="img/work5.jpg" alt="NCKU Piano Club summer concert" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>NCKU Piano Club summer concert</h2>
        <p><b>Graphic Design</b></p>
        <p>為自己所參加的社團所辦的夏季音樂會，設計一連串周邊</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="img/work6.jpg" alt="Poster Design" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>Cyclon BMX new type publication</h2>
        <p><b>Poster Design</b></p>
        <p>修習系上商業編輯課程時，為BMX廠商設計新品發表活動海報</p>
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="img/work9.jpg" alt="Tech Coordinate(Card)" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>Tech Coordinate(Card)</h2>
        <p><b>Card Design</b></p>
        <p>利用課餘時間接的案子，為一間新創公司設計CIS，其中為名片設計部分</p>
		<p href=""></p>
      </div>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="img/work8.jpg" alt="Tainan Enterprises Culture & Art Foundation(Card)" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>Tainan Enterprises Culture & Art Foundation(Card)</h2>
        <p><b>Card Design</b></p>
        <p>在系上修習設計與品牌行銷時，為合作單位台南企業文化藝術基金會進行CIS設計時，製作的名片設計</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="img/work7.jpg" alt="Tainan Enterprises Culture & Art Foundation(DM)" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>Tainan Enterprises Culture & Art Foundation(DM)</h2>
        <p><b>DM Design</b></p>
        <p>在系上修習設計與品牌行銷時，為合作單位台南企業文化藝術基金會進行CIS設計時，製作的DM設計</p>
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="img/work4.jpg" alt="Tainan Enterprises Culture & Art Foundation(WEB)" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>Tainan Enterprises Culture & Art Foundation(WEB)</h2>
        <p><b>Website Design</b></p>
        <p>在系上修習設計與品牌行銷時，為合作單位台南企業文化藝術基金會進行CIS設計時，製作的網頁設計，以下為連結</p>
		<p href=""></p>
      </div>
    </div>
  </div>
  
    <!-- Third Photo Grid-->
  <div class="w3-row-padding">
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="img/work1.jpg" alt="ASUS IOT Workshop Project" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>ASUS Workshop Project</h2>
        <p><b>IOT UI mockup</b></p>
        <p>在大三下時參與了華碩來成大舉辦的工作坊，進行開發以聲音及音樂為核心的APP。

我們在兩天的工作坊中，開發出了以用戶根據喜好的音樂類別來進行交友配對的社群軟體介面。</p>
      </div>
    </div>
    <div class="w3-third w3-container w3-margin-bottom">
      <img src="img/work2.jpg" alt="Traveler Check" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>Traveler Check</h2>
        <p><b>Tour Management Platform</b></p>
        <p>Traveler Check為大四修習電機系的使用者介面設計與開發時的專案，為一個將想要旅行的人將零錢小額儲存進入帳戶，作為旅遊基金的網頁設計</p>
      </div>
    </div>
    <div class="w3-third w3-container">
      <img src="img/work3.jpg" alt="GO ART" onclick="onClick(this)" style="width:100%" class="w3-hover-opacity">
      <div class="w3-container w3-white">
	    <h2>GO ART</h2>
        <p><b>Art Project Fund-raising Platform</b></p>
        <p>GO ART為大四修習電機系的使用者介面設計與開發時練習前端設計時的提案，為一個讓藝術家進行提案，匯集對該藝術提案有興趣者資金的平台。</p>
      </div>
    </div>
  </div>
  
    <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-red w3-xlarge w3-display-topright">close</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>


  <!-- Images of Me -->
  <div class="w3-row-padding w3-padding-16" id="about">
    <div class="w3-col m6">
      <img src="img/selfi.jpg" alt="Me" style="width:100%">
    </div>

  </div>

  <div class="w3-container w3-padding-large" style="margin-bottom:32px">
    <h4><b>About Me</b></h4>
    <p>今年為大四生，就讀國立成功大學工業設計學系學士班，即將從學校畢業，將為往後的畢業製作與畢業後的設計工作有著期許與熱忱。
      在校期間認真學習設計領域的專業，培養獨立思考的能力，更在本科專業領域外，也嘗試學習其他學科領域的專業，例如程式設計，提升跨領域的能力。
      感謝您的撥冗閱讀，若有機會進入貴公司實習，定會努力表現，發揮自身專長</p>
    <hr>
    
	 <div class="w3-container w3-card-2 w3-white w3-margin-bottom">
	    <h2 class="w3-text-grey w3-padding-16"><i class="fa fa-asterisk fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Skills</h2>
          <div class="w3-third w3-container w3-margin-bottom w3-center">
		 	<img src="img/ps-01.jpg">
		    <div>
			<p><b>Photoshop<b></p>
		    </div>
		  </div>	

		  <div class="w3-third w3-container w3-margin-bottom w3-center">
            <img src="img/ai-01.jpg">
			<div>
            <p><b>Illustrator<b></p>
			</div>
		  </div>	

		  <div class="w3-third w3-container w3-margin-bottom w3-center">
            <img src="img/sketch-01.jpg">
			<div>
            <p><b>Sketch<b></p>
			</div>
		  </div>

		  <div class="w3-third w3-container w3-margin-bottom w3-center">
            <img src="img/html-01.jpg">
		    <div>
		    <p><b>Html<b></p>
		    </div>
		  </div>

		  <div class="w3-third w3-container w3-margin-bottom w3-center">
		  <img src="img/css-01.jpg">
		  <div>
		  <p><b>CSS<b></p>
		  </div>
		  </div>


		 
	 
	 
	 </div>
	
	 <div class="w3-container w3-card-2 w3-white w3-margin-bottom">
        <h2 class="w3-text-grey w3-padding-16"><i class="fa fa-suitcase fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Work Experience</h2>
        <div class="w3-container">
		  <img src="img/kdan.jpg">
		  <hr>
          <h5 class="w3-opacity"><b>UI/UX Intern / Kdan Mobile</b></h5>
          <h6 class="w3-text-teal"><i class="fa fa-calendar fa-fw w3-margin-right"></i>2016/7/1 - <span class="w3-tag w3-white w3-text-teal w3-round">2016/9/1</span></h6>
          <p>2016年暑假，我曾在台南的<a href="https://www.kdanmobile.com/zh-tw/">凱鈿行動科技</a>從事UI/UX實習，實習期間熟悉了ios與android的設計規範，與使用app annie進行分析</p>
		  <a href="https://drive.google.com/file/d/0B9G59LAQUG76UGhzVGhKOE1xYWc/view?usp=sharing" class="w3-text-grey">實習證書</a>
          <hr>
        </div>
        
      </div>
	
    <p>
      <button class="w3-button w3-dark-grey w3-padding-large w3-margin-top w3-margin-bottom">
        <i class="fa fa-download w3-margin-right"></i>Download Resume
      </button>
    </p>
    <hr>

    <!-- Pricing Tables -->
   
  </div>
  

  
  <div class="w3-black w3-center w3-padding-24">Design by Lin,Ting-Shaun</a></div>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
    document.getElementById("mySidebar").style.display = "block";
    document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
    document.getElementById("myOverlay").style.display = "none";
}
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

</script>

</body>
</html>
