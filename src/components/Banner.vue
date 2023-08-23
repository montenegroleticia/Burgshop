<template>
    <div>
        <h2>BurgShop</h2>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
div {
    background-image: url('../../public/img/burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

h2 {
    color: #fff;
    text-align: center;
    font-size: 60px;
    margin-left: 80px;
}
</style>
