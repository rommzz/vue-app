<template>
  
  <div class="columns px-5 py-5 is-multiline is-flex">  
    <div :v-for="n in 3" class="column is-flex is-one-fifth py-1">
      <div class="card is-vcentered">
        <div>
          <figure class="image is-128x128 py-2 px-3" style="margin: auto;">
            <img src="~@/assets/images/qtela.png" alt="">
          </figure>
        </div>
        <div class="px-2" style="font-family: Rubik, Sans-serif; font-weight: bold">
          Qtela Tempe Cabai Rawit 55gr
        </div>
        <div class="buttons is-centered py-3" >
          <b-button class="" style="
            display: block;
            border-radius: 12px;
            background-color: #d63b30;
            color: #fff;
            font-size: 0.8125em;
            line-height: 1em;
            font-weight: 500;
            text-align: center;
            text-decoration: none;
            ">Add To Chart</b-button>
        </div>
      </div>    
    </div>
  </div>
  
  
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>
