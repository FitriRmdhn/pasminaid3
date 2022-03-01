<template>
  <main>
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
  <a class="navbar-brand" href="#">Pasminaid</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li>
        <NuxtLink to="/" class="text-white col-md-4">
          <i class='bx bx-grid-alt'></i>
          <span class="links_name">Home</span>
        </NuxtLink>
         <span class="tooltip">Home</span>
      </li>
      <li>
       <NuxtLink to="/product" class="text-white col-md-4">
         <i class='bx bx-cart-alt' ></i>
         <span class="links_name">Product</span>
       </NuxtLink>
       <span class="tooltip">Product</span>
     </li>
     <li>
       <NuxtLink to="/contact" class="text-white col-md-4">
         <i class='bx bx-chat' ></i>
         <span class="links_name">Contact</span>
       </NuxtLink>
       <span class="tooltip">Contact</span>
     </li>
    </ul>
  </div>
</nav>
  </main>
</template>