<template>  
  <div style="margin: auto;" class="columns container is-multiline px-6 py-6 column is-full-mobile is-full-tablet is-full-desktop is-full-widescreen is-full-fullhd">
    <div
      v-for='item in items'
      :key='item._id'>
      <div style="" class="column is-narrow card mx-1 my-1">
        <div class="card-image conatiner">
          <figure style="justify-content: center;" class="image is-128x128">
            <img :src="item.image" alt="Placeholder image">
          </figure>
        </div>
        <div class="card-content">
          <div class="media is-left">
            <div class=" has-text-left">
              <p style="max-width: 128px; font-family: 'Rubik', sans-serif;" class="title is-size-6 ">{{item.name}}</p>
              <p class="subtitle is-size-6">{{item.harga}}</p>
            </div>
          </div>
          <div class="content">
            <div class="button is-warning">Add to chart</div>
          </div>
        </div>
      </div>
    </div>
  </div>   
    

</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');
</style>
<script>
var image_qtela = require('../assets/images/qtela.png');
var image_fernleaf = require('../assets/images/fernleaf.png');
export default {
  name: 'Home',
  props: {
    msg: String
  },
  data: function(){
    return{
      items: [
      { id: 1, name: 'Qtela Tempe Cabai Rawit 55g', harga: 'Rp. 12.000', image: image_qtela },
      { id: 2, name: 'Susu Fernleaf', harga: 'Rp. 7.700', image: image_fernleaf },
      { id: 3, name: 'Qtela Tempe Cabai Rawit 55g', harga: 'Rp. 12.000', image: image_qtela },
      { id: 4, name: 'Susu Fernleaf', harga: 'Rp. 7.700', image: image_fernleaf},
      { id: 5, name: 'Qtela Tempe Cabai Rawit 55g', harga: 'Rp. 12.000', image: image_qtela },
      { id: 6, name: 'Susu Fernleaf', harga: 'Rp. 7.700', image: image_fernleaf},
    ]
    }
  }
}
</script>
