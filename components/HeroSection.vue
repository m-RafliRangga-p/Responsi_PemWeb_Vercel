<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">
  <section class="hero bg">
   <div class="container">
      <div class="row justify-content-around">
        <div class="col-lg-7 order-2 order-lg-1">
          <h3 class="mt-4 mt-lg-0">Hi, it's me Mr.Rp</h3>
          <h1 class="main-text">Muhammad Rafli Rangga Pratama</h1>
            <p class="mt-3 mb-4">
              A student from <span class="main-text">Amikom University Yogyakarta</span> who is very interested in learning web programming. Skilled in using HTML, CSS, Bootstrap, and several front-end frameworks. If interested, please download my CV below.
            </p>
            <div>
              <div class="d-flex align-items-center">
                <div class="social-icons">
                  <a target="_blank" href="mailto:raflirangga35@gmail.com"><i class="ri-mail-open-fill"></i></a>
                </div>
                <div class="mt-3">
                  <p>raflirangga35@gmail.com</p>
                </div>
              </div>
              <div class="d-flex align-items-center">
                <div class="social-icons">
                  <a target="_blank" href="https://www.instagram.com/rafli_rangga_35?igsh=NnAwb2wxcGlhODBk"><i class="ri-instagram-fill"></i></a>
                </div>
                <div class="mt-3">
                  <p>@rafli_rangga_35</p>
                </div>
              </div>
              <div class="d-flex align-items-center">
                <div class="social-icons">
                  <a target="_blank" href="https://github.com/m-RafliRangga-p"><i class="ri-github-fill"></i></a>
                </div>
                <div class="mt-3">
                  <p>m-RafliRangga-p</p>
                </div>
              </div>
              <div class="d-flex align-items-center">
                <div class="social-icons">
                  <a target="_blank" href="https://www.linkedin.com/in/rafli-rangga-65ba872b6/"><i class="ri-linkedin-box-fill"></i></a>
                </div>
                <div class="mt-3">
                  <p>Rafli Rangga</p>
                </div>
              </div>
            </div>
            <a target="_blank" href="https://drive.google.com/file/d/1v6xBRVlKpw_EFTOXQd3jgPwmCUQn57O0/view?usp=sharing" class="btn btn-brand mt-3 mb-3 theme-shadow">Download CV</a>
        </div>
        <div class="col-lg-5 order-1 order-lg-2">
          <img src="../assets/raf-Photoroom-modified.png" alt="Admin" class="img-size filter-img">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>
<style scoped>
*{
  font-family: "JetBrains Mono", monospace;
}
.hero {
  padding: 100px 0 40px;
}
</style>
