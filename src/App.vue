<template>
  <div id="app">
    <div class="container">
      <div class="row mt-4 mb-4">
        <div class="col">
          <h1 class="text-center text-uppercase"><b>Asanteit Exam</b></h1>
        </div>
      </div>      
      <div class="row">
        <div class="col">
          <router-view />
        </div>
      </div>
    </div>    
  </div>
</template>

<style lang="scss">
  h1{
    padding: 10px;
    background-color: #30aba5;
    color: white;
  }
  body{
    margin: 0px;
    padding: 0px;
  }
</style>
