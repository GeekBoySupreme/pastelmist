<template>
  <div class='footer'>
   <div class='container'>
     <div class='row'>
       <div class='col-lg-6 col-md-6 col-sm-6'>
         <h3>Copyleft - All Wrongs Reserved</h3>
         <p>&nbsp;</p>
         <h3>Made with <i class="fas fa-heart"></i> by <a href='https://twitter.com/shuvam360' target='blank' class='blue-name'>@shuvam360</a></h3>
         <p>&nbsp;</p>
         <p>&nbsp;</p>

         <div class='social-link-holder'>
            <a class='social-link' href='https://chrome.google.com/webstore/detail/tabtrum/jhfphbjeobgkfkhjapgihmpgphcikgik?hl=en&authuser=0' target='blank'>
              <i class="fab fa-chrome"></i> <span>Add to Chrome</span>
            </a>

            <a class='social-link' href='https://twitter.com/tabtrumapp' target='blank'>
                <i class="fab fa-twitter"></i>
            </a>
         </div>
         <p>&nbsp;</p>
         <p>&nbsp;</p>
       </div>

       <div class='col-lg-6 col-md-6 col-sm-6'>

         <h4 class='dark-text'>PS - <i class="fab fa-airbnb"></i> , <a href='https://airbnb.design' target='blank' class='blue-name'>airbnb.design</a> and associated entities belong to <a href='https://www.airbnb.co.in/' target='blank' class='blue-name'>Airbnb</a>.</h4>
         <h4 class='dark-text'>The Screenshot is solely for representational purposes.</h4>
         <p>&nbsp;</p>

         <h4 class='light-text'>Liked TabTrum?</h4>
         <h4 class='light-text'>We don't do Ads here. So please donate &amp; show your support</h4>
         <p>&nbsp;</p>
         <p>&nbsp;</p>
         <div class='social-link-holder'>
            <a class='social-link' href='https://paypal.me/ShuvamManna' target='blank'>
              <i class="fas fa-mug-hot"></i> <span>Buy me a Coffee</span>
            </a>
         </div>
       </div>
     </div>
   </div>
  </div>
</template>

<style>
.footer {
  width: 100vw;
  background: #545b6d;
  padding: 30px;

  position: relative;
  bottom: 0px;
}
.footer .col-lg-6 {
  padding-top: 20px;
}

h3 {
  color:#ffdea6;
  font-weight: 600;
}

.fa-heart {
  color: #ff615c;
  margin: 3px;
}

.blue-name {
  text-decoration: none;
  color: #84afff;
}







.social-link {
  margin-right: 3px;
  border-radius: 50px;
  background: #464e5c;
  width: 50px;
  height: 50px;
  padding: 15px 30px;

  cursor: pointer;
  transition: all 0.3s ease;
}
.social-link i, span {
  font-size: 20px;
  color: #d3d3d3;
}
.social-link span {
  margin-left: 10px;
  font-weight: 600;
  color: #d3d3d3;
}

.social-link:hover {
  background: #677085;
}

.social-link:nth-child(1) {
  padding: 15px 30px;
  margin-left: 0px;
}
.social-link:nth-child(2) {
  padding: 15px 17px;
}

.dark-text {
  color: #1a1e24;
}
.light-text {
  color: #ffdea6;
}

.social-link {
  margin-top : 15px;
}


@media (min-width: 320px) and (max-width: 480px) {
  .social-link-holder {
    width: 120%;
    margin-left: -10px;
  }
}
</style>
