<template>
  <div class="part3">
    <div class="box-part3">
      <div class="box-title">
        <h2>Our Finished Project</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing
          elit, sed do eiusmod tempor incididunt ut labore et
          dolore magna aliqua. Ut enim ad minim veniam.
        </p>
      </div>
      <div class="content-grid">
        <div class="grid-item">LOGO CLIENT 1</div>
        <div class="grid-item">LOGO CLIENT 2</div>
        <div class="grid-item">LOGO CLIENT 3</div>
        <div class="grid-item">LOGO CLIENT 4</div>
        <div class="grid-item">LOGO CLIENT 5</div>
        <div class="grid-item">LOGO CLIENT 6</div>
        <div class="grid-item">LOGO CLIENT 7</div>
        <div class="grid-item border-box">More Client</div>
      </div>
    </div>
  </div>
</template>
<style scoped>
/* part3 */
.part3{
    width: 100%;
    margin: 0 auto;
    background-color:  #5A98D0;
    border-radius: 200px 0 0 0;  
    color: #FFFFFF;
}
.box-part3{
    padding-bottom: 125px;
}
.box-title{
    display: flex;
    width: 940px;
    margin: 0 auto;
    justify-content: space-between;
    padding: 96px 0;
    margin-top: 123px;
}
.box-title h2{
    width: 224px;
    margin: 0;
    font-size: 36px;
    line-height: 46px;
    
}
.box-title p{
    width: 620px;
    margin: 0;
    font-size: 24px;
    line-height: 32px;
    opacity: 0.6;
}
.content-grid{
    display: grid;
    grid-template-columns:  repeat(4, 235px);
    grid-template-rows: repeat(2, 128px);
    width: 940px;
    margin: 0 auto;
    background-color: #fff;
    grid-gap: 1px;
}
.grid-item{
    background-color: #5A98D0;
    /* border: 1px solid #ffffff; */
    text-align: center;
    padding: 41px;
    border: 0px;
}
.border-box:hover{
    background: #1F3F68;
    opacity: 0.8;
    outline: none;
}
/* end part3 */
</style>