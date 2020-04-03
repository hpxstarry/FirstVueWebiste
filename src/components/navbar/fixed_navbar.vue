<template>
    <div>
        <nav class="navbar navbar-inverse navbar-static-top" style="z-index: 10">
            <div class="container-fluid">
                <div class="collapse navbar-collapse" aria-expanded="false" id="main-menu">
                    <ul class="nav navbar-nav navbar-left">
                        <img id="brand-img" alt="OIH" src="@/assets/logo.png">
                        <nav-router-link href="/home"><i class="fa fa-server"></i>&nbsp;Home</nav-router-link>
                        <nav-router-link href="/create"><i class="fa fa-server"></i>&nbsp;Create</nav-router-link>
                        <nav-router-link href="/search"><i class="fa fa-question"></i> Search</nav-router-link>
                        <nav-router-link href="/help"><i class="fa fa-user-circle-o"></i>&nbsp;Help</nav-router-link>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script type="text/ecmascript-6">
    import NavRouterLink from '@/components/navbar/nav_router_link.vue'

    export default {
        components: {
            NavRouterLink
        },
        props: {
            brand: { default: 'Brand' },
            routes: { default: false }
        }
    }

</script>

<style scoped>
    nav {
        padding: 0px 15px;
    }

    div.spacing {
        padding-bottom: 70px;
    }

    .navbar-header {
        margin-right: 10px;
    }

    #brand-img {
        display: inline-block;
        height: 56px;
        line-height: 56px;
    }

    
    li {
        display: inline-block;
        margin: 0 10px;
    }
</style>
