<template>
  <div class="columns is-mobile is-multiline px-6">
    <div class="column card is-2">
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="~@/assets/images/qtela.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="media is-left">
          <div class="media-content">
            <p class="title is-4">John Smith</p>
            <p class="subtitle is-6">@johnsmith</p>
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
        <div class="media">
          <div class="media-left">
            <figure class="image is-48x48">
              <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
            </figure>
          </div>
          <div class="media-content">
            <p class="title is-4">John Smith</p>
            <p class="subtitle is-6">@johnsmith</p>
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
