<template>
  <div class="columns is-multiline px-6">

    <div class="column card is-2">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="~@/assets/images/qtela.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="media is-left">
          <div class="media-content">
            <p class="title is-4">Susu fernleaf</p>
            <p class="subtitle is-6">Rp 7.700</p>
          </div>
        </div>
        <div class="content">
          <div class="button is-warning">Add to chart</div>
        </div>
      </div>
    </div>

    <div class="column card is-2">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="~@/assets/images/fernleaf.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="media is-left">
          <div class="media-content">
            <p class="title is-4">Qtela cabe rawit 55gr</p>
            <p class="subtitle is-6">Rp 12.000</p>
          </div>
        </div>

        <div class="content">
          <div class="button is-warning">Add to chart</div>
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
