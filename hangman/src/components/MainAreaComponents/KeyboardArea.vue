<template>
  <section id="keyboardArea">
    <button
      id="keyboardBtns"
      v-for="char in alphabet"
      @click="pickingLetter(char)"
      :disabled="toBeDisabled[char]"
      :key="char"
    >
      {{ char }}
    </button>
  </section>
</template>
