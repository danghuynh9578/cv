<template>
    <div class="wrapper">
      <div class="container">
        <div class="box">
          <left />
          <right />
        </div>
        <test />
      </div>
    </div>
</template>

<script>
import left from './left'
import right from './right'
import test from './menu-right'
export default {
  name: 'HelloWorld',
  components: {
    left,
    right,
    test
  },
  data () {
    return {
    }
  }
}
</script>
