<template lang='pug'>
#app
  call-button
</template>

<script>
import 'materialize-css/bin/materialize.css'
import 'materialize-css/bin/materialize.js'

import CallButton from './components/CallButton'

export default {
  name: 'app',
  components: {
    CallButton
  }
}
</script>

<style>
html,
body,
#app {
  height: 100%;
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
