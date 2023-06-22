<template>
  <div id="navbar">
    <nav class="navbar navbar-expand-lg navbar-fixed-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Karos</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Experiences</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Links
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="http://discord.karos.me/">Discord</a></li>
                <li><a class="dropdown-item" href="http://fb.karos.me/">Facebook</a></li>
                <li><a class="dropdown-item" href="http://github.karos.me/">GitHub</a></li>
                <li><a class="dropdown-item" href="http://ig.karos.me/">Instagram</a></li>
                <li><a class="dropdown-item" href="http://yt.karos.me/">YouTube</a></li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
  <div>
    <h1 class="mx-auto">{{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      msg: 'Karos',
      name: 'Joy'
    }
  }
}
</script>