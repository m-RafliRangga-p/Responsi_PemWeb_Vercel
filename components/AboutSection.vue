<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">
  <section id="about" class="about section-padding bg">
    <div class="container">
      <div class="row mb-3">
        <div class="col-12 text-center">
          <div class="section-title">
            <h1 class="main-text">About Me</h1>
            <p>
              An ordinary person who loves to code
            </p>
          </div>
        </div>
      </div>
      <div class="row justify-content-between align-items-center">
        <div class="col-lg-6">
          <img src="../assets/about-middle.png" class="img-size filter-img" alt="about" />
        </div>
        <div class="col-lg-5">
          <p class="mt-3 mb-4">
            Just an ordinary person who is very interested in the world of programming, especially web programming. Skilled in HTML, CSS, Bootstrap, a bit of JS, and some frontend frameworks. Currently, I am still striving to learn frontend programming more deeply.
          </p>
          <div class="d-flex pt-4 mb-3">
            <div class="iconbox me-4">
              <i class="ri-html5-fill"></i>
            </div>
            <div>
              <h5>HTML 5</h5>
            </div>
          </div>
          <div class="d-flex mb-3">
            <div class="iconbox me-4">
              <i class="ri-css3-fill"></i>
            </div>
            <div>
              <h5>CSS 3</h5>
            </div>
          </div>
          <div class="d-flex">
            <div class="iconbox me-4">
              <i class="ri-bootstrap-fill"></i>
            </div>
            <div>
              <h5>Bootstrap</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
*{
  font-family: "JetBrains Mono", monospace;
}
.about{
  background-color: var(--second-bg-color)
}
.img-size{
  border-radius: 30px;
}
h5{
  margin-left: 15px;
  margin-top: 25px;
}
</style>
