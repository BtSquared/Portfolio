<template>
    <div>
        <h2 class="nav">Tanner Mitchell</h2>
        <div class="nav">
            <a href="https://www.linkedin.com/in/tanner-mitchell/">LinkedIn</a>
        </div>
        <div class="nav">
            <a href="https://github.com/BtSquared">Github</a>
        </div>
        <div class="nav">
            <h4>Contact Info</h4>
            <div>TannerTMitchell@gmail.com</div>
            <div>832-725-7969</div>
            <a :href="`${publicPath}TannerMitchellResume.pdf`" download="TannerMitchellResume">Download my Resume</a>
        </div>
        
    </div>
</template>

<script>
export default {
    name: "NavBar",
    data: () => ({
    publicPath: process.env.BASE_URL
    })
}
</script>

<style scoped>
a {
    text-decoration: none;
    color: rgb(237, 237, 237);
}
h4 {
margin: 30px 15px 5px 0;
}
.nav {
margin: 15px;
color: rgb(237, 237, 237);
}
</style>