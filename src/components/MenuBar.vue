<template>
    <div class="menu">
        <div class="menu-item">
            Nicolas Zamorano
        </div>
        <div class="menu-item">
            LinkedIn
        </div>
        <div class="menu-item">
            About
        </div>
        <div class="menu-item">
            Real State App
        </div>
    </div>
</template>


<script>
export default {
    name: 'MenuBar',
    props: {
        msg: String
    }
}
</script>

  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.menu {
    display: flex;
    font-size: 75px;
    border-bottom: 2px white solid;
    background-color: rgb(43, 43, 43);
    align-items: center;
    justify-content: center;
}

.menu-item {
    margin: 15px;
    margin-right: 100px;
    padding-left: 25px;
    padding-right: 25px;
    border-radius: 25px;

}

.menu-item:hover {
    font-size: 80px;
    border: 1px solid rgba(17, 0, 255, 0.075);
    background-color: rgba(12, 12, 12, 0.411);
}
</style>