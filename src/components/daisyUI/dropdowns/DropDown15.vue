<!-- Dropdown in navbar -->

<template>
<div class="navbar bg-base-300 rounded-box">
  <div class="flex-1 px-2 lg:flex-none">
    <a class="text-lg font-bold">daisyUI</a>
  </div>
  <div class="flex flex-1 justify-end px-2">
    <div class="flex items-stretch">
      <a class="btn btn-ghost rounded-btn">Button</a>
      <div class="dropdown dropdown-end">
        <div tabindex="0" role="button" class="btn btn-ghost rounded-btn">Dropdown</div>
        <ul
          tabindex="0"
          class="menu dropdown-content bg-base-100 rounded-box z-[1] mt-4 w-52 p-2 shadow">
          <li><a>Item 1</a></li>
          <li><a>Item 2</a></li>
        </ul>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'DropDown15'
}
</script>

<style>

</style>