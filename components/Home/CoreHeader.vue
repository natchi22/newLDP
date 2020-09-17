<template>
<div class="bg-img">
    <div class="bg-head">
            <div class="title">
                <h1>New Automation
                    Tool for Your Home</h1>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing
                    elit. Faucibus tristique vulputate ultrices ut mauris
                    tellus at. Posuere sollicitudin odio tellus elit.</p>
                <coreButton />
            </div>
    </div>
</div>
</template>
<script>
import CoreButton from '@/components/Button/CoreButton'
export default {
    props:{
        head:{
            type:String,
            required: true
        },
        submit:{
            type:String,
            required: true
        },
        footer:{
            type:String,
            required: true
        }
    },
    components:{
        CoreButton
    }
}
</script>
<style scoped>
.bg-img{
    width: 100%;
    height: 688px;
    background-image: url('../../assets/home/header.jpg');
    background-repeat: no-repeat;
    background-position: top 100px left 95%;
}
.bg-head{
    width: 100%;
    background: linear-gradient(0deg, rgba(152, 195, 232, 0.2)  8.84%, rgba(152, 195, 232, 0) 31.12%);
    height: 688px
}
.title{
    width: 995px;
    padding: 115px 0 0 168px;
    margin: 0 auto;
    color: #1F3F68;
}
.title h1{
    width: 542px;
    margin: 0;
    font-size: 56px;
    line-height: 74px;
}
.title p{
    width: 425px;
    margin: 0;
    padding: 32px 0 72px 0;
    opacity: 0.6;
    font-size: 16px;
    line-height: 26px;
}
</style>