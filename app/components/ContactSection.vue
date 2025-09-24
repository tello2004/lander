<template>
  <section id="contacto" class="py-20 bg-base-100">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Ponte en Contacto</h2>
      <div class="flex flex-col lg:flex-row gap-10">
        <div class="lg:w-1/2">
          <form class="space-y-4" @submit.prevent>
            <label class="input input-bordered flex items-center gap-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4 opacity-70"><path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6ZM12.735 14c.618 0 1.093-.561.872-1.139a6.002 6.002 0 0 0-11.215 0c-.22.578.254 1.139.872 1.139h9.47Z" /></svg>
              <input type="text" class="grow" placeholder="Nombre completo" />
            </label>
            <label class="input input-bordered flex items-center gap-2">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" fill="currentColor" class="w-4 h-4 opacity-70"><path d="M2.5 3A1.5 1.5 0 0 0 1 4.5v.793c.026.009.051.02.076.032L7.674 8.51c.205.137.478.137.683 0L14.924 5.325c.025-.012.05-.023.076-.032V4.5A1.5 1.5 0 0 0 13.5 3h-11Z" /><path d="M15 6.954 8.978 9.86a2.25 2.25 0 0 1-1.956 0L1 6.954V11.5A1.5 1.5 0 0 0 2.5 13h11a1.5 1.5 0 0 0 1.5-1.5V6.954Z" /></svg>
              <input type="email" class="grow" placeholder="Correo electrónico" />
            </label>
            <textarea class="textarea textarea-bordered w-full" placeholder="Escribe tu mensaje aquí..." rows="6"></textarea>
            <button type="submit" class="btn btn-primary w-full">
              Enviar Mensaje
            </button>
          </form>
        </div>
        <div class="lg:w-1/2">
          <h3 class="text-xl font-bold mb-4">Información Directa</h3>
          <p class="mb-2"><strong>Dirección:</strong><br />Emiliano Zapata 7. Col Centro. 48850. La Huerta, Jalisco.</p>
          <p class="mb-2"><strong>Teléfonos:</strong><br />357 384 0552<br />357 384 0474</p>
          <p class="mb-4"><strong>Correo:</strong><br /><a href="mailto:unidad.especializada@cajalahuerta.com" class="link link-primary">unidad.especializada@cajalahuerta.com</a></p>
          <div class="w-full h-64 rounded-lg shadow-lg overflow-hidden">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3756.248386472652!2d-104.6468759850889!3d19.48782398697669!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8423806f157f46c9%3A0xe54e6e665c8872b!2sCaja%20Popular%20Inmaculada%20Concepci%C3%B3n%20de%20La%20Huerta!5e0!3m2!1ses-419!2smx!4v1672957456789!5m2!1ses-419!2smx" width="100%" height="100%" style="border:0;" allow="fullscreen" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>