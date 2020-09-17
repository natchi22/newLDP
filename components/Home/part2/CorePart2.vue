<template>
    <div class="part2">
        <div class="part2-boxtop">
            <h2>Our Finished Project</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing
                elit, sed do eiusmod tempor incididunt ut labore et
                dolore magna aliqua. Ut enim ad minim veniam.</p>
        </div>
        <div class="part2-box">
            <img class="img-box" src="../../../assets/home/home.jpg" alt="รูปบ้านยาว">
            <div class="gradient-box">
                <img class="img-box  sizeicon-box" src="../../../assets/home/Mask Group.png" alt="รูปไอคอน">
            </div>
            <div class="text-box">
                <h3>Smart Home Installation</h3>
                <p>In Muarakana Housing Estate</p>
            </div>

        </div>
        <div class="part2-boxdown">
            <coreBoxcar :box="phone" />
            <coreBoxcar :box="car" />
        </div>
    </div>
</template>
<script>
import CoreBoxcar from "@/components/Home/part2/CoreBoxcar";
export default {
    components:{
        CoreBoxcar
    },
    data(){
        return{
            phone: {
                image:require('../../../assets/home/phone.jpg'),
                title:"Sparklite App",
                content:"Marketplace"
            },
            car:{
                image:require('../../../assets/home/car.jpg'),
                title:"Car-Rapetition App",
                content:"Board"
            }
        }
    }
}
</script>
<style scoped>
.part2{
    width: 100%;
    margin: 0 auto;
    margin-top: 189px;
    color: #FFFFFF;
}
.part2 p{
    opacity: 0.8;
}
.part2-boxtop{
    display: flex;
    width: 940px;
    margin: 0 auto;
    justify-content: space-between;
    padding: 0 0 96px 0;
    color: #1F3F68;
}
.part2-boxtop h2{
    width: 235px;
    /* width: 100%; */
    margin: 0;
    font-size: 36px;
    line-height: 46px;
}
.part2-boxtop p{
    width: 620px;
    /* width: 100%; */
    margin: 0;
    opacity: 0.6;
    font-size: 24px;
    line-height: 32px;
}
.part2-boxdown{
    display: flex;
    flex-direction: row;
    width: 940px;
    justify-content: space-between;
    margin: 0 auto;
}
.part2-box{
    width: 940px;
    margin: 0 auto;
    position: relative;   
    margin-bottom: 96px;
}
.img-box{
    width: 100%;
    border-radius: 10px;
}
.gradient-box{
    background: linear-gradient(89.97deg, #1F3F68 3.62%, rgba(31, 63, 104, 0.37) 97.78%);
    width: 100%;
    position: absolute;
    top: 0;
    border-radius: 10px;
    height: 98%;  
}
.sizeicon-box{
    width: 381px;
    height: 374px;
    padding-top: 44px;
}
.text-box{
    width: 100%;
    position: absolute;
    top: 48px;
    right: 49px;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.part2-boxtop{
    flex-direction: column;
}
}
@media screen and (max-width: 767px){
  
}
</style>