<script setup>
  import Spotify from "./components/Spotify.vue"
                        
</script>

<template>
  <Spotify></Spotify>
</template>

<style>
@font-face {
  font-family: Gotham-Black;
  src: url("./assets/Gotham-Black.otf");
}  
<!--  -->
@font-face {
  font-family: Gotham-Bold; 
  src: url("./assets/Gotham-Bold.otf");
}
@font-face {
  font-family: Gotham-Light; 
  src: url("./assets/GothamLight.ttf");
}

@font-face {
  font-family: Proxima; 
  src: url("./assets/proxima_nova.otf");
}

* {
  font-family: Gotham-Bold;
}

.gradient {
  background: rgb(39,32,113);
background: linear-gradient(135deg, rgba(39,32,113,1) 0%, rgba(39,32,113,1) 6%, rgba(167,165,198,1) 100%, rgba(255,255,255,1) 100%);
}
.borderbottom {
  border-bottom: 0.02vh solid rgb(55, 55, 55);
}
.mont {
  font-family: Gotham-Light  !important;
  font-weight: 500;
}
.bordertest {
  border: 1px solid red;
}
.background-fill {
  background: rgba(0, 0, 0, 0.905);
}
.background {
  background: rgba(0, 0, 0, 0.405);

}
.playlist {
  font-family: Gotham-Bold; 
  font-weight: 400;
}
.musicname {
  font-family: Proxima;
  color: white;
}

.albume {
  font-family: Proxima;
  color: rgb(157, 156, 156);
  font-size: 1.6vh;
}
.songer {
  font-family: Proxima;
  color: rgb(157, 156, 156);
  font-size: 1.3vh;

}
.username {
  font-weight: 600;
  color: white;
}

.white {
  color: white;
}
.itemlist{
  font-family: Gotham-Light  !important;
  font-weight: 500;
  font-size: 1.5vh;
}

.background-bottom {
  background: rgb(21, 21, 21);
}
</style>

