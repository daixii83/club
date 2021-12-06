<template lang="pug">
#update
  p 最近更新日期 {{ date }}
</template>

<script>
export default {
  name: 'Update',
  data () {
    return {
      date: new Date().toLocaleDateString()
    }
  }
}
</script>
