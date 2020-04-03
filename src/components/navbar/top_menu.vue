<template>
    <fixed-nav-bar brand="OIH">
    </fixed-nav-bar>
</template>

<script type="text/ecmascript-6">
    import FixedNavBar from '@/components/navbar/fixed_navbar.vue'
    export default {
        components: {
            FixedNavBar
        },
        props: {
            href: { required: false },
            active: { default: false }
        }
    }

</script>
