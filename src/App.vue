<template lang='pug'>
#app
  .container
    .row
      .col.s3
        .card
          .card-image
            img(src='./assets/logo.png')
            span.card-title Card Title

            a.btn-floating.halfway-fab.waves-effect.waves-light.teal.lighten-2
              i.material-icons phone

          .card-content
            p I am a very simple card
</template>

<script>
import 'materialize-css/bin/materialize.css'
import 'materialize-css/bin/materialize.js'

export default {
  name: 'app'
}
</script>

<style>
</style>
