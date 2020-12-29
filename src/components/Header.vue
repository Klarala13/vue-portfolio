<template>
  <b-navbar
    toggleable="lg"
    type="dark"
    class="nav bg-dark fixed-top"
    id="my-nav"
  >
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#projects" class="nav-link p-3">Projects</b-nav-item>
        <b-nav-item href="#skills" class="nav-link p-3">Skills</b-nav-item>
        <b-nav-item href="#stack" class="nav-link p-3">Stack</b-nav-item>
        <b-nav-item href="#contact" class="nav-link p-3">Contact</b-nav-item>
        <b-nav-item-dropdown text="CV" class="mt-0.7 p-3">
          <b-dropdown-item href="cv/ITCV.pdf" target="blank"
            >EN</b-dropdown-item
          >
          <b-dropdown-item href="cv/IT-CVesp.pdf" target="blank"
            >ES</b-dropdown-item
          >
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {};
</script>
