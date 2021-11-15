<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link" href="#">
            Creative Tim
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            Blog
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            Licenses
          </a>
        </li>
      </ul>
      <div class="copyright">
        © {{year}} made with <i class="tim-icons icon-heart-2"></i> by
        <a href="#" target="_blank" rel="noopener">Pedro </a>&nbsp;&
        <a href="#" target="_blank" rel="noopener">Nkiambi</a> Teste.
      </div>
    </div>
  </footer>
</template>
<script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      }
    }
  };
</script>
<style>
</style>
