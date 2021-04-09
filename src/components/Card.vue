<template>
  <div>
  <b-card-group deck>
    <b-card title="Centro Espírita Fé E Amor" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
      <template #footer>
        <small class="text-muted">01/04/2021</small>
      </template>
    </b-card>

    <b-card title="Centro Espírita Taquaritinga" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This card has supporting text below as a natural lead-in to additional content.
      </b-card-text>
      <template #footer>
        <small class="text-muted">01/04/2021</small>
      </template>
    </b-card>

    <b-card title="Centro Espírita Araraquara" img-src="https://picsum.photos/300/300/?image=41" img-alt="Image" img-top>
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This card has even longer content than the first to show that equal height action.
      </b-card-text>
      <template #footer>
        <small class="text-muted">01/04/2021</small>
      </template>
    </b-card>
  </b-card-group>
</div>
</template>

<style scoped>
.card-deck{
    padding: 0px;
    margin-top: 10px;
    margin-right: 0;
    margin-left: 0;
    margin-bottom: 10px;
}  
</style>

<script>
export default {
  name: 'Card',
}
</script>