<template>
  <header class="w-full navbar bg-base-300 sticky top-0 z-50">
    <div class="flex-1 px-2 mx-2">
      <img
        src="https://cajalahuerta.com/wp-content/uploads/2020/01/NUEVO-LOGO-CAJAblanco-300x98.png"
        alt="Logo Caja Inmaculada"
        class="h-10 logo-inverted"
      />
    </div>
    <div class="flex-none lg:hidden">
      <label
        for="my-drawer-3"
        aria-label="open sidebar"
        class="btn btn-square btn-ghost"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="inline-block w-6 h-6 stroke-current"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          ></path>
        </svg>
      </label>
    </div>
    <nav class="flex-none hidden lg:block">
      <ul class="menu menu-horizontal items-center">
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#quienes-somos">Quiénes Somos</a></li>
        <li><a href="#servicios">Servicios</a></li>
        <li><a href="#galeria">Galería</a></li>
        <li><a href="#contacto">Contacto</a></li>
        <li><a class="btn btn-primary ml-4">Hazte Socio</a></li>
      </ul>
    </nav>
  </header>
</template>