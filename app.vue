<template>
  <div>
    <Navbar />
    <Hero />
    <Partners />
    <Numbers />
    <Directions />
    <AboutCompany />
    <Technologies />
    <Rest />
    <Cases />
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/uikit/Navbar";
import Hero from "~/components/indexPage/Hero";
import Partners from "~/components/indexPage/Partners";
import Numbers from "~/components/indexPage/Numbers";
import Directions from "~/components/indexPage/Directions";
import Technologies from "~/components/indexPage/Technologies";
import AboutCompany from "~/components/indexPage/AboutCompany";
import Rest from "~/components/indexPage/Rest";
import Cases from "~/components/indexPage/Cases";
import Footer from "~/components/uikit/Footer";

export default {
  name: "Index",
  components: {
    Navbar,
    Hero,
    Partners,
    Numbers,
    Directions,
    Technologies,
    AboutCompany,
    Rest,
    Cases,
    Footer
  },
}
</script>

<style lang="scss">
  .qwerty {
    max-width: 1920px;
  }
</style>
