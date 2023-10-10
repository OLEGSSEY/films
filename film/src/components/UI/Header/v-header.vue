<template>
    <div class="v-header">
        <div class="v-container">
            <div class="v-inner">
                <Logo />
                <Nav />
            </div>
        </div>
    </div>
</template>

<script>
import Logo from "./v-logo.vue";
import Nav from "./v-nav.vue";

export default {
    components: {
        Logo,
        Nav
    }
}

</script>

<style scoped>
.v-header {
    z-index: 9999;
    padding: 20px;
    background: #292929;
}
</style>