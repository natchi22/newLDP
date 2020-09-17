<template>
  <div class="footer">
    <div class="footer-top">
      <div class="box-footertop">
        <h2>
          Intersted to woek
          with our team?
        </h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit,
          sed do eiusmod tempor incididunt ut labore et dolore
          magna aliqua. Ut enim ad minim veniam.
        </p>
      </div>
      <div class="box-footertop box-size">
        <button class="bt bt-footer">Let’s Talk</button>
      </div>
    </div>
    <hr class="line-footer" />
    <div class="footer-down">
      <div class="box-footer">
        <div class="box1">
          <div class="box-icon">
            <img src="../../assets/icon/logodown.png" alt="โลโก้" />
            <h3>Afrianska</h3>
          </div>
          <p>
            A.Lorem ipsum dolor sit amet,
            consectetur adipisicing elit.
          </p>
          <p>T.+62-812-7313-4321</p>
          <p>E.hello.afrian@gmail.com</p>
          <p  class="add-text-p">2019 © Afrianska. All rights reserved.</p>
        </div>
        <div class="box2">
          <h4>About US</h4>
          <p>About</p>
          <p>What We Do</p>
          <p>Project</p>
          <p>How It Work With Us</p>
        </div>
        <div class="box2">
          <h4>Follow US</h4>
          <p>Instagram</p>
          <p>Facebook</p>
          <p>LinkedIn</p>
          <p>Youtube</p>
        </div>
      </div>
      <p class="add-text-p-hider">2019 © Afrianska. All rights reserved.</p>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
/* footer */
.footer{
    position: absolute;
    width: 100%;
    margin: 0 auto;
    background: #316099;
    border-radius: 0px 200px 0px 0px;
    color: #FFFFFF;
}
.footer-top{
    display: flex;
    flex-direction: row;
    width: 860px ; 
    margin: 0 auto;
    justify-content: space-between;
}
.box-footertop{
    width: 100%;
    padding-top: 90px;
}
.box-size{
    width: 220px;
}
.box-footertop h2{
    width: 317px;
    margin: 0;
    padding-bottom: 32px;
}
.box-footertop p{
    width: 460px;
    margin: 0;
    padding-bottom: 69px;
    opacity: 0.6;
}
.line-footer{
    width: 80%;
}
.bg-footer{
    background-color: #5A98D0;
    width: 100%;
    height: 200px;
    margin: 0 auto;
}
.xfooter2{
    padding: 0 0 16px 16px;
}
.add-text-p{
  opacity: 0.4;
}
.add-text-p-hider{
  opacity: 0.4;
  display: none;
}
/* end footer */
/* footer down */
.box-footer{
    display: flex;
    width: 745px;
    margin: 0 auto;
    justify-content: space-between;
    padding: 97px 0 64px 0;

}
.box-icon{
    display: flex;
    width: 100%;
    margin: 0 auto;
    align-items: center;
    padding-bottom: 33px;
}
.box-icon img{
    padding-right: 30px;
}
.box1 p{
    width: 290px;
    margin: 0 auto;
    padding-bottom: 24px;
}
.box2 h4{
    padding-bottom: 32px;
}
.box2 p{
    padding-bottom: 16px;
}
.xfooter2{
    padding: 0 0 16px 16px;
}
/* end footer down */
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.footer-top{
  width: 768px;
  flex-direction: column;
}
}
@media screen and (max-width: 767px){
.footer-top{
  width: 360px;
  flex-direction: column;
}  
.box-footertop p{
  width: 276px;
}
.box-footer{
  width: 360px;
  flex-direction: column;
}
.box1,.box2 p{
  width: 360px;
}
}
</style>