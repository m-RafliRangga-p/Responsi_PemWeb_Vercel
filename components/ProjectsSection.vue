<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">
  <section id="projects" class="projects section-padding bg">
    <div class="container">
      <div class="row mb-3">
        <div class="col-12 text-center">
          <div class="section-title">
            <h1 class="main-text">My Porjects</h1>
            <p>
              An ordinary person who loves to code
            </p>
          </div>
        </div>
      </div>
      <div class="row justify-content-between">
        <div class="card ms-lg-3 mt-3" style="width: 23rem">
          <div class="image-zoom">
            <div class="image-zoom-wrapper">
              <img src="../assets/elixir.png" class="img-size filter-img" alt="elixir" />
            </div>
          </div>
          <div class="card-body bg-dark">
            <h5 class="card-title main-text text-center">Elixir Company Profile Project</h5>
            <p class="card-text text-white">
              An individual project to create a company profile using HTML, CSS, JS, Bootstrap, and Vue.js
            </p>
            <a target="_blank" href="https://github.com/m-RafliRangga-p/Company_Profile_Elixir" class="btn btn-brand theme-shadow">Github</a>
          </div>
        </div>
        <div class="card ms-lg-3 mt-3" style="width: 23rem">
          <div class="image-zoom">
            <div class="image-zoom-wrapper">
              <img src="../assets/bumdes.png" class="img-size filter-img" alt="elixir" />
            </div>
          </div>
          <div class="card-body bg-dark">
            <h5 class="card-title main-text text-center">Promotional Web BUMDES</h5>
            <p class="card-text text-white">
              A final project for Pemrograman Web course with front-end and back-end
            </p>
            <a target="_blank" href="https://github.com/zendevs404/FP-Web-Promotional" class="btn btn-brand theme-shadow">Github</a>
          </div>
        </div>
        <div class="card ms-lg-3 mt-3" style="width: 23rem">
          <div class="image-zoom">
            <div class="image-zoom-wrapper">
              <img src="../assets/AI.png" class="img-size filter-img" alt="elixir" />
            </div>
          </div>
          <div class="card-body bg-dark">
            <h5 class="card-title main-text text-center">Flappy Bird AI</h5>
            <p class="card-text text-white">
              A task to make an AI using neat python
            </p>
            <a target="_blank" href="https://github.com/m-RafliRangga-p/Tugas_AI" class="btn btn-brand theme-shadow">Github</a>
          </div>
        </div>
        <div class="card ms-lg-3 mt-3" style="width: 23rem">
          <div class="image-zoom">
            <div class="image-zoom-wrapper">
              <img src="../assets/yudha.png" class="img-size filter-img" alt="elixir" />
            </div>
          </div>
          <div class="card-body bg-dark">
            <h5 class="card-title main-text text-center">Inventory System Using C#</h5>
            <p class="card-text text-white">
              A final project for Pemrograman Lanjut course where this project is created using the C# language
            </p>
            <a target="_blank" href="https://github.com/m-RafliRangga-p/FP_PemrogramanLanjut" class="btn btn-brand theme-shadow">Github</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
*{
  font-family: "JetBrains Mono", monospace;
}

.card{
  border: 1px solid var(--main-color);
}

.filter-img{
  filter: drop-shadow(0px 20px 25px rgba(0, 238, 255, 0.5));
}
</style>
