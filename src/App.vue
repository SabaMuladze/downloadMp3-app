
<template>
  <div>
    <h1>MP3 Downloader</h1>
    <input v-model="url" placeholder="Enter MP3 URL" />
    <button @click="downloadMp3">Download</button>
  </div>
</template>

<script >
export default {
  data() {
    return {
      url:'',
    }
  },
  methods:{
   async downloadMp3(){

    }
  }
}
</script>


<style scoped>
div {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

input {
  margin-bottom: 10px;
  padding: 8px;
  width: 300px;
}

button {
  padding: 8px 16px;
}
</style>
