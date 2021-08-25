<template>

<div id="v-model-multiple-checkboxes">
  <input type="checkbox" id="jack" value="Jack" v-model="checkedNames" />
  <label for="jack">Jack</label>
  <input type="checkbox" id="john" value="John" v-model="checkedNames" />
  <label for="john">John</label>
  <input type="checkbox" id="mike" value="Mike" v-model="checkedNames" />
  <label for="mike">Mike</label>
  <br />
  <span>Checked names: {{ checkedNames }}</span>
</div>  
</template>

<script>
import {createApp} from 'vue'
createApp({
 data() {
    return {
      checkedNames: []
    }
  }
}).mount('#v-model-multiple-checkboxes')
   

// createApp.mount('#v-model-multiple-checkboxes')
</script>
