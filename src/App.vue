<template>
  <MDXProvider>
    <Home />
  </MDXProvider>
</template>

<script>
import {MDXProvider} from '@mdx-js/vue'
import Home from './pages/Home.mdx'

export default {
  name: 'app',
  components: {
    Home,
    MDXProvider
  },
  data() {
    return {
    }
  }
}
</script>
