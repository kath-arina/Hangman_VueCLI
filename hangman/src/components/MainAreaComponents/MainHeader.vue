<template>
  <section id="top">
    <div id="status">{{ setStatus }}STATUS</div>
    <div id="fails">Fails {{ fails }}/10</div>
    <button id="newGameBtn" @click="startNewGame">New Game</button>
  </section>
</template>
