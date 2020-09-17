<template>
    <div class="title">
        <img src="../../assets/imgblog/Mask.jpg" alt="title">
        <div class="title-text">
            <h1>{{topic.title}}</h1>
            <p>{{topic.content}}</p>
        </div>
    </div>
</template>
<script>
export default {
    props:['topic']
}
</script>
<style scoped>
.title{
    position: relative;
    color: #FFFFFF;
}
.title img{
    width: 100%;
    margin: 0 auto;
}
.title-text{
    width: 100%;
    position: absolute;
    top: 60px;
    text-align: center;
}
.title-text h1{
    font-size: 44px;
    line-height: 74px;
}
.title-text p{
    width: 780px;
    margin: 0 auto;
    padding-top: 50px;
    opacity: 0.4;
    font-size: 20px;
    line-height: 30px;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.title-text p{
    width: 547px;
}
}
@media screen and (max-width: 767px){
.title-text p{
    width: 280px;
}  
}
</style>