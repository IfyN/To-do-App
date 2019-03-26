<template>
  <div class="about">
  <h1>Hello {{their_name}}, About page </h1>
  <p> This is a To do App</p>
  </div>
  </template>

<script>
export default {
  name: 'skills',
  data () 
  {
  return {
    their_name: this.$route.params.name

}
  
  }
}

</script>