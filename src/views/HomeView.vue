<script setup></script>

<template>
  <div class="container">
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
    <div class="questionnaire-area">
      <button>刪除</button>
      <button>新增</button>
      <div class="survey-table"></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  margin: 4rem;
}
.search-area {
  display: flex;
  flex-direction: column;

  border: 1px solid;
}
</style>
