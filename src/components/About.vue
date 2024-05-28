<script setup>

</script>

<template>
    <div id="about-blurb">
        <h1 class="about-heading">Hi, I'm Nathan Tebbs</h1>
        <!-- <h3 class="about-blurb">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illo officiis odit sint beatae tempore repella</h3>    -->
        <span class="circle"></span>
    </div>
</template>

<style scoped>
#about-blurb {
    position: relative;
    text-align: center;
}

.circle {
    height: 350px;
    width: 350px;
    background-color: #bbb;
    border-radius: 50%;
    display:inline-block;
    background-image: url(
        '../assets/nathan2.jpeg'
    );
    background-size: cover;
}

.about-heading {
    font-size: 3rem;
}

.about-blurb {
    color: wheat;
}
</style>