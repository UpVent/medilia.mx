<script>
    // Get Current Year
    let year = new Date().getFullYear();

    // Medilia logo
    const logo = 'images/medilia-logo.png';

    // Footer Icons
    import Twitter from 'svelte-bootstrap-icons/lib/Twitter';
    import Instagram from 'svelte-bootstrap-icons/lib/Instagram';
    import Facebook from 'svelte-bootstrap-icons/lib/Facebook';
    import HeartFill from 'svelte-bootstrap-icons/lib/HeartFill';
</script>

<div class="container">
  <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
    <div class="col-md-4 d-flex align-items-center">
      <a href="/" class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
        <img class="img-thumbnail" src={logo} alt="Logo de Medilia"/>
      </a>
      <span class="text-muted">© {year} Medilia.</span>
    </div>

    <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
        <li class="ms-3"><a class="text-muted" href="#"><Twitter/></a></li>
        <li class="ms-3"><a class="text-muted" href="#"><Instagram/></a></li>
        <li class="ms-3"><a class="text-muted" href="#"><Facebook/></a></li>
    </ul>

    <div class="container text-center text-muted">
        <p>Hecho con <HeartFill class="text-danger"/> por <a class="text-decoration-none" href="https://upvent.codes" target="_blank">UpVent Technologies</a></p>
    </div>

  </footer>
</div>
