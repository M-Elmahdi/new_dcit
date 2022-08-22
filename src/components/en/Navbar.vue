<template>
    <nav
    class="navbar navbar-expand-lg bg-white navbar-light sticky-top px-4 px-lg-5">
    <img
        width="100"
        height="100"
        class="img-fluid me-3"
        src="@/assets/identity/ex.png"
    />
    <a href="" class="navbar-brand d-flex align-items-center">
        <h4 class="m-0">
            {{ lang.company_name }}
        </h4>
    </a>
    <button
        type="button"
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarCollapse"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarCollapse">
        <div class="navbar-nav ms-auto bg-light shadow-sm rounded pe-4 py-3 py-lg-0">
         
            <a href="#about" class="nav-item nav-link">About</a>
            <a href="#vision" class="nav-item nav-link">Vision</a>
            <a href="#values" class="nav-item nav-link">Values</a>
            <a href="#services" class="nav-item nav-link">Services</a>
            <a href="#social" class="nav-item nav-link">News</a>
            <a href="#contactus" class="nav-item nav-link">Contact Us</a>
            
        </div>
    </div>
    </nav>
</template>

<script>
export default {
    name: 'EnNavbar',
    props: {
        lang: Object,
    }
}
</script>