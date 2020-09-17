<template>
    <div class="popular-top">
            <div class="popular-top-text">
                <h1>Feugiat sodales at nullam tellus.</h1>
                <p>Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit, sed do eiusmod tempor incididunt
                    ut labore et dolore magna aliqua. Mi posuere
                    nibh tempor fringilla porta pellentesque ipsum.</p>
                <div class="share">
                    <div class="text-share">
                        <h4>Samatha Leuthex</h4>
                        <h4 class="opa">May 5, 3 min read</h4>
                    </div>
                    <div class="img-share">
                        <img src="../../assets/imgblog/icon/bookmarks.png" alt="">
                        <img src="../../assets/imgblog/icon/share.png" alt="">
                    </div>
                </div>
            </div>
            <div class="imgbig">
                <img src="../../assets/imgblog/Feugiat.jpg" alt="">
            </div>
        </div>
</template>
<style scoped>
.popular-top{
    display: flex;
    flex-direction: row;
    width: 100%;
    margin: 0 auto;
    padding-top: 25px;
}
.popular-top-text h1{
    font-size: 48px;
    line-height: 58px;
    letter-spacing: 0.02em;
    color: #1F3F68;
}
.popular-top-text p{
    width: 100%;
    padding: 32px 0 76px 0;
    font-size: 16px;
    line-height: 26px;
    letter-spacing: 0.04em;
    opacity: 0.6;
    color: #000000;
}
.share{
    width: 300px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.text-share h4{
    padding: 0;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.04em;
    color: #1F3F68;
}
.img-share{
    width: 80px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.img-share img{
    width: 24px;
    height: 24px;
}
.opa{
    opacity: 0.4;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.popular-top{
    width: 704px;
}
.imgbig img{
    width: 396px;
    height: 279px;
}
}
@media screen and (max-width: 767px){
  
}
</style>