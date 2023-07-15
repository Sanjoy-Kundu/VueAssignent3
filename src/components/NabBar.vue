<script setup>
	import {colors} from '../data/nav_prom'

</script>
<template>
		<header>
<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#"><b>Launch</b><span style="color:rgb(86, 86, 240)">.</span></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
      
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Testimonial</a></li>
            <li><a class="dropdown-item" href="#">Menu 2</a></li>
            <li><a class="dropdown-item" href="#">Menu 3</a></li>
          </ul>
        </li>
		<li class="nav-item">
			<a class="nav-link active" aria-current="page" href="#">Features</a>
		  </li>
		<li class="nav-item">
			<a class="nav-link active" aria-current="page" href="#">Pricing</a>
		  </li>
		<li class="nav-item">
			<a class="nav-link active" aria-current="page" href="#">About</a>
		  </li>
      </ul>


	  <ul class="navbar-nav  d-flex">
        <li class="nav-item">
          <a :class="[colors.navSignBorder, colors.underlineNone, colors.roundedPillBorder]" aria-current="page" href="#">Sign In</a>
        </li>
        <li class="nav-item">
          <a :class="[colors.primaryButton, colors.roundedPillBorder, colors.buttonGap]" aria-current="page" href="#">Register</a>
        </li>
		</ul>

      <!-- <form class="d-flex" role="search">
        
      </form> -->
    </div>
  </div>
</nav>
	</header>
</template>
<style scoped></style>