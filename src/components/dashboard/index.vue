<template>

</template>

<script>
import studentBoard from './student-dashboard'
import teacherBoard from './teacher-dashboard'
import adminBoard from './admin-dashboard'
export default {
  name: "index",
  components: {
    studentBoard, teacherBoard, adminBoard
  },
  data () {
    return {
      userInfo: {}
    }
  },
  created () {
    this.userInfo = JSON.parse(localStorage.userInfo);
  }
}
</script>

<style scoped>
</style>
