<template>
    <div class="container">
      <div> <slot name="header"></slot> </div>
      <div> <slot name="main"></slot> </div>
      <div><slot name="footer"></slot></div>
    </div>
</template>

<script>
    export default {
      name: 'Container'
    }
</script>
