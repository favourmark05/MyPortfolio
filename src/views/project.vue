<template>
  <div>
    <MyProjects />
  </div>
</template>

<script>
// @ is an alias to /src
import MyProjects from '@/components/MyProjects.vue'

export default {
  name: 'Home',
  components: {
    MyProjects
  }
}
</script>
