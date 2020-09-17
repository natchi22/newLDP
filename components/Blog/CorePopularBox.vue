<template>
  <div class="popular-down-box">
    <img :src="pop.image"  />
    <h2>{{pop.title}}</h2>
    <h3>
      {{pop.content}}
    </h3>
    <div class="subtopic">
      <div class="text-subtopic">
        <h4>{{pop.name}}</h4>
        <h5>{{pop.date}}</h5>
      </div>
      <div class="img-share">
        <img src="../../assets/imgblog/icon/bookmarks.png" alt />
        <img src="../../assets/imgblog/icon/share.png" alt />
      </div>
    </div>
  </div>
</template>
<script>
export default {
    props:['pop']
}
</script>
<style scoped>
.popular-down-box h2{
    font-weight: 600;
    font-size: 24px;
    line-height: 32px;
    letter-spacing: 0.02em;
    color: #1F3F68;
}
.popular-down-box h3{
    font-size: 16px;
    line-height: 26px;
    letter-spacing: 0.04em;
    color: rgba(0, 0, 0, 0.6);
    margin: 35px 0 16px 0;
}
.text-subtopic h4{
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.04em;
    color: #1F3F68;
}
.text-subtopic h5{
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.04em;
    color: #1F3F68;
    color: rgba(0, 0, 0, 0.4);
    margin-bottom: 8px;
}
.popular-down-box{
    width: 300px;
    padding: 8px;
    cursor: pointer;
}
.popular-down-box:hover{
    box-shadow: 0px 0px 16px rgba(53, 110, 173, 0.25);
    border-radius: 5px;
    transform: scale(01.01);
    transition: 0.3s;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.popular-down-box{
  width: 222px;
}
.popular-down-box img{
  width: 222px;
}
.img-share img{
  width: 18px;
  height: 18px;
}
}
@media screen and (max-width: 767px){
  
}
</style>