<script>
    import { defineComponent } from 'vue'

    // Layout
    import Header from '@/components/layout/AppHeader.vue'
    import Footer from '@/components/layout/AppFooter.vue'

    // Global
    import Marquee from '@/components/global/GlobalMarquee.vue'
    import Background from '@/components/global/GlobalBackground.vue'
    import CTAs from '@/components/global/GlobalFixedCTAs.vue'
    import Button from '@/components/global/GlobalButton.vue'

    // Sections
    import Hero from '@/components/sections/SectionHero.vue'
    import LatestContent from '@/components/sections/SectionLatestContent.vue'
    import ServicesList from '@/components/sections/SectionServicesList.vue'
    import SideProjects from '@/components/sections/SectionSideProjects.vue'
    import InstagramFeed from '@/components/sections/SectionInstagramFeed.vue'

    // Components export
    export default defineComponent({
        components: { Header, Footer, Marquee, Background, CTAs, Button, Hero, LatestContent, ServicesList, SideProjects, InstagramFeed },
    })

</script>

<template>
    <div>
        <!-- Essentials -->
        <Marquee/>
        <Background />
        <Header />
        <CTAs />
        <!-- Content -->
        <Hero />
        <LatestContent />
        <ServicesList />
        <SideProjects />
        <InstagramFeed />
        <!-- Footer -->
        <Footer />
    </div>
</template>