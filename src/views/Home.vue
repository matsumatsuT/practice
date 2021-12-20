<template>
    <div class="home">
        <MyHeader />
        <Base />
        <MyFooter />
    </div>
</template>

<script>
import MyHeader from '@/components/MyHeader.vue'
import Base from '@/components/base.vue'
import MyFooter from '@/components/MyFooter.vue'

export default {
    name: 'Home',
    components: {
        MyHeader,
        Base,
        MyFooter,
    }
}
</script>

<style lang="scss" scoped>
.home {
    background: #fff;
}
</style>
