<script setup></script>
<template>
  <body>
    <div class="preloader">
      <div class="loading">
        <h2>Loading...</h2>
        <span class="progress"></span>
      </div>
    </div>

    <div class="wrapper">
      <ul
        class="scene unselectable"
        data-friction-x="0.1"
        data-friction-y="0.1"
        data-scalar-x="25"
        data-scalar-y="15"
        id="scene"
      >
        <li class="layer" data-depth="0.00"></li>
        <!-- BG -->

        <li class="layer" data-depth="0.10">
          <div class="background"></div>
        </li>

        <!-- Hero -->

        <li class="layer" data-depth="0.20">
          <div class="title">
            <h2>IMMINENT</h2>
            <span class="line"></span>
          </div>
        </li>

        <li class="layer" data-depth="0.25">
          <div class="sphere">
            <img alt="sphere" src="../assets/images/sphere.png" />
          </div>
        </li>

        <li class="layer" data-depth="0.30">
          <div class="hero">
            <h1 id="countdown">The most spectacular coming soon template!</h1>

            <p class="sub-title">The most spectacular coming soon template!</p>
          </div>
        </li>
        <!-- Flakes -->

        <li class="layer" data-depth="0.40">
          <div class="depth-1 flake1">
            <img alt="flake" src="../assets/images/flakes/depth1/flakes1.png" />
          </div>

          <div class="depth-1 flake2">
            <img alt="flake" src="../assets/images/flakes/depth1/flakes2.png" />
          </div>

          <div class="depth-1 flake3">
            <img alt="flake" src="../assets/images/flakes/depth1/flakes3.png" />
          </div>

          <div class="depth-1 flake4">
            <img alt="flake" src="../assets/images/flakes/depth1/flakes4.png" />
          </div>
        </li>

        <li class="layer" data-depth="0.50">
          <div class="depth-2 flake1">
            <img alt="flake" src="../assets/images/flakes/depth2/flakes1.png" />
          </div>

          <div class="depth-2 flake2">
            <img alt="flake" src="../assets/images/flakes/depth2/flakes2.png" />
          </div>
        </li>

        <li class="layer" data-depth="0.60">
          <div class="depth-3 flake1">
            <img alt="flake" src="../assets/images/flakes/depth3/flakes1.png" />
          </div>

          <div class="depth-3 flake2">
            <img alt="flake" src="../assets/images/flakes/depth3/flakes2.png" />
          </div>

          <div class="depth-3 flake3">
            <img alt="flake" src="../assets/images/flakes/depth3/flakes3.png" />
          </div>

          <div class="depth-3 flake4">
            <img alt="flake" src="../assets/images/flakes/depth3/flakes4.png" />
          </div>
        </li>

        <li class="layer" data-depth="0.80">
          <div class="depth-4">
            <img alt="flake" src="../assets/images/flakes/depth4/flakes.png" />
          </div>
        </li>

        <li class="layer" data-depth="1.00">
          <div class="depth-5">
            <img alt="flake" src="../assets/images/flakes/depth5/flakes.png" />
          </div>
        </li>
        <!-- Contact -->

        <li class="layer" data-depth="0.20">
          <div class="contact">
            <ul class="icons">
              <li>
                <a class="behance" href="#"><i class="fa fa-behance"></i></a>
              </li>

              <li>
                <a class="twitter" href="#"><i class="fa fa-twitter"></i></a>
              </li>

              <li>
                <a class="dribbble" href="#"><i class="fa fa-dribbble"></i></a>
              </li>
            </ul>
            Theme by <a href="https://themewagon.com/" target="_blank">ThemeWagon</a>
            <a class="mail" href="mailto:info@example.com?subject=Hi%20ThemeWagon!"
              >info@example.com</a
            >
          </div>
        </li>
      </ul>
    </div>
  </body>
</template>
<style scoped></style>
