<template>
  <Layout>
    <g-image alt="Example image" src="~/favicon.png" width="135" />
    <h1>Hello, world!</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores</p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Clean and Simple Sites - Websites For the Rest of Us - Home',
    meta: [
      { name: 'description', content: 'This is the awesome Clean and Simple Sites website!' }
    ]
  }
}
</script>

<style lang="scss">
    $primary-color: blue;
    
    p {
      color: $primary-color;
    }
</style>
