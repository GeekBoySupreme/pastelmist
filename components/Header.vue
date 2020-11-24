<template>
  <div class='header'>
    <div class='container'>
      <div class='row'>
         <div class='col-lg-12'>
            <div class='image-logo-component'>
              <img class="header-logo" src='../assets/tabtrum_128.png'/>
              <span class="header-text">TabTrum</span>
            </div>

            <a class='coffee-button-header' href='https://chrome.google.com/webstore/detail/tabtrum/jhfphbjeobgkfkhjapgihmpgphcikgik?hl=en&authuser=0' target='blank'>
              <i class="fab fa-chrome"></i> <span>Add to Chrome</span>
            </a>
         </div>
      </div>
    </div>
  </div>
</template>

<style>
.header {
  width: 100vw;
  position: relative;
  top: 0px;

  display: flex;
  flex-direction: row;
  justify-content: center;
}

.coffee-button-header {
  float: right;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 15px 30px;
  margin: 3px;
  border-radius: 50px;
  background: #ff9268;

  cursor: pointer;
  transition: all 0.3s ease;
}
.coffee-button-header i, span {
  font-size: 20px;
  color: white;
}
.coffee-button-header span {
  margin-left: 10px;
  font-weight: 600;
  color: white;
}

.coffee-button-header:hover {
  background: #ffa784;
}



.image-logo-component {
  float: left;
  display: flex;
  justify-content: center;
  align-items: center;

  position: relative;
  top: 8px;
}
.header-logo {
  width: 50px;
}
.image-logo-component span {
  margin-left: 10px;
  color: rgb(83, 83, 83);
  font-size: 25px;
  font-weight: 700;
}



.image-logo-component, .coffee-button-header {
  margin-top: 30px;
}




@media (min-width: 320px) and (max-width: 480px) {
  
  .header {
    height: 15vh;
  }
  .coffee-button-header span {
    display: none;
  }

  .coffee-button-header {
    padding: 15px 15px;
  }
}
</style>
