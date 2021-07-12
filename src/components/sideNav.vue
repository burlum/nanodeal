<template>
    <div class=SideNav>
        <div class="logo"><i class='bi bi-list' @click="OpenSideNav()"></i><img src="../assets/logo.png"/><img class="avatar" src="../assets/avatar-2.png"></div>
        <div class="SideMenu">
            <div class="SideBar"><i class='bi bi-house-door-fill'></i><p>Dashboard</p></div>
            <div class="SideBar SideBarActive"><i class='bi bi-grid-fill'></i><p>Предложение</p></div>
            <div class="SideBar"><i class='bi bi-plus-square-fill'></i><p>Добавить новое</p></div>
            <div class="SideBar"><i class='bi bi-bar-chart-line-fill'></i><p>Статистика</p></div>
            <div class="SideBar"><i class='bi bi-person-circle'></i><p>Профиль</p></div>
            <div class="SideBar"><i class='bi bi-headset'></i><p>Поддержка</p></div>
            <div class="SideBar"><i class='bi bi-cash-stack'></i><p>Billing</p></div>
        </div>
    </div>
</template>
<script>
import $ from "jquery";
export default {
    name:"Sidenav",
    methods:{
        OpenSideNav:function(){
            if($(".SideMenu")[0].style.display!=="block")
            {
                $(".SideMenu")[0].style.display="block"
                $(".SideMenu")[0].style.position="absolute"
                $(".Info")[0].style.display="none"
            }else{
                $(".SideMenu")[0].style.display="none"
                $(".Info")[0].style.display="block"
            }
        }
    }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway&display=swap');
.SideNav{
    top:0;
    width:35vh;
}
.logo{
    text-align: center;
    margin-top: 4vh;
}
.SideBar>p{
    font-family: 'Raleway', sans-serif;
    font-weight: 500;
    margin-left:1.5vh;
    color: #2D3134;
    line-height:5vh;
    vertical-align: center;
}
.SideBar{
    display:flex;
    width:22vh;
    height:5.5vh;
    border:2px solid rgba(0,0,0,0);
    border-radius: 16px; 
    margin-left:3vh;
    margin-top:2vh;
    cursor:pointer;
}
.SideBar:hover{
    border:2px solid #FE8862;
}
.bi{
    font-size:2.5vh;
    line-height:5vh;
    vertical-align: center;
    color: #2D3134;
    margin-left:3vh;
}
.SideBarActive{
    background: #FE8862;
}
.SideBarActive>i,.SideBarActive>p{
    color: white;
}
.avatar{
    width:6vh;
    height:6vh;
    border-radius: 50%;
    display: none;
}
.bi-list{
    display: none;
}
@media(max-width:500px){
.SideNav{
    top:0;
    width:100%;
}
.SideBar{
    width:30vh;
    height:8vh;
    margin-left:3vh;
    margin-top:2vh;
    margin:2vh auto;
}
.SideBar>p{
    line-height:8vh;
    vertical-align: center;
}
.bi{
    font-size:3vh;
    line-height:8vh;
    vertical-align: center;
    margin-left:2vh;
}
.logo{
    position: absolute;
    width:100%;
    display: flex;
    justify-content: space-between;
}
.SideMenu{
    display:none;
    z-index: 9;
    margin-top:15vh;
    width:100%;
}
.avatar{
    display: block;
    margin:auto 4vh;
}
.bi-list{
    display:block;
    font-size: 5vh;
    margin:auto 4vh;
}
}
</style>