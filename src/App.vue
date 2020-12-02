<template>
  <div>
    <p>{{count}}</p>
    <button @click="myFn">按钮</button>
  </div>
</template>

<script>
  import { shallowRef } from 'vue'
export default {
  name: 'App',
  setup() {
    // 监听数据变化
    let count = shallowRef(10)
    function myFn() {

    }
  }
}
</script>
