<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ncechandi.ac.in</title>
  </head>
  
  <style>
    *{
    margin: 0;
    padding: 0;
}
header{
    display: block;
    flex-direction: column;
}
nav{
    display: flex;
    
}
.logo{
    display: flex;
    padding-left: 166px;
    
}
.line{
    padding-top: 20px;
    padding-left: 11px;
    font-family: 'Yanone Kaffeesatz', sans-serif;
    cursor: pointer;
}
.line2{
    padding-top: 33px;
    font-weight:lighter;
    font-size: 18px;
    
}
.line1{
    font-size: 24px;
}
.rightside{
    display: flex;
    padding-top: 65px;
    font-family: 'Yanone Kaffeesatz', sans-serif;
    font-size: 17px;
    margin-left: 346px;
    
}
.btn1{
    cursor: pointer;
    margin-right: 27px;
}

.btn2{
    cursor: pointer;
}
.bihar img{
    padding-top: 29px;
    padding-left: 23px;
}
.container{
     margin-top: 9px;
    height: 50px;
    width: 80%;
    padding-left: 161px;
    display: flex;
    justify-content: space-around;
    font-family: sans-serif;
    font-size: 15px;
    cursor: pointer;
}
.secondnav{
    
    z-index: 50;
    box-shadow: #f0c463;
    margin-top: 15px;
    height: 50px;
    width: 100%;
    background-color:#f0c463;
}
.container :nth-child(1){
    padding-top: 5px;
}
.box1{
    height: 500px;
    width: 65%;
    border: 1px solid rgb(242, 237, 237);
}
.box2{
    font-family: sans-serif;
    font-size: 16px;
    background-color: #f5f5f5;
    height: 40px;
    width: 35%;
    border: 1px solid rgb(242, 234, 234);
    padding-top: 13px;
    padding-left: 12px;
    font-weight: 600;
}
.box3{
    width: 35%;
    height: 460px;
    margin-left: 960px;
    margin-top: -445px;
    cursor: pointer;


}
.main{
    display: flex;
}
.parag{
    height: 231px;
    width: 100%;
    background-color:  rgba(72, 64, 64, 0.2);
}
.box4{
    height: 182px;
    width: 652px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    overflow: auto;
    margin-left: 600px;
    margin-top: 22px;
    padding-top: 45px;
}
.picm{
    
        margin-top: 15px;
        height: 225px;
        width: 100%;
        background-color:#f0c463;
        cursor: pointer;
        
}
.image{
    display: flex;
        justify-content: center;
        padding-top: 39px;
        box-sizing: border-box;
        
        
}
.foot{
    height: 545px;
    width: 100%;
    padding-top: 55px;
}


  </style>

  <body>
    <header>
      <nav>
        <div class="logo">
          <ul class="hidden-xs" style="list-style-type: none; position: absolute; top: -1px; right: 10px; left: 1001px; font-family: sans-serif; z-index: 50; font-size: 12px;">
            <li style="display: inline-block; vertical-align: top; margin-top: 5px;">Font Size:</li>
            <li style="display: inline-block; padding: 3px; vertical-align: top; background: #333; color: #fff;">
                <span style="font-size: 12px; cursor: pointer;" onclick="doIncreaseBodyFontSize()">A+</span>
            </li>
            <li style="display: inline-block; padding: 3px; vertical-align: top; background: #333; color: #fff;">
                <span style="font-size: 12px; cursor: pointer;" onclick="doDecreaseBodyFontSize()">A-</span>
            </li>
            <li style="display: inline-block; vertical-align: top; margin-top: 5px; margin-left: 5px;">Color Scheme:</li>
            <li style="display: inline-block; padding: 1px;"><span onclick="changeTheme('theme3.css')" style="display: inline-block; width: 25px; height: 25px; cursor: pointer; background-color: #285690;"></span></li>
            <li style="display: inline-block; padding: 1px;"><span onclick="changeTheme('default.css')" style="display: inline-block; width: 25px; height: 25px; cursor: pointer; background-color: #adca32;"></span></li>
            <li style="display: inline-block; padding: 1px;"><span onclick="changeTheme('theme1.css')" style="display: inline-block; width: 25px; height: 25px; cursor: pointer; background-color: #6E1A98;"></span></li>
            <li style="display: inline-block; padding: 1px;"><span onclick="changeTheme('theme2.css')" style="display: inline-block; width: 25px; height: 25px; cursor: pointer; background-color: #F0C463;"></span></li>
        </ul>
          <img height="100px" src="logo10.jpg" alt="">
             <div class="line">
               <div class="line1">
                Nalanda College Of Engineering
               </div>
              <div class="line2">
                  (Dept. Of Science And Technology,Govt Of Bihar)
               </div>
        </div>

              <div class="rightside">
                  <div class="btn1">Home</div>
                  <div class="btn2">Important Link </div>
                  <svg width="20px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                    </path>
                </svg>
                </div>
                <div class="bihar"><img height="55px" src="gov-bih-logo.png" alt=""></div>
      </nav>
      <nav class="secondnav">
        <div class="container">
          <ul><img height="15px" src="home2.png" alt="">Home</ul>
          <ul>About Us<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>Academics<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>Department<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>Facilities & Service<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>TEQUIP<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>T&P<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>Galery<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>Approaval<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
          <ul>Login<svg width="16px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 9L11.2929 14.2929C11.6262 14.6262 11.7929 14.7929 12 14.7929C12.2071 14.7929 12.3738 14.6262 12.7071 14.2929L18 9" stroke="#141B34" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
            </path>
        </svg></ul>
        </div>
      </nav>
    </header>
    <div class="main">
      <div class="box1"><img height="500px" width="100%" src="gatepic.png" alt=""></div>
      
      <div class="box2">Latest News/Updates</div>
      
    </div>
    <div class="box3"><img height="460px"  src="thirdbox.png" alt=""></div>
    <div class="notice">

      <a href="https://ncechandi.ac.in/notice-for-advertisement-for-guest-faculty-oct-2023/" target="_blank" rel="noopener"> Notice for Advertisement for Guest Faculty Oct 2023 </a>
    </div>
    <div class="parag">
      <div class="box4">

        Nalanda College OF Engineering (NCE), Chandi is One OF The Best New Government Engineering College . It is Under administrative Control of Department of Science and Technology and wholly Funded by Government of Bihar .Established in 2008 , It is Affiliated to Aryabhatta Knowledge University , Patna and offers undergraduate programs in engineering branches- computer science,civil engineering,mechanical engineering and electrical and electronics engineering with an intake of 60 per branch and 240 students in total.
      </div>
    </div>
    <div class="picm">
      <div class="image">

        <div class="img1"><img height="74%" src="fir.png" alt=""></div>
        <div class="img2"><img height="68%" src="seco.png" alt=""></div>
        <div class="img3"><img height="68%" src="thir.png" alt=""></div>
        <div class="img4"><img height="68%" src="fort.png" alt=""></div>
      </div>
    </div>
    <div class="foot">
      <img height="100%" width="100%" src="footer.png" alt="">
    </div>
  </body>
</html>
