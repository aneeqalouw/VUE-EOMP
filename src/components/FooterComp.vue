<template>
<div class="container-fluid bg-dark text-white" id="footer">
  
  <p class="d-flex justify-content-center">Copyright &copy; {{ year }}. All rights reserved</p>
</div>
</template>

<script>
export default {
  data() {
    return {
      // getting the current year to be displayed in the footer
      year: new Date().getFullYear(),
    };
  },
};
</script>

<style scoped>
#footer{
  height: 30px;
}
</style>
