<template>
  <div class="drawer">
    <input id="my-drawer-3" type="checkbox" class="drawer-toggle" />
    <div class="drawer-content flex flex-col">
      <AppHeader />
      <main>
        <slot />
      </main>
      <AppFooter />
    </div>
    <div class="drawer-side">
      <label
        for="my-drawer-3"
        aria-label="close sidebar"
        class="drawer-overlay"
      ></label>
      <ul class="menu p-4 w-80 min-h-full bg-base-200">
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#quienes-somos">Quiénes Somos</a></li>
        <li><a href="#servicios">Servicios</a></li>
        <li><a href="#galeria">Galería</a></li>
        <li><a href="#contacto">Contacto</a></li>
        <li class="mt-4"><a class="btn btn-primary">Hazte Socio</a></li>
      </ul>
    </div>
  </div>
</template>
