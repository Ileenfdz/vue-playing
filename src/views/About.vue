<template>
  <div class="about">
    <HelloVue/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloVue from '@/components/HelloVue.vue'

export default {
  name: 'About',
  components: {
    HelloVue
  }
}
</script>
