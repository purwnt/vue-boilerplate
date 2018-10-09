<template>
  <div class="app-layout">
    <navbar></navbar>

    <div class="container mt-4">
      <child/>
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import '@/assets/sass/app.scss'

require('jquery')
require('popper.js')

export default {
  name: 'app-layout',

  components: {
    Navbar
  }
}
</script>
