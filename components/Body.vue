<template>
  <div class='body'>
   <div class='container-1'>
     <div class='container'>
      <div class='row'>
        <div class='col-lg-12 col-md-12 col-sm-12'>
          <div class='headliner-text'>
            <b>Tired of <u>messy</u> Tabs?</b>
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
          <div class='col-lg-12'>
            Knock knock
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
}

.headliner-text {
  text-align: center;
  margin: 40px auto 5px auto;
  color:rgb(68, 68, 68);
}
.headliner-text b {
  font-size: 4vw;
}

.main-section {
  width: 100vw;
  background: #ffe8ba;
  position: relative;
  margin-top: -10px;
  padding-top: 15vh;
}
#bigHalfCircle path {
  fill: #ffe8ba;
	stroke: #ffe8ba;
}
#bigRectangle {
  margin-top: -10px;
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
</style>
