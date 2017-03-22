<template lang='pug'>
.call-button-component
  a.btn-floating.btn-large.waves-effect.waves-light.teal.lighten-2(@click='startCall')
    i.material-icons phone
</template>

<script>
import ua from '../asterisk'

export default {
  methods: {
    startCall () {
      console.log('startCall')

      // Invite with audio only
      ua.invite('salon', {
        media: {
          constraints: {
            audio: true,
            video: false
          }
        }
      })
    }
  }
}
</script>
