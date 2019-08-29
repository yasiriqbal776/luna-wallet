<template>
    <div id="whole-container">
        <div class="side-bar">
            <page-sidebar/>
        </div>
        <div class="right-container">
            <div class="topmost-container">
                <page-header/>
                <router-view />
            </div>
        </div>
    </div>
</template>

<script>
    import Header from "./Header/Header";
    import Sidebar from "./Sidebar/Sidebar";

    export default {
        name: "Dashboard",
        components: {
            'page-header':Header,
            'page-sidebar':Sidebar,
        }
    }
</script>

<style scoped>

</style>