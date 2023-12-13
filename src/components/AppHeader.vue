<script>
export default {
    name: "AppHeader",
    data() {
        return {}
    },
    mounted() {},
    methods: {}
}
</script>

<template>
  <nav class="navbar navbar-expand-md navbar-light" style="background-color: #3498db; height: 160px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
    <div class="container d-flex align-items-center justify-content-between w-100">
      <a class="navbar-brand mb-2" href="#">
        <img src="" alt="" style="max-height: 50px;">
        <span style="color: #ffffff; font-weight: bold;">BDoctors</span>
      </a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <a class="navbar-brand mb-2" href="#">
          <img src="" alt="" style="max-height: 50px;">
          <span style="color: #ffffff; font-weight: bold;">Accedi</span>
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <a class="navbar-brand mb-2" href="#">
          <img src="" alt="" style="max-height: 50px;">
          <span style="color: #ffffff; font-weight: bold;">Chi Siamo</span>
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
.navbar {
  height: 80px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.navbar-brand {
  display: flex;
  flex-direction: column;
  align-items: center;
  color: #ffffff;
}

.btn-accesso,
.btn-altro {
  border-radius: 5px;
  background-color: #3498db;
  color: #ffffff;
  padding: 8px 16px;
  height: 40px;
  line-height: 40px;

  &:hover {
    background-color: #3498db;
  }
}
</style>










