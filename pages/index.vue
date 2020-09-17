<template>
  <div>
    <coreHeader />
    <div class="part1">
      <div class="box-part1">
        <div class="box-flex">
          <div class="title-part1">
            <h2>
              What we do to help
              our client grow in
              digital era,
            </h2>
          </div>
          <corePart1 :core="core1" />
        </div>
        <div class="box-flex">
          <corePart1 :core="core2" />
          <corePart1 :core="core3" />
        </div>
      </div>
    </div>
    <corePart2 />
    <corePart3/>
  </div>
</template>
<script>
import CoreHeader from "@/components/Home/CoreHeader";
import CorePart1 from "@/components/Home/CorePart1";
import CorePart2 from "@/components/Home/part2/CorePart2";
import CorePart3 from "@/components/Home/CorePart3";
export default {
  components: {
    CoreHeader,
    CorePart1,
    CorePart2,
    CorePart3,
  },
  data() {
    return {
      core1: {
        image: require('../assets/home/01make.jpg'),
        title:'Make Your business To Be Better Famous In Internet',
        content:'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.'
      },
      core2: {
        image: require('../assets/home/02bring.jpg'),
        title:'Bring Technology To Your Comfrotable Home',
        content:'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.'
      },
      core3: {
        image: require('../assets/home/03build.jpg'),
        title:'Build Your Digital Product That Suitable For Your Need',
        content:'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.'
      }
    }
  },
};
</script>
<style scoped>
/* part1 */
.part1 {
  width: 100%;
  margin: 0 auto;
}
.box-part1 {
  display: flex;
  width: 802px;
  margin: 0 auto;
  padding-top: 160px;
}
.title-part1 {
  width: 358px;
  margin: 0 auto;
  padding-bottom: 120px;
  color: #316099;
  /* font-size: 36px !important; */
  line-height: 46px;
}
.box {
  width: 380px;
  height: 525px;
  margin: 0 40px 37px 0px;
  border: 1px solid #c4c4c4;
  transition: 0.5s;
  border-radius: 10px;
  cursor: pointer;
}
.box img {
  display: flex;
  justify-content: center;
  margin: 0 auto;
}
.box:hover {
  box-shadow: 5px 20px 50px rgba(16, 112, 177, 0.2);
}
.box h3 {
  width: 284px;
  margin: 0 auto;
  padding-bottom: 16px;
}
.box p {
  width: 284px;
  margin: 0 auto;
}
.box-flex {
  width: 801px;
  margin: 0;
  justify-content: space-between;
}
.box-vector {
  width: 284px;
  margin: 0 auto;
  padding-top: 32px;
}
.vector {
  display: flex;
  flex-direction: row;
  width: 130px;
  height: 30px;
  margin: 0;
  justify-content: space-between;
  align-items: center;
}
.vector a {
  text-decoration: none;
  color: #5a98d0;
}
/* end part1 */
/* part2 */

/* end part2 */
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.box-part1{
  flex-direction: column;
}
.box{
  margin: 0 auto;
  margin-bottom: 64px;
}
}
@media screen and (max-width: 767px){

}
</style> 

