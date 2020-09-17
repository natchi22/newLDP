<template>
    <div class="box">
        <img :src="core.image" alt="รูป1">
        <h3>
            {{core.title}}
        </h3>
        <p>
            {{core.content}}
        </p>
        <div class="box-vector">
            <div class="vector">
                <a href="#">Learn more</a>
                <img src="../../assets/icon/Vector.png" alt="ลูกศร">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    props: ['core']
}
</script>
<style scoped>
.box{
    width: 380px;
    height: 525px;
    margin: 0 40px 37px 0px;
    border: 1px  solid #C4C4C4;
    transition: 0.5s;
    border-radius: 10px;
    cursor: pointer;
    color: #1F3F68;
}
.box:hover{
    box-shadow: 5px 20px 50px rgba(16, 112, 177, 0.2);
}
.box h3{
    width: 284px;
    margin: 0 auto;
    padding-bottom: 16px;
    font-size: 20px;
    line-height: 30px;
}
.box p{
    width: 284px;
    margin: 0 auto;
    font-size: 16px; 
    line-height: 26px;
    opacity: 0.6;
}
.box-vector{
    width: 284px;
    margin: 0 auto;
    padding-top: 32px;
}
.vector{
    display: flex;
    flex-direction: row;
    width: 130px;
    height: 30px;
    margin: 0 ;
    justify-content: space-between;
    align-items: center;
}
.vector a{
    text-decoration: none;
    color: #5A98D0;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){

}
@media screen and (max-width: 767px){
  
}
</style>>

