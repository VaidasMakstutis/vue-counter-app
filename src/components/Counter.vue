<template>
  <div>
    <h2>The count is: {{ count }}</h2>
    <p>
      <button class="btn btn-secondary" @click="count += 5">Increment</button>
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return { count: 0 };
  }
};
</script>
