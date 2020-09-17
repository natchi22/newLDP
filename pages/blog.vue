<template>
<div class="blog">
    <coreTitle :topic="blog"/>
    <coreSearch/>
    <div class="popular">
        <p>POPULAR</p>
        <corePopularMain/>
        <div class="popular-down">
            <corePopularBox :pop="boxpop1"/>    
            <corePopularBox :pop="boxpop2"/> 
            <corePopularBox :pop="boxpop3"/> 
        </div>
    </div>
    <div class="article">
        <p>ALL ARTICLE</p>
    <div>
        <coreAticle :aticle="all1"/>
        <coreAticle :aticle="all2"/>
        <coreAticle :aticle="all3"/>
        <coreAticle :aticle="all4"/>
        <coreAticle :aticle="all5"/>
    </div>
</div>
</div>

</template>
<script>
import CoreTitle from '@/components/Global/CoreTitle'
import CoreSearch from '@/components/Blog/CoreSearch'
import CorePopularMain from '@/components/Blog/CorePopularMain'
import CorePopularBox from '@/components/Blog/CorePopularBox'
import CoreAticle  from '@/components/Blog/CoreAticle'
export default {
    components:{
        CoreTitle,
        CoreSearch,
        CorePopularMain,
        CorePopularBox,
        CoreAticle
    },
    data(){
        return{
            all1:{
                image:require('../assets/imgblog/all1.jpg'),
                title:"Massa eu in laoreet enim augue vulputate nunc.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            all2:{
                image:require('../assets/imgblog/all2.jpg'),
                title:"Feugiat a euismod arcu feugiat posuere morbi.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            all3:{
                image:require('../assets/imgblog/all3.jpg'),
                title:"Sociis purus pellentesque faucibus vitae et felis..",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            all4:{
                image:require('../assets/imgblog/all4.jpg'),
                title:"Cursus feugiat mi pellentesque mauris sed eu.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            all5:{
                image:require('../assets/imgblog/all5.jpg'),
                title:"A morbi arcu curabitur etiam fringilla augue.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            boxpop1:{
                image:require('../assets/imgblog/Feugiat1.jpg'),
                title:"Porta proin tellus sed pulvinar odio eu pulvinar.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            boxpop2:{
                image:require('../assets/imgblog/Feugiat2.jpg'),
                title:"Non quam tortor, proin eu egestas scelerisque purus.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            boxpop3:{
                image:require('../assets/imgblog/Feugiat3.jpg'),
                title:"Amet amet sed pharetra risus sit eget interdum.",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lectus quisque magna in nisl nibh bibendum ipsum, elit duis. Donec.",
                name:"Samatha Leuthex",
                date:"May 5, 3 min read"
            },
            blog:{
                title:"Blog Afrianska",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. "
            },
            content:{
                title:"Contact Us",
                content:"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. "
            }
        }
    }
}
</script>
<style scoped>
.blog p{
    color: #356EAD;
    opacity: 0.8;
    font-size: 20px;
    line-height: 32px;
}
/* popular */
.popular{
    width: 948px;
    margin: 0 auto;
}
.popular-down{
    display: flex;
    justify-content: space-between;
}
/* end popular */
/* aticle */
.article {
  width: 869px;
  margin: 0 auto;
  margin-top: 48px;
  margin-bottom: 58px;
}
.article h3 {
  width: 869px;
  margin: 0 auto;
  margin-bottom: 25px;
}
/* end aticle */

@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.popular-down{
    width: 704px;
}
.popular{
    width: 704px;
}
.search{
    width: 704px;
}
.article{
    width: 713px;
}
}
@media screen and (max-width: 767px){
  
}
</style>