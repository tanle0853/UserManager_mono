<template>
  <div>
    <h2>Login</h2>
    <form @submit.prevent="login">
      <div>
        <label for="username">Username:</label>
        <input type="text" v-model="username" id="username" required />
      </div>
      <div>
        <label for="password">Password:</label>
        <input type="password" v-model="password" id="password" required />
      </div>
      <button type="submit">Login</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      username: "",
      password: "",
    };
  },
  methods: {
    login() {
      // Thực hiện xử lý đăng nhập tại đây, ví dụ:
      console.log("Username:", this.username);
      console.log("Password:", this.password);
    },
  },
};
</script>

<style>
/* Thêm CSS cho component đăng nhập (tuỳ chọn) */
</style>
