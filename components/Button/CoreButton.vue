<template>
    <div>
        <button  class="bt bt-head">See Our Project</button>
        <button  class="bt bt-submit">SUBMIT</button>
        <button  class="bt bt-footer">Let’s Talk</button>
    </div>
</template>
<script>
export default {
    // props:{
    //     head:{
    //         type:String,
    //         required: true
    //     },
    //     submit:{
    //         type:String,
    //         required: true
    //     },
    //     footer:{
    //         type:String,
    //         required: true
    //     }
}
</script>
<style scoped>
/* button */
.bt{
    box-shadow: 0px 20px 50px rgba(16, 112, 177, 0.2);
    border-radius: 10px;
    background: #5A98D0;
    border-color:#5A98D0;
    color: #ffffff;
    font-size: 16px;
    line-height: 26px;
    letter-spacing: 0.04em;
    border: none;
    cursor: pointer;
    outline: none; 
}
.bt:focus{
    border: none;
}
.bt-head{
    width: 220px;
    height: 56px;
}
.bt-footer{
    width: 220px;
    height: 56px;
    margin-top: 72px;
}
/* end button */
</style>