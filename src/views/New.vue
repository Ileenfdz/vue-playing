<template>
  <div class="about">
    <HelloNew/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloNew from '@/components/HelloNew.vue'

export default {
  name: 'About',
  components: {
    HelloNew
  }
}
</script>