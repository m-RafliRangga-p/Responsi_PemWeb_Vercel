<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&display=swap" rel="stylesheet">
  <section id="contact" class="contact section-padding bg">
    <div class="container">
      <div class="row mb-3">
        <div class="col-12 text-center">
          <div class="section-title">
            <h1 class="main-text">Contact</h1>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <form action="#" class="row g-3 p-lg-5 p-4 theme-shadow frm">
            <div class="form-group col-lg-6">
              <input type="text" class="form-control" placeholder="Enter First Name" />
            </div>
            <div class="form-group col-lg-6">
              <input type="text" class="form-control" placeholder="Enter Last Name" />
            </div>
            <div class="form-group col-lg-12">
              <input type="email" class="form-control" placeholder="Enter Email Address" />
            </div>
            <div class="form-group col-lg-12">
              <input type="text" class="form-control" placeholder="Enter Subject" />
            </div>
            <div class="form-group col-lg-12">
              <textarea
                name="message"
                rows="5"
                class="form-control"
                placeholder="Enter Message"
              ></textarea>
            </div>
            <div class="form-group col-lg-12 d-grid">
              <button class="btn btn-brand">Send Message</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
*{
  font-family: "JetBrains Mono", monospace;
}
.contact {
  background-color: var(--second-bg-color)
}
.frm{
  background-color: var(--bg-color);
}
.form-control{
  background-color: #d9d9d9;
  color: var(--bg-color) !important;
}
</style>
