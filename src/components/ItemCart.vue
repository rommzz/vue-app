<template>  
  <div style="" class="column is-narrow card mx-1 my-1">
        <div class="card-image conatiner">
          <figure style="justify-content: center;" class="image is-128x128">
            <img :src="image" alt="Placeholder image">
          </figure>
        </div>
        <div class="card-content">
          <div class="media is-left">
            <div class=" has-text-left">
              <p style="max-width: 128px; font-family: 'Rubik', sans-serif;" class="title is-size-6 ">{{name}}</p>
              <p class="subtitle is-size-6">{{harga}}</p>
            </div>
          </div>
          <div class="content">
            <div class="button is-warning">Add to chart</div>
          </div>
        </div>
      </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');
</style>
<script>
export default {
  name: 'ItemCart',
  props: [
      'name',
      'harga',
      'image'
      
  ]
}
</script>