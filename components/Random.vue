<template>
  <view class="container">
    <text>Hello from Random Compoent</text>
    <text-input
      :style="{ height: 40, width: 200, borderColor: 'gray', borderWidth: 1 }"
    />
    <button title="Add To Do" />
  </view>
</template>

<script>
export default {
  name: "Random",
};
</script>
