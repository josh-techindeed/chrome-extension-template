<template>
  <div>
    <p>{{helloworld}}</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      helloworld: chrome.i18n.getMessage("helloWorld")
    }
  }
}
</script>

<style lang="scss" scoped>
p {
  font-size: 20px;
}
</style>
