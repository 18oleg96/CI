<template>
  <div class="contacts" >
    <Navbar color="secondary"/>
    <Contacts />
  </div>
</template>

<script>
import Navbar from "~/components/uikit/Navbar";
import Contacts from "~/components/contactsPage/Contacts";

export default {
  name: "contacts",
  components: {
    Navbar,
    Contacts
  },
}
</script>

<style lang="scss">
  .contacts {
    background-color: #181818;
    height: 100vh;
  }
</style>
