<template>
  <div>
    <nav class="menu">
      <p class="menu-label">Menu</p>
      <ul class="menu-list">
        <router-link to="/products">Products</router-link>
        <router-link to="/about">About</router-link>
      </ul>
    </nav>
    <div>Hi, new testing</div>
  </div>
</template>
<script>
/* export default {
  name: 'NavBar',
  data() {
    return {
      userInfo: {
        type: Object,
        default() {},
      },
      providers: ['twitter', 'github', 'aad'],
      redirect: window.location.pathname,
    };
  },
  methods: {
  async getUserInfo() {
    try {
      const response = await fetch('/.auth/me');
      const payload = await response.json();
      const { clientPrincipal } = payload;
      return clientPrincipal;
    } catch (error) {
      console.error('No profile could be found');
      return undefined;
    }
  },
},
async created() {
  this.userInfo = await this.getUserInfo();
},
}; */
</script>
