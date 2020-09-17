<template>
  <div class="boxdown">
    <img class="img-box1" :src="box.image" alt="รูปมือถือ" />
    <div class="gradient-down">
      <h3>{{box.title}}</h3>
      <p>{{box.content}}</p>
    </div>
  </div>
</template>
<script>
export default {
    props:['box']
}
</script>
<style scoped>
.boxdown{
    display: flex;
    flex-direction: row;
    position: relative;
    margin: 0 ;
    justify-content: space-between;
}
.boxdown p{
  opacity: 0.8;
}
.boxdown img{
    border-radius: 10px;
}
.img-box1{
    border-radius: 10px;
}
.gradient-down{
    background: linear-gradient(309.18deg, rgba(66, 165, 245, 0.4) -1.71%, rgba(21, 101, 192, 0.6) 74.54%);
    width: 422px;
    height: 417px;
    position: absolute;
    border-radius: 10px;
}
</style>