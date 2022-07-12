<template>
    <div class="title">ElecTrap 樂齡挑戰</div>
    <p>Start Your Game</p>
    <div class="ButtonForm">
    <input type="button" value="hands" onclick="javascript:location.href='hands.html'">
    <br>
    <br>
    <input type="button" value="head" onclick="window.alert('此區域尚未開發')" >
    <br>
    <br>
    <input type="button" value="foot" onclick="window.alert('此區域尚未開發')">
  </div>
</template>

<script>
export default {
    name:'IndexButton',
    props: {
        msg: String
    }
}
</script>

<style>
    .title{
        font-family:'Comic Sans MS','LiHei Pro';
        font-size:70px;
        color: rgb(255, 255, 255);
        /*background-color: rgb(51, 51, 51);*/
        text-shadow: rgb(255, 255, 255) 0px -1px 4px, rgb(255, 255, 0) 0px -2px 10px, rgb(255, 128, 0) 0px -10px 20px, rgb(255, 0, 0) 0px -18px 40px;
    }
    .ButtonForm {
    position:fixed;
    top:300px;
    left:630px;
    }

    p {
        font-family:'Comic Sans MS';
        font-size:45px;
        position:fixed;
        top:175px;
        left:590px;
        font-weight: bolder;
        color: rgba(255, 255, 255, 0.7);
        text-shadow: rgba(255, 255, 255, 0.5) 0px 0px 15px, rgba(255, 255, 255, 0.5) 0px 0px 10px;
        }
    input {
        box-shadow: -6px 6px 0 hsl(201, 80%, 21%);
        border-radius: 20%;
        background-color:rgb(193, 220, 235); 
        height:100px; 
        width:300px; 
        font-size: 50px;

    }
    input:hover{
        color:aliceblue;
        background-color: #9876
    }
    #bg {
    background: url("~@/assets/flash.jpg") center center no-repeat;
    min-height: 100vh;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    z-index: -999;
    }
</style>