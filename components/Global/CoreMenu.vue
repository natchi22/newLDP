<template>
    <div>
        <div class="topbar">
            <div class="">
                <img src="../../assets/icon/logo.png" alt="logotop">
            </div>
            <ul class="menubar">
                <li>
                    <a href="index.html" class="f-menubar">
                        HOME
                    </a>
                </li>
                <li>
                    <a href="blogpage.html" class="f-menubar">
                        BLOG
                        </a>
                    </li>
                <li>
                    <a href="contact.html" class="f-menubar">
                        CONTAT US
                        </a>
                </li>
            </ul>
        </div>
        <div class="topbar-nav">
            <div class="">
                <img src="../../assets/icon/logo.png" alt="logotop">
            </div>
            <div>
                <span class="bt-open-nav" onclick="openNav()">&#9776;</span>
            </div>
            <div class="menubar-nav" id="mySidenav">
                <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a><br><br>
                <a href="index.html" class="f-menubar">
                    HOME
                </a>
                <hr class="line">
                <a href="blogpage.html" class="f-menubar">
                    BLOG
                </a>
                <hr class="line">
                <a href="contact.html" class="f-menubar">
                    CONTAT US
                </a>
            </div>
        </div>
    </div>
</template>
<script>
closeNav()
        function openNav() {
            document.getElementById("mySidenav").style.width = "240px";
        }

        function closeNav() {
            document.getElementById("mySidenav").style.width = "0px";
        }
export default {
    
}
</script>
<style scoped>

</style>