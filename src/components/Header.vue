/* eslint-disable */
<template>
    <header>
        <h1>
            {{ title }}
        </h1>
    </header>
</template>

<script>
import ButtonX from './ButtonX'
export default{
    name: 'HeaderX',
    props: {
        title: String,
        
    },
    components:{
        ButtonX
    },
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>