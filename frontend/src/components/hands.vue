<template>
    <div id="iframe">
        <iframe frameborder="0"
            noresize="noresize"
            src="http://127.0.0.1:5000">
        </iframe>
    </div>
</template>

<script>
import IndexButton from './components/IndexButton.vue'
export default {
  name: 'HandsModel',
  components: {
    IndexButton
  }
}


</script>

<style>
    /*#bg {
    background: url("~@/assets/flash.jpg") center center no-repeat;
    min-height: 100vh;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    z-index: -999;
    }*/

    #iframe {
        display:block;
        width: 100%; height:100%;
        background: transparent;
        position:fixed;  
        top:60px;
        left:450px;
    }
</style>