<script setup></script>

<template>
   <h1>問卷管理</h1>
   <div class="search-area">
      <div class="title d-flex">
         <p>問卷標題</p>
         <input type="text" />
      </div>
      <div class="date d-flex">
         <p>開始/結束</p>
         <input type="date" />
         <input type="date" />
      </div>
   </div>
</template>

<style lang="scss" scoped>
.search-area {
   display: flex;
   flex-direction: column;
   margin: 4rem;
   border: 1px solid;
}
</style>
