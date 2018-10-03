<template>
  <div class="about">
    <h1>Hello, {{ input_name }} </h1>
    <h1>This is an about page</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return { 
      input_name: this.$route.params.name
    }
  }  
}
</script>