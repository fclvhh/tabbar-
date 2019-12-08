<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name:"TabBar"
}

</script>
<style>
 #tab-bar {
    position: fixed;
    width: 100%;
    height:49px;
    bottom: 0px;
    left: 0px;
    display:flex;
    justify-content: space-around;
    background-color: #f6f6f6;
    align-items: center;
    box-shadow: 0px -5px 1px rgba(100,100,100,0.08); 
  }

</style>