<template>  
  <div style="margin: auto;" class="columns container is-multiline px-6 py-6 column is-full-mobile is-full-tablet is-full-desktop is-full-widescreen is-full-fullhd">
    <item-cart
      v-model="cart"
      :v-for="item in items"
      v-bind:key="item.id"
      v-bind:name="item.name"
      v-bind:harga="item.harga"
      v-bind:image="item.image"
    >
    </item-cart>
  </div>   
    

</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');
</style>

<script>
import ItemCart from '../components/ItemCart.vue';

var image_qtela = require('../assets/images/qtela.png');
var image_fernleaf = require('../assets/images/fernleaf.png');
export default {
  components: { ItemCart },
  name: 'Home',
  props: {
    msg: String
  },
  data: function(){
    return{
      cart: 0,
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
