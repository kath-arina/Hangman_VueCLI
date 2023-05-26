<template>
  <main>
    <MainHeader />
    <OutputField />
    <KeyboardArea />
  </main>
</template>

<script>
import KeyboardArea from "@/components/MainAreaComponents/KeyboardArea.vue";
import MainHeader from "@/components/MainAreaComponents/MainHeader.vue";
import OutputField from "@/components/MainAreaComponents/OutputField.vue";

export default {
  compoents: {
    KeyboardArea,
    MainHeader,
    OutputField,
  },
};
</script>

<style scoped>
main {
  border: 5px solid black;
}
</style>
