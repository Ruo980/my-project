<template>
  <div class="app">
    <div class="avatar">
      <img src="your-avatar-url" alt="Avatar" />
    </div>
    <h1 class="nickname">{{ nickname }}</h1>
    <p class="student-id">{{ studentId }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nickname: "Your Nickname",
      studentId: "Your Student ID",
    };
  },
};
</script>

<style>
.app {
  text-align: center;
  padding: 20px;
}

.avatar {
  margin-bottom: 20px;
}

.nickname {
  font-size: 24px;
  margin-bottom: 10px;
}

.student-id {
  font-size: 18px;
  color: gray;
}
</style>
