<template>
  <div class="about">
        <h1>Hello {{ their_name }}, this is Jayanth's about page</h1>
    <p>This is Jaynth’s To Do list developed in Vue.Js to learn Vue.Js</p>
  </div>
</template>

<script>
        export default {
          name: 'About',
          data() {
            return {
              their_name: this.$route.params.name
            }
          }
        }
        </script>