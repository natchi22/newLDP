<template>
    <div class="message-box">
        <div class="send-box">
          <h3 class="box-input">SEND US MESSAGE</h3>
          <div class="box-input pd-fullname">
            <p>Full Name</p>
            <input class="input-name" type="text" placeholder="Your Name" />
          </div>
          <div class="box-input">
            <p>Email</p>
            <input class="input-name" type="text" placeholder="Your Email" />
          </div>
          <div class="box-input">
            <p>Message</p>
            <input class="input-name input-message" type="text" placeholder="Your Message" />
          </div>
          <div class="box-input">
            <button class="bt bt-submit">SUBMIT</button>
          </div>
        </div>
      </div>
</template>
<style scoped>
.message-box{
    width: 60%;
}
.send-box{
    width: 540px;
    height: 800px;
    background: #FFFFFF;
    box-shadow: 5px 10px 50px rgba(16, 112, 177, 0.2);
    border-radius: 10px;
}
.send-box h3{
  color: #1F3F68;
  font-size: 20px;
  line-height: 30px;
  padding-top: 56px;
}
.box-input{
    width: 428px;
    margin: 0 auto;
}
.box-input p{
    padding: 32px 0 8px 0;
    font-size: 16px;
    line-height: 30px;
    letter-spacing: 0.04em;
    color: #1F3F68;
    opacity: 0.8;
}
.pd-fullname p{
    padding-top: 8;
}
.bt-submit{
    width: 428px;
    height: 72px;
    box-shadow: 5px 20px 50px rgba(16, 112, 177, 0.2);
    border-radius: 10px;
    background: #5A98D0;
    border-color:#5A98D0;
    margin-top: 72px;
}
.input-name{
    width: 428px;
    height: 72px;
    border: 1px solid #356EAD;
    box-sizing: border-box;
    border-radius: 10px;
    padding-left: 42px;
    opacity: 0.4;
    outline: none; 
}
.input-message{
    height: 144px;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.message-box{
  width: 388px;
}
.send-box{
  width: 388px;
}
.box-input{
  width: 307px;
}
.input-name{
  width: 307px;
}
.bt-submit{
  width: 307px;
}
}
@media screen and (max-width: 767px){
.message-box{
  width: 296px;
}
.send-box{
  width: 296px;
  height: 484px;
}
.box-input{
  width: 234px;
}
.input-name{
  width: 234px;
  height: 39px;
}
.bt-submit{
  width: 234px;
  height: 39px;
  margin-top: 30px;
}  
.input-message{
  height: 78px;
}
.box-input p{
  padding: 27px 0 0 0;
  font-size: 14px;
}
.send-box h3{
  padding-top: 30px;
  font-size: 16px;
}
}
</style>