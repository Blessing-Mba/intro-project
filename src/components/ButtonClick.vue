<template>
     <button @click="handleClick" class="btn">
              Learn More
            </button>
</template>

<script>
   export default {
  name: 'MyButton',
  methods: {
    handleClick() {
      alert('Button clicked!');
    }
  }
}
</script>

<style scoped>
.btn{
  height: 3rem;
  width: 9rem;
  background: #000;
  color: #fff;
  margin-left: 5rem;
  margin-top: -1rem;
  border-radius: 0.5rem;
}
</style>