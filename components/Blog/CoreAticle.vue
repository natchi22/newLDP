<template>
  <div class="article-box">
    <div class="article-box-img">
      <img :src="aticle.image" alt />
    </div>
    <div class="text-article">
      <h2>{{aticle.title}}</h2>
      <p>{{aticle.content}}</p>
      <div class="all">
        <div class="text-all">
          <h4>{{aticle.name}}</h4>
          <h5>{{aticle.date}}</h5>
        </div>
        <div class="img-all">
          <img src="../../assets/imgblog/icon/bookmarks.png" alt />
          <img src="../../assets/imgblog/icon/share.png" alt />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["aticle"],
};
</script>
<style scoped>
/* article */
.article-box {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 869px;
  margin: 0 auto;
  margin-bottom: 22px;
}
.article-box-img {
  margin-right: 20px;
}
.img-all img {
  width: 24px;
  height: 24px;
}
.text-article {
  width: 550px;
}
.text-article h2 {
  width: 550px;
  font-weight: 600;
  font-size: 24px;
  line-height: 38px;
  letter-spacing: 0.02em;
  color: #1f3f68;
}
.text-article p {
  width: 539px;
  padding: 16px 0 14px 0;
  font-size: 16px;
  line-height: 26px;
  letter-spacing: 0.04em;
  color: rgba(0, 0, 0, 0.6);
}
.text-article h4 {
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.04em;
  color: #1f3f68;
}
.text-article h5 {
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.04em;
  color: rgba(0, 0, 0, 0.4);
}

.all {
  display: flex;
  flex-direction: row;
  width: 300px;
  justify-content: space-between;
}
.text-all {
  width: 120px;
}
.img-all {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  width: 80px;
}
/* end article */
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.article-box-img img{
  width: 242px;
  height: 161px;
}
.article-box{
  width: 713px;
}
.text-article{
  width: 455px;
}
.text-article h2{
  width: 455px;
}
.text-article p{
  width: 455px;
}
}
@media screen and (max-width: 767px){
  
}
</style>