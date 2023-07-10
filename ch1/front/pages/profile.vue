<template>
  <div>
    <div>{{ name }}</div>
  </div>
</template>

<script>
export default {
  layout: 'admin',

  data() {
    return {
      name: 'PROFILE',
    };
  },
  // 개별 페이지에 head tag가 따로 정의되어 있으면 개별 페이지의 것을 우선한다.
  head() {
    return {
      title: '프로필',
    };
  },
};
</script>

<style></style>
