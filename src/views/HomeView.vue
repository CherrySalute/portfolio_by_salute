<script setup>
import HeaderSection from "@/components/HeaderSection.vue";
import FooterSection from "@/components/FooterSection.vue";
import IntroSection from "@/components/IntroSection.vue";
import CarrerSection from "@/components/CarrerSection.vue";
import PortfolioSection from "@/components/PortfolioSection.vue";
import ContactSection from "@/components/ContactSection.vue";
</script>

<template>
    <HeaderSection />
    <main id="main" role="main">
        <IntroSection />
        <CarrerSection />
        <PortfolioSection />
        <ContactSection />
    </main>
    <FooterSection />
</template>