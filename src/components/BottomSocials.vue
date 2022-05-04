!
<template>
  <div
    id="socials"
    class="container d-flex justify-content-around align-items-center"
  >
    <div class="btn-signup"><span>Sign-Up NOW!</span></div>
    <div class="links">
      <ul>
        <li>
          <a href=""><span class="bottom-text">Follow us</span></a>
        </li>
        <li>
          <div class="social-wrap">
            <a href=""> <i class="fa-brands fa-facebook-f"></i></a>
          </div>
        </li>
        <li>
          <div class="social-wrap">
            <a href=""><i class="fa-brands fa-twitter"></i></a>
          </div>
        </li>
        <li>
          <div class="social-wrap">
            <a href=""><i class="fa-brands fa-youtube"></i></a>
          </div>
        </li>
        <li>
          <div class="social-wrap">
            <a href=""><i class="fa-brands fa-pinterest-p"></i></a>
          </div>
        </li>
        <li>
          <div class="social-wrap">
            <a href=""><i class="fa-solid fa-location-dot"></i></a>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default { name: "Socials" };
</script>

<style scoped lang="scss">
@import "@/assets/bottomSocials.scss";
// @import "@/assets/generals.scss";
</style>
