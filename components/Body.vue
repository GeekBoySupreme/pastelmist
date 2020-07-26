<template>
  <div class='body'>
   <div class='container-1'>
     <div class='container'>
      <div class='row'>
        <div class='col-lg-12 col-md-12 col-sm-12'>
          <div class='headliner-text'>
            <b>Tired of <u>messy</u> Tabs?</b>
            <h2 class='lighter-text'>Save & Launch a list of tabs with a Single Click</h2>
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
          <div class='col-lg-8'>
            
            <h1>Whyyyyyyy ?</h1>
            <br />
            <h2>We built TabTrum to address one of the key problems we were facing.</h2>
            <br />
            <h2 class='lighter-text'>Budget Device <i class="fas fa-arrow-right"></i> 20+ Open Tabs <i class="fas fa-arrow-right"></i> RAM Drained <i class="far fa-dizzy"></i>  <i class="fas fa-arrow-right"></i> Device Frozen <i class="fas fa-arrow-right"></i> You Sad <i class="fas fa-heart-broken"></i></h2> 
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
    padding-top: 1vh;
    margin-top: -100px;
  }
  
}

@media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
  
  .container-2 {
    margin-top: -30vh;
  }

  .main-section {
    padding-top: 1vh;
    margin-top: -200px;
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
</style>
