<template>
  <div>
    <p>
      HEY! It is the home page! :D
    </p>
  </div>
</template>

<script>
import utils from '../utils'

export default {
  created: function () {
    utils.clearTitle()
  }
}
</script>
