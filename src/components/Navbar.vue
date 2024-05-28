<template>
    <nav>
        <ul>
            <li class="nabar-item">
                <router-link to="/">Home</router-link>
            </li>
            <li class="navbar-item">
                <router-link to="/about">About</router-link>
            </li>
            <li class="logo">
                <a href="https://github.com/nathantebbs" target="_blank">
                    <img src="../assets/github(1).png" alt="github">
                    <i class="fab fa-github"></i>
                </a>
            </li>
        </ul>
    </nav>
</template>


<style scoped>

nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color:#323232;
}

nav ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    display: 1;
    padding: 5px;
    margin: 5px;
    text-align: center;
    align-self: center;
}

a {
    color: wheat;
    font-weight: bold;
    font-size: 1.75rem;
}

a:hover {
    color: rgb(254, 193, 80)
}

.logo {
   flex: 0 0 auto;
   margin-left: auto;
}
</style>