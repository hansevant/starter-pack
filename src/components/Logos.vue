<template>
    <h1> Find Best Logos</h1>
    <div class="logos-wrapper">
        <div class="item-logos">
            <img src="https://seeklogo.com/images/S/starbucks-logo-BFBFE6C3A3-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/A/Absolut_Vodka-logo-3244BFB46E-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/H/halal-malaysia-logo-83E58494C7-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/H/halal-malaysia-logo-83E58494C7-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/M/mcdonald-s-logo-1E9F99D2ED-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/U/uber-eats-logo-CA3BA2098B-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/S/skol_do_site-logo-76D82908A5-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/C/Coca-Cola-logo-D3CE7D7110-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/M/monster-energy-logo-5733774FD9-seeklogo.com.png" alt="">
        </div>
        <div class="item-logos">
            <img src="https://seeklogo.com/images/H/Hard_rock_Cafe-logo-7F8FE3C3ED-seeklogo.com.png" alt="">
        </div>
    </div>
</template>

<script>
    export default {
        name: 'C-Logos',
    }
</script>

<style scoped>

    *{
        /* outline: 1px solid red; */
    }

    .logos-wrapper {
        width: 1360px;
        /* overflow: hidden; */
        flex-wrap: wrap;
        display: flex;
        margin: auto;
        background-color: cadetblue;
        justify-content: center;
    }

    .item-logos {
        width: 150px;
        height: 150px;
        /* float: left; */
        margin: 20px;
        padding: 10px;
    }

    .item-logos:nth-child(odd){
        background-color: darkseagreen;
    }
    .item-logos:nth-child(even){
        background-color: darksalmon;
    }

    .item-logos img {
        width: 150px;
        height: 150px;
        object-fit: contain;
        object-position: center;
    }
</style>