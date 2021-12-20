<template>
    <main>
        <Philosophy />
        <Instagram />
        <News />
        <Access />
    </main>
</template>

<script>
import Instagram from '@/components/Instagram.vue'
import Philosophy from '@/components/Philosophy.vue'
import News from '@/components/News.vue'
import Access from '@/components/Access.vue'

export default {
    name: 'Base',
    components: {
        Instagram,
        Philosophy,
        News,
        Access,
    }
}
</script>