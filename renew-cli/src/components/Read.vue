<template>
  <div>
    <table>
      <tr :key="index" v-for="(value,index) in data">
        <td>{{ value.writer }}</td>
        <td>{{ value.title }}</td>
        <td>{{ value.content }}</td>
      </tr>
    </table>
    <button @click="write">글쓰기</button>
    <create/>
  </div>
</template>

<script>
import data from '@/data'
export default {
  name: 'Read',
  data () {
    return {
      data:data
    }
  },
  methods: {
    write() {
      this.$router.push({
        path: 'create'
      })
    }
  }
}
</script>

<style>

</style>