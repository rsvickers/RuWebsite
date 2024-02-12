<template>
  <div class="container-fluid">
    <section class="row">
      <div class="col-12">
        Ru is still sick so that sucks for me. While I am waiting I may start writing. But I am real busy with the play as
        well. I think we may be able to meet up this week!
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: clamp(500px, 50vw, 100%);

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
