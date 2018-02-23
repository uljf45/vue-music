<template>
  <div>{{rest}}</div>
</template>

<script>
const user = {
  name: '陈泽敏',
  age: new Date().getFullYear() - 1990
}
const {username, ...rest} = user
export default {
  name: 'test',
  data () {
    return {
      user,
      nums: [1, 2, 3, 4, 5, 6, 7, 8, 9, 0],
      rest
    }
  }
}
</script>

<style lang="stylus" scoped>

</style>
