<script setup>
  import Ara from './components/Ara.vue';
  import Assessment from './components/Assessment.vue';
  import Footer from './components/Footer.vue';
  import Habits from './components/Habits.vue';
  import Header from './components/Header.vue';
  import Headline from './components/Headline.vue';
  import Juara from './components/Juara.vue';
  import Partner from './components/Partner.vue';
  import Questions from './components/FAQ.vue';
  import RPP from './components/RPP.vue';
  import Teacher from './components/Teacher.vue';
  import Testimonial from './components/Testimonial.vue';
  import WinWin from './components/WinWin.vue';
</script>

<template>
  <Header />
  <main>
    <Headline />
    <Partner />
    <Juara />
    <Ara />
    <Habits />
    <WinWin />
    <Testimonial />
    <RPP />
    <Teacher />
    <Assessment />
    <Questions />
  </main>
  <Footer />
</template>

