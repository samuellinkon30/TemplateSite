<template>
  <div class="Global">
   <div class="NamePage">
    <h4>Services</h4>
  </div>
  <div class="Products-Services">
    <div class="Container">
      <img class="fts" src="../assets/solar1.jpg">

      <div class="Container-text">
       <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a</p>
     </div>
   </div>
   <div class="Container">
    <img class="fts" src="../assets/solar2.jpg">
    <div class="Container-text">
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a</p>
   </div>
 </div>
 <div class="Container">
  <img class="fts" src="../assets/solar3.jpg">
  <div class="Container-text">
   <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a</p>
 </div>
</div>
<div class="Container">
  <img class="fts" src="../assets/solar4.jpg">
  <div class="Container-text">
   <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a</p>
 </div>
</div>

</div>
</div>
</template>

<script >

</script>

<style>

.NamePage {
  background: white;
  padding: 10px;
  opacity: 0.8;
  text-align: center;
  font-size: 15px;
}
.Products-Services {
  background: white;
  padding: 10px;
  text-align: center;
  font-size: 15px;
}
.Container {
  margin-bottom: 20px;
  background: #D8D8D8;
  padding: 10px;
  text-align: center;
  font-size: 15px;
}
.Container-text {
  padding-top: 5px;
  text-align: center;
  font-size: 15px;
}
.fts {
  width: 100%;
  height: 250px;
}

@media only screen and (min-width: 900px)
{
  .Products-Services {
    background: white;
    padding: 10px;
    font-size: 15px;

  }
  .Container {
    margin-bottom: 20px;
    margin-left: 20%;
    margin-right: 20%;
    height: 400px;
    background: #D8D8D8;
    padding: 10px;
    text-align: center;
    font-size: 15px;
  }
  .Container-text {
    padding-top: 5px;
    text-align: center;
    font-size: 15px;
  }
  .fts {
    width: 100%;
    height: 90%;
  }
}
</style>
