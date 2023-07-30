<template>
  <div>
    <h1>Welcome to My App</h1>
    <LoginComponent /> <!-- Đảm bảo rằng bạn đã thêm component này vào đây -->
  </div>
</template>

<script>
import LoginComponent from "./components/LoginComponent.vue";

export default {
  components: {
    LoginComponent,
  },
};
</script>
