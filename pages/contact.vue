<template>
  <div>
    <coreTitle :topic="contact" />
    <div class="contact">
      <coreAddress />
      <coreMessage/>
    </div>
    <coreMap class="map"/>
  </div>
</template>
<script>
import CoreTitle from "@/components/Global/CoreTitle";
import CoreAddress from "@/components/Contact/CoreAddress";
import CoreMessage from "@/components/Contact/CoreMessage";
import CoreMap from "@/components/Contact/CoreMap"
export default {
  components: {
    CoreTitle,
    CoreAddress,
    CoreMessage,
    CoreMap
  },
  data() {
    return {
      contact: {
        title: "Contact Us",
        content:
          "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ",
      },
    };
  },
};
</script>
<style scoped>
.contact{
    width: 940px;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    margin-top: 57px;
}
.contact h3{
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.04em;
    color: #1F3F68;
    padding: 24px 0;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.contact{
  width: 688px;
  justify-content: space-between;
}
.map{
  width: 702px;
}
}
@media screen and (max-width: 767px){
.contact{
  width: 296px;
  flex-direction: column;
}
.map{
  width: 328px;
}  
}
</style>