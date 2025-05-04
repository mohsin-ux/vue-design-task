<script setup>
import Archive from "./components/Archive.vue";
import Header from "./components/Header.vue";
import LovedByDesigners from "./components/LovedByDesigners.vue";
import Main from "./components/Main.vue";
import ShareAnything from "./components/ShareAnything.vue";
import Testimonial from "./components/Testimonial.vue";
import KeepInLoop from "./components/KeepInLoop.vue";
import TeamsVisibility from "./components/TeamsVisibility.vue";
import Footer from "./components/Footer.vue";
import MainPortion from "./components/BetterFeedback/MainPortion.vue";
</script>

<template>
  <Header></Header>

  <Main></Main>

  <ShareAnything></ShareAnything>
  <MainPortion></MainPortion>

  <Archive></Archive>

  <Testimonial></Testimonial>

  <LovedByDesigners></LovedByDesigners>

  <KeepInLoop></KeepInLoop>

  <TeamsVisibility></TeamsVisibility>

  <Footer></Footer>
</template>

<style scoped></style>
