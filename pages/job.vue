<template>
  <div class="jobPage">
    <Navbar />
    <Container>
      <AccordionBlock 
        :list1="['JavaScript' , 'ES6' , 'React' , 'MobX' , 'Node.js' , 'Next.js' , 'Scss' , 'Git']"
        :list2="['JavaScript' , 'MobX']"
        :list3="['Git' , 'JavaScript']"
      />
      <Button color="secondary">
        Хочу в команду
      </Button>
    </Container>
  </div>
</template>

<script>
import Container from "~/components/uikit/Container";
import Navbar from "~/components/uikit/Navbar";
import AccordionBlock from "~/components/jobPage/AccordionBlock";
import Button from "~/components/uikit/Button";

export default {
  name: "job",
  components: {
    Container,
    Navbar,
    AccordionBlock,
    Button
  },
}
</script>

<style lang="scss">
  .jobPage {
    background-color: #181818;
  }
</style>
