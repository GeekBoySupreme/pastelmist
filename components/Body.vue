<template>
  <div class='body'>
   <div class='container-1'>
     <div class='container'>
      <div class='row'>
        <div class='col-lg-12 col-md-12 col-sm-12'>
          <div class='headliner-text'>
            <b>Tired of <u>messy</u> Tabs?</b>
            <h2 class='lighter-text'>Save &amp; Launch lists of tabs with a Single Click</h2>

            <a class='add-to-chrome-color1'>
              <i class="fab fa-chrome"></i> <span>Coming Soon</span>
            </a>
          </div>
          <img class='img-fluid' src='../assets/tabtrum_ss.png'/>
          <p>&nbsp;</p>
        </div>
      </div>
    </div>
   </div>

  <div class='container-2'>
    <svg id="bigHalfCircle" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%" height="90" viewBox="0 0 100 100" preserveAspectRatio="none slice">
			<path d="M0 100 C40 0 60 0 100 100 Z"/>
    </svg>
    <svg id='bigRectangle' width="100%" height="300" viewBox="0 0 100 100" preserveAspectRatio="none slice">
      <rect width="100%" height="100" style="fill:#ffe8ba;stroke-width:3;stroke:#ffe8ba" />
    </svg>
    <div class='main-section'>
      <div class='container'>
        <div class='row'>
          <div class='col-lg-8 col-md-8 col-sm-8'>
            <h1>Whyyyyyyy ?</h1>
            <br />
            <h2>We built TabTrum to address one key problem we all face.</h2>
            <br />
            <h2 class='lighter-text'>Budget Device <i class="fas fa-arrow-right"></i> 20+ Open Tabs <i class="fas fa-arrow-right"></i> RAM Drained <i class="far fa-dizzy"></i>  <i class="fas fa-arrow-right"></i> Device Frozen <i class="fas fa-arrow-right"></i> You Sad <i class="fas fa-heart-broken"></i></h2> 
            <br />
            <br />
            <h2 class='text-kinda-light'>With TabTrum, you can 
              <br /><i class="fas fa-scroll"></i> open <b>n tabs (duh)</b>,
              <br /><i class="fas fa-shapes"></i> save them as a Snapshot when you're taking off,
              <br /><i class="fas fa-dove"></i> close the browser in peace,
              <br /><i class="fas fa-space-shuttle"></i> come back and launch all tabs at once !
            </h2>
            <br />
            <a class='add-to-chrome-color2'>
              <i class="fab fa-chrome"></i> <span>Coming Soon</span>
            </a>
          </div>
          <div class='col-lg-4 col-md-4 col-sm-4'>
            <div class='float-image-div'>
              <img class='float-image' src='../assets/tabtrum.png'/>
            </div>
          </div>
        </div>

        <div class='row'>
          <div class='col-lg-8 col-md-8 col-sm-8'>
            <br />
            <br />
            <h1>Suggestions &amp; Feedback</h1>
            <br />
            <h2 class='text-kinda-light'>Have a Feature Request? Want to report a bug?</h2>
            <h2 class='text-kinda-light'>Drop us a Message, or tweet <a href='https://twitter.com/tabtrumapp' target='blank' class='blue-name'>@tabtrumapp</a></h2>
            <br />
            <br />
            
          </div>
         
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<style>

.body .col-lg-6 {
  padding-top: 40px;
  margin-top: 20px;
}

.img-fluid {
  width: 100%;
  z-index: 10;
  animation: slideIn 0.7s;
}

.headliner-text {
  text-align: center;
  margin: 40px auto 5px auto;
  color:rgb(68, 68, 68);
}
.headliner-text b {
  font-size: 4vw;
  animation: slideIn 0.6s;
}

.main-section {
  width: 100vw;
  background: #ffe8ba;
  position: relative;
  margin-top: -10px;
  padding-top: 10vh;

  padding-bottom: 50px;
}
#bigHalfCircle path {
  fill: #ffe8ba;
	stroke: #ffe8ba;
}
#bigRectangle {
  margin-top: -10px;
}

.lighter-text {
  font-weight: 700;
  color: rgb(97, 97, 97);
}

.text-kinda-light {
  color: rgb(66, 63, 63);
}

.text-kinda-light i {
  color: #c0ae8b!important;
}

h2 .fas {
  font-size : 15px;
  color:rgb(94, 94, 94);
  margin: 0px 4px 0px 4px;
}

.fa-heart-broken {
  font-size: 20px!important;
  color: rgb(255, 109, 72)!important;
  margin: 0px 4px 0px 4px;
}


.container-1, .headliner-text, .img-fluid {
  z-index: 10;
}
.container-2 {
  z-index: 9;
  margin-top: -50vh;
}


.float-image {
  width: 100%;
  border-radius: 5px;
  margin: 30px auto;
}

.float-image-div {
  position: relative;
  /* animation: MoveUpDown 2s linear infinite; */
}

@media (min-width: 320px) and (max-width: 480px) {
  .headliner-text b {
    font-size: 8vw;
  }

  .container-2 {
    margin-top: -25vh;
  }

  .main-section {
    padding-top: 1vh;
    margin-top: -200px;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
  
  .container-2 {
    margin-top: -30vh;
  }

  .main-section {
    padding-top: 4vh;
  }
  
}

@media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
  
  .container-2 {
    margin-top: -30vh;
  }

  .main-section {
    padding-top: 1vh;
    margin-top: -100px;
  }
  
}

@keyframes slideIn {
  from {
    position: relative;
    opacity: 0;
    top: 5px;
  }
  to {
    opacity: 1;
    position: relative;
    top: 0px;
  }
}

@keyframes MoveUpDown {
  0%, 100% {
    bottom: 0;
  }
  50% {
    bottom: 10px;
  }
}






/* Add to Chrome Buttons */
.add-to-chrome-color1 {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 15px 30px;
  margin: 20px auto 5px auto;
  border-radius: 50px;
  background: #ff976e;
  width: 250px;

  cursor: pointer;
  transition: all 0.3s ease;
}
.add-to-chrome-color1 i, span {
  font-size: 20px;
  color: white;
}
.add-to-chrome-color1 span {
  margin-left: 10px;
  font-weight: 600;
  color: white!important;
}

.add-to-chrome-color1:hover {
  background: #ffa581;
}






.add-to-chrome-color2 {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 15px 30px;
  margin: 3px;
  border-radius: 50px;
  background: #ffdca7;
  width: 250px;

  cursor: pointer;
  transition: all 0.3s ease;
}
.add-to-chrome-color2 i, span {
  font-size: 20px;
  color: rgb(94, 94, 94);
}
.add-to-chrome-color2 span {
  margin-left: 10px;
  font-weight: 600;
  color: rgb(94, 94, 94);
}

.add-to-chrome-color2:hover {
  background: #ffd98d;
}
</style>
