<!-- Modal using anchor link -->

<template>
<!-- The button to open modal -->
<a href="#my_modal_8" class="btn">open modal</a>

<!-- Put this part before </body> tag -->
<div class="modal" role="dialog" id="my_modal_8">
  <div class="modal-box">
    <h3 class="text-lg font-bold">Hello!</h3>
    <p class="py-4">This modal works with anchor links</p>
    <div class="modal-action">
      <a href="#" class="btn">Yay!</a>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Modal8'
}
</script>

<style>

</style>