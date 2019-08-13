<template>
  <div>
    <div>{{ name }}</div>
    <div>{{ name }}</div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      name: 'cherish',
      objects: [{ id: 1 }, { id: 1 }, { id: 1 }],
      names: 123
    }
  },
  methods: {
    haha() {
      const data = this.objects.map(item => item)
      console.log(data)
    }
  }
}
</script>
