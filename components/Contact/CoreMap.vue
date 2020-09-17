<template>
    <div class="map">
        <iframe class="box-map" 
            src="https://www.google.com/maps/embed?pb=!1m10!1m8!1m3!1d8237.922593022467!2d98.9515724740228!3d18.79351075313022!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sth!2sth!4v1596369423074!5m2!1sth!2sth" >
        </iframe>
    </div>
</template>
<style scoped>
/* map */
.map{
    width: 960px;
    height: 420px;
    margin: 0 auto;
    padding:  96px 0;
}
.box-map{
    width: 960px;
    height: 420px;
    border: none;
    padding: 0 0 96px 0;
}
/* end map */
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.box-map{
    width: 702px;
    height: 420px;
}
}
@media screen and (max-width: 767px){
.box-map{
    width: 328px;
    height: 420px;
}  
}
</style>