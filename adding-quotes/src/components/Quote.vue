<template>
  <div class="col-xl-4 col-lg-4 col-md-6 col-sm-12 col-xs-12">
    <div class="panel panel-default">
      <div class="panel-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        props:['quotes']
    }
</script>

<style scoped>
  .panel-body{
    font-family:'Arizona',cursive;
    font-size: 24px;
    color:#6e6e6e;
  }
  .quote{
    cursor: pointer;
  }
  .quote:hover{
    background-color: #ffe2e2;
  }
</style>
