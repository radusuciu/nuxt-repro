<template>
  <div>
    <div>hi {{ name }}</div>
    <input type="text" :value="name" />
  </div>
</template>

<script>
export default {
  data: () => ({
    name: 'tester',
    wat: 'lol',
  }),
};
</script>
