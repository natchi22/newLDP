<template>
    <div class="search">
        <input class="inputtext" type="text" placeholder="Search Article">
    </div>
</template>
<style scoped>
.search{
    width: 940px;
    margin: 0 auto;
    padding: 56px 0;
}
.inputtext{
    width: 100%;
    margin: 0 auto;
    box-sizing: border-box;
    border: 0px none #F4F4F4;
    box-shadow: 0px 4px 8px rgba(49, 96, 153, 0.25);
    border-radius: 10px;
    background-color: #F4F4F4;
    background-image: url('../../assets/imgblog/icon/mag.png');
    background-position: 10px 10px; 
    background-repeat: no-repeat;
    padding: 12px 20px 12px 40px;
}
.inputtext:focus{
    outline: none; 
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.inputtext{
    width: 704px;
}
}
@media screen and (max-width: 767px){
  
}
</style>