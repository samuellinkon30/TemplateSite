<template>
  <div class="global">
   <div class="contanier0">
    <h4>Home</h4>
   </div>
   <div class="container1">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet= Integer posuere erat. </p>
   </div>
     <div class="carousel">
      <b-carousel id="carousel1"
      style="text-shadow: 1px 1px 2px #333;"
      controls
      indicators
      background="#ababab"
      :interval="4000"
      img-width="1024"
      img-height="480"
      v-model="slide"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd">

      <b-carousel-slide>
       <img slot="img" class="d-block img-fluid w-100" width="1024" height="480"
       src="../assets/slide4.jpg" alt="image slot">
     </b-carousel-slide>

     <b-carousel-slide>
       <img slot="img" class="d-block img-fluid w-100" width="1024" height="480"
       src="../assets/slide2.jpg" alt="image slot">
     </b-carousel-slide>

     <b-carousel-slide>
       <img slot="img" class="d-block img-fluid w-100" width="1024" height="480"
       src="../assets/slide1.jpg" alt="image slot">
     </b-carousel-slide>

     <b-carousel-slide>
       <img slot="img" class="d-block img-fluid w-100" width="1024" height="480"
       src="../assets/slide3.jpg" alt="image slot">
     </b-carousel-slide>
     </b-carousel>
   </div>
    <div class="container2">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet= Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a a= Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet= Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a a= Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.Lorem ipsum dolor sit amet= Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a a= Integer posuere erat a ante.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.
      </p>
    </div>
  </div>

</template>

<script >
export default {
  data () {
    return {
      slide: 0,
      sliding: null
    }
  },
  methods: {
    onSlideStart (slide) {
      this.sliding = true
    },
    onSlideEnd (slide) {
      this.sliding = false
    }
  }
}
</script>

<style>
.carousel {
  opacity: 0.9;

}
.container1 {
 border-radius: 2px;
 background: white;
 opacity: 0.65;
 padding: 10px;
 text-align: center;
 font-size: 15px;
}

.container2 {
  border-radius: 2px;
  background: white;
  opacity: 0.65;
  padding: 10px;
  text-align: center;
  font-size: 15px;
}
.contanier0 {
  background: white;
  padding: 10px;
  opacity: 0.8;
  text-align: center;
  font-size: 15px;
}
@media screen and (min-width: 320px)
{
  .carousel
  {
    margin-top: 20px;
  }
}
</style>
