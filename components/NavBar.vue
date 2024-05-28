<template>
    <div>
        <nav class="navbar">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a href="/">Home</a>
                </li>
                <li class="nav-item">
                    <a href="/about">About</a>
                </li>
                <li class="nav-item">
                    <a href="/services">Services</a>
                </li>
                <li class="nav-item">
                    <a href="/pricing">Pricing</a>
                </li>
                <li class="nav-item">
                    <a href="/contact">Contact</a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script setup>

</script>

<style scoped>
        .navbar {
        background-color: #333;
        padding: 10px;
    }

    .navbar-nav {
        list-style-type: none;
        margin: 0;
        padding: 0;
        display: flex;
    }

    .nav-item {
        margin-right: 15px;
    }

    .nav-link {
        color: #fff;
        text-decoration: none;
        font-weight: bold;
    }

    .nav-link:hover {
        text-decoration: underline;
    }
</style>