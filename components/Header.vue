<template>
  <div class='header'>
    <div class='container'>
      <div class='row'>
         <div class='col-lg-12'>
            <div class='image-logo-component'>
              <!-- <img class="header-logo" src='../assets/tabtrum_128.png'/> -->
              <span class="header-text">TabTrum</span>
            </div>

            <a class='coffee-button-header'>
              <i class="fas fa-mug-hot"></i> <span>Buy me a Coffee</span>
            </a>
         </div>
      </div>
    </div>
  </div>
</template>

<style>
.header {
  width: 100vw;
  height: 70vh;
  position: relative;
  top: 0px;

  background: #f73e3f;
}

.coffee-button-header {
  float: right;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 15px 25px;
  margin: 3px;
  border-radius: 4px;
  background: rgba(255, 255, 255, 0.13);

  transition: all 0.5s ease;
}
.coffee-button-header i, span {
  font-size: 20px;
  color: rgb(46, 16, 16);
}
.coffee-button-header span {
  margin-left: 10px;
  font-weight: 500;
}

.coffee-button-header:hover {
  background: rgba(255, 255, 255, 0.26);
}



.image-logo-component {
  float: left;
  display: flex;
  justify-content: center;
  align-items: center;
}
.header-logo {
  width: 40px;
}
.image-logo-component span {
  /* margin-left: 10px; */
  color: hsl(0, 0%, 19%);
  font-size: 25px;
  font-weight: 700;
}



.image-logo-component, .coffee-button-header {
  margin-top: 30px;
}


@media (min-width: 320px) and (max-width: 480px) {
  
  .header {
    height: 100vh;
  }
  .coffee-button-header span {
    display: none;
  }
}
</style>
