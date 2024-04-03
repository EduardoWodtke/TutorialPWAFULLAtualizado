<script setup>
    import SmallHeader from '../components/templates/small/SmallFooter.vue'
    import SmallFooter from '../components/templates/small/SmallHeader.vue'
</script>
<template>
    <header>
        <SmallHeader/>
    </header>
    <main>
        <RouterView/>
    </main>
    <footer>
        <SmallFooter/>
    </footer>
</template>