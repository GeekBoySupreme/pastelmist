<template>
  <div>
      <Header />
      <Body />
      <Footer />
  </div>
</template>

<script>
export default {}
</script>

<style>
html {
  font-family: 'Nunito', sans-serif;
  overflow-x:hidden;
}

.img-fluid {
  width: 100%;
}
  /*------- Scrollbar --------------*/
  html::-webkit-scrollbar {
    width: 0.3rem;
  }
  
  html::-webkit-scrollbar-track {
    background: rgba(49, 49, 49, 0.075);
  }
  
  html::-webkit-scrollbar-thumb {
    background: #5d7bff;
    width: 0.3rem;
    border-radius: 20px;
  }

</style>
