<template>
    <li class="nav-item">
        <router-link class="nav-link" :to="href">
            <slot></slot>
        </router-link>
    </li>
</template>

<script type="text/ecmascript-6">
    export default {
        props: {
            href: { required: false }
        }
    }
</script>

<style scoped>
    .nav-item {
        margin: 0px 5px 0px 20px;
        list-style: none;
    }

    a.nav-link {
        font-size: 18px;
        padding: 18px;
        margin: 0px 5px;
        border-radius: 0px;
        
    }
</style>
