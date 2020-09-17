<template>
    <div class="addess-box">
        <img class="addess-img" src="../../assets/imgcontact/contact.jpg" alt />
        <div class="addess">
          <h3>ADDRESS</h3>
          <p>
            Id convallis placerat sit sed duis id
            amet volutpat quam a, pharetra.
          </p>
        </div>
        <div class="cell">
          <h3>PHONE</h3>
          <div class="icon-contact">
            <img src="../../assets/imgcontact/icon/phone.png" alt />
            <p>+62-812-7313-4321</p>
          </div>
          <div class="icon-contact">
            <img src="../../assets/imgcontact/icon/phone.png" alt />
            <p>+62-817-000-1234</p>
          </div>
        </div>
        <div class="cell">
          <h3>ONLINE SERVICE</h3>
          <div class="icon-contact">
            <img src="../../assets/imgcontact/icon/language.png" alt />
            <p>www.afrianska.com</p>
          </div>
          <div class="icon-contact">
            <img src="../../assets/imgcontact/icon/email.png" alt />
            <p>hello.afrian@gmail.com</p>
          </div>
        </div>
      </div>
</template>
<style scoped>
.addess-box{
    width: 40%;
    margin-top: 63px;
}
.addess-box h3{
  color: #1F3F68;
  font-size: 20px;
  margin-top: 40px;
}
.addess-box p{
    font-size: 16px;
    line-height: 26px;
    letter-spacing: 0.04em;
    color: #1F3F68;
}
.addess h3{
    padding-top: 31px;
}
.addess p{
    opacity: 0.6;
    width: 299px;
    /* margin-top: 24px; */
}
.cell h3{
  margin-bottom: 24px;
}
.icon-contact{
    display: flex;
    flex-direction: row;
    opacity: 0.6;
    padding-bottom: 16px;
}
.icon-contact img{
    margin-right: 16px;
}
@media screen and (min-width: 1280px ){

}
@media screen and (max-width: 1279px ) and (min-width: 768px ){
.addess-box{
  width: 260px;
}
}
@media screen and (max-width: 767px){
.icon-contact p{
  width: 160px;
}
.icon-contact{
  width: 200px;
}
.cell h3{
  width: 163px;
}
}
</style>