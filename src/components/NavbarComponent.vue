<template>
  <div class="sidemenu d-flex justify-content-center">
    <ul class="navcollection nav flex-column align-self-center">
      <li class="logobutton nav-item align-self-center">
        <a class="logo navbar-brand" href="/">
          <img
            src="../assets/logo.png"
            alt=""
            width="30"
            height="24"
            class="d-inline-block align-text-top"
          />
        </a>
      </li>
      <li class="navbutton nav-item align-self-center">
        <router-link class="navtext nav-link text-center" to="/"
          >Home</router-link
        >
      </li>
      <li class="navbutton nav-item align-self-center">
        <router-link class="navtext nav-link text-center" to="/about"
          >Resume</router-link
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent",
};
</script>

<style scoped>
.navcollection {
  width: 100%;
}

.logobutton:hover {
  transform: scale(1.5);
}

.logo {
  margin: 0px;
  padding: 0px;
}

.sidemenu {
  background-color: #141414 !important;
  padding: 0px;
  min-height: 100vh;
}

.navbutton:hover {
  background-color: #ba4bbc94 !important;
  width: 100%;
}
.navbutton {
  width: 100%;
}

.navtext {
  color: rgb(255, 255, 255) !important;
  font-weight: bold !important;
}

.navtext:hover {
  transform: scale(1.1);
}
</style>
