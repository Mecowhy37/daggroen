<template>
  <div class="full">
    <h1>Welcome to Dag Groen! <span>˶ᵔ ᵕ ᵔ˶</span></h1>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&display=swap");

html,
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Bree Serif", serif;
  font-weight: 400;
  font-style: normal;
}

.full {
  display: grid;
  width: 100dvw;
  height: 100dvh;
  background-color: #eedfbb;
}
.full > * {
  place-self: center;
  color: hsl(44, 60%, 98%);
  text-align: center;
  margin-bottom: 2rem;
}
.full span {
  white-space: nowrap;
}
</style>
