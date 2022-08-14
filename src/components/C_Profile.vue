<template>
    <div class="card">
        <img src="../assets/pap.jpg" alt="pap me!">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi odio quas labore voluptate doloribus culpa veritatis, ducimus ipsum? Voluptatibus maiores enim laboriosam doloribus corporis sapiente possimus nam inventore, reiciendis sed!</p>
    </div>
</template>

<script>
    export default {
        name: 'C_Profile',
    }
</script>

<style scoped>
    .card{
        margin: 20px auto;
        background-color: antiquewhite;
        width: 600px;
        display: flex;
    }

    .card img{
        width: 300px;
    }

    .card p{
        text-align: left;
        padding-left: 20px;
    }
</style>