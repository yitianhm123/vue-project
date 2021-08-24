<template>
  <div>
    <input v-model="message" />
    <p>关联显示信息{{message}} </p>

  </div>
</template>

<script>
    export default{
        data(){
            return {
                message : "i am king"
            }
        }
    } 
</script>