<template >
    <div>
        <nav>
            <span>
                <img src="../assets/logo.svg" alt="Vue logo">
            </span>
            <ul>
                <li>Home</li>
                <li>New</li>
                <li >Popular</li>
                <li>Trending</li>
                <li>Categories</li>
            </ul>
        </nav>
    </div>
</template>
<script>
import { defineComponent } from 'vue';
export default defineComponent({
    name: "navbar",

})
</script>
<style scoped >
ul{
    display: flex;
    justify-content: space-between;
    width: 30%;
}
li{
    list-style-type: none;
    padding: 1rem 0;
    
}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: rgb(223, 100, 100);
    color: aquamarine;
}
    
</style>