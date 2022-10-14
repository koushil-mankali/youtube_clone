<script setup lang="ts"></script>

<template>
  <div class="searchbarBox">
    <div class="searchBarDiv">
      <div class="inptIcon">icon</div>
      <input type="search" placeholder="Search" class="search" />
      <button type="button" class="searchBtn">btn icon</button>
    </div>
    <div class="micDiv">mic icon</div>
  </div>
</template>

<style scoped>
.searchbarBox {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  /* background-color: aqua; */
}

.searchBarDiv {
  margin-right: 0.5rem;
  display: flex;
}

.inptIcon {
  display: none;
}

.search {
  padding: 10px;
  font-size: 1.1rem;
  color: var(--txt-color);
  background-color: var(--black-background-color);
  border-radius: 2px 0 0 2px;
  border: 1px solid var(--black-border-color);
  outline: none;
}

.search:focus {
  outline-offset: -1px;
  outline: 1px solid var(--blue-border-color);
}

.searchBtn {
  padding: 0.5rem;
  outline: none;
  border-radius: 0 2px 2px 0;
  border: 1px solid var(--black-border-color);
  background-color: var(--srch-btn-background-color);
  cursor: pointer;
}
</style>
