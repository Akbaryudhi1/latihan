<template>
    <div>
        <ul>
            <li>
                <img src="../assets/image-web-3-mobile.jpg" alt="Logo"/>
                <li>
                    <h1>The Bright Future of Web 3.0?</h1>
                </li>
                <li>we dive into the next evolution of the web that claims to put the power of the platforms back into the hands of the people. But is it really fulfilling its promise?</li>
                <li>
                    <h1>READ MORE</h1>
                </li>
            </li>
            <li class="samping">
                <h1>NEW</h1>
                <h2>Hydrogen VS Electric Cars</h2>
                <p>Will hydrogen-fueled cars ever catch up to EVs?</p>
                <h2>The Downsides of AI Artistry</h2>
                <p>What are the possible adverse effects of on-demand AI image generator?</p>
                <h2>Is VC Funding Drying Up?</h2>
                <p>Private funding by VC firms is down 50% YOY. We take a look at what that means.</p>
            </li>
        </ul>
    </div>
    <div>
        <ul>
            <li>
                <img src="../assets/image-retro-pcs.jpg" alt="Gambar 1">
            </li>
            <li>
                <h1>01</h1>
                <h2>Reviviing Retro PCs</h2>
                <p>What happens when old PCs are given modern upgrades?</p>
            </li>
            <li>
                <img src="../assets/image-top-laptops.jpg" alt="Gambar 2">
            </li>
            <li>
                <h1>02</h1>
                <h2>Top 10 Laptops of 2022</h2>
                <p>Our best picks for various needs and budgets.</p>
            </li>
            <li>
                <img src="../assets/image-gaming-growth.jpg" alt="Gambar 3">
            </li>
            <li>
                <h1>03</h1>
                <h2>The Growth of Gaming</h2>
                <p>How the pandemic has sparked fresh opportunities.</p>
            </li>
        </ul>
    </div>
</template>
<script>
import { defineComponent } from 'vue';
export default  defineComponent ({
    name: "Hero",
})
</script>
<style scoped>
ul {
    display: flex;
    justify-content: center;
}
li {
    list-style-type: none;
}
.samping {
    background-color: rgb(20, 99, 99);
}
</style>