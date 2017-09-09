<template>
<nav class="navbar">
    <section>
        <button class="navbar-link">Button</button>
    </section>
</nav>
</template>

<style lang="scss">

$color-primary: #f44336;
$color-primary-light: #ff7961;
$color-primary-dark: #ba000d;
.navbar {
    position: fixed;
    top:0;
    height: 80px;
    width: 100%;
    background-color: $color-primary;
}

.navbar-link {
    min-height: 100%;
}
</style>


