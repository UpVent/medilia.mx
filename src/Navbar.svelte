<script>
    // Sveltestrap imports
    import { Button } from 'sveltestrap';

    // Navbar icons
    import House from 'svelte-bootstrap-icons/lib/House';
    import JournalCheck from 'svelte-bootstrap-icons/lib/JournalCheck';
    import People from 'svelte-bootstrap-icons/lib/People';
    import Phone from 'svelte-bootstrap-icons/lib/Phone';
    import Rulers from 'svelte-bootstrap-icons/lib/Rulers';
    import Thermometer from 'svelte-bootstrap-icons/lib/Thermometer';

    // Navbar logo
    const logo = 'images/medilia-logo.png';
</script>

<header class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-0">
    <a href="/" class="d-flex align-items-center col-md-3 mb-2 mb-md-0 text-dark text-decoration-none navbar-brand">
    <img class="mx-auto"  width="150" height="60" src="{logo}" alt="UpVent Logo">
    </a>

    <ul class="nav nav-pills col-12 mx-auto col-md-auto mb-2 justify-content-center mb-md-0">
        <li><a class="nav-link px-2 text-muted" href="/">Inicio <House/></a></li>
        <li><a class="nav-link px-2 text-muted" href="/">Nosotros <People/></a></li>
        <li><a class="nav-link px-2 text-muted" href="/">Servicios <JournalCheck/></a></li>
        <li><a class="nav-link px-2 text-muted" href="/">Magnitudes <Thermometer/></a></li>
        <li><a class="nav-link px-2 text-muted" href="/">Calibración <Rulers/></a></li>
    </ul>

    <div class="text-end me-auto ms-auto mx-auto">
        <Button size="lg" color="primary">Contacto <Phone/></Button>
    </div>
</header>
