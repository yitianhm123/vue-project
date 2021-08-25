<template>
<ul id="array-rendering">
  <li :for="item in items" :key="item">
    {{ item.message }}
  </li>
</ul>  
</template>

<script>
// import {createApp} from 'vue'
// createApp({
export default {
 data() {
    return {
      items: [{ message: 'Foo' }, { message: 'Bar' }]
    }
  }
}
</script>

