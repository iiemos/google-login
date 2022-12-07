<script setup>
</script>

<template>
  <div>
    <div id="g_id_onload"
      data-client_id="310381460275-g8011qapq5li02afmt7hubiu0k1ce6tt.apps.googleusercontent.com"
      data-login_uri="http://localhost:5173/"
      data-itp_support="true"
      data-allowed_parent_origin="http://localhost:5173/">
    </div>
    <header>
      <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
      <div class="wrapper">
      </div>
    </header>
    <main>
    </main>
  </div>

</template>
<script>
  // import { GoogleAuthProvider, getAuth } from "firebase/auth";
  // const provider = new GoogleAuthProvider();
  // provider.addScope('https://www.googleapis.com/auth/contacts.readonly');
</script>
<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
