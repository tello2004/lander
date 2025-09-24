<script setup>
const branches = [
  { name: 'La Huerta', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/1Sucursal-La-Huerta.png' },
  { name: 'La Concepción', img: 'https://cajalahuerta.com/wp-content/uploads/2022/08/SUCURSAL-LA-CONCEPCION.png' },
  { name: 'Melaque', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/3Sucursal-Melaque.png' },
  { name: 'Cihuatlán', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/4Sucursal-Cihuatla%CC%81n-768x496.png' },
  { name: 'Hidalgo', img: 'https://cajalahuerta.com/wp-content/uploads/2021/09/SUCURSAL-HIDALGO-768x492.png' },
  { name: 'Emiliano Zapata', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/7Sucursal-Emiliano-Zapata-768x420.png' },
  { name: 'Barra de Navidad', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/8Sucursal-Barra-de-Navidad-768x414.png' },
  { name: 'Villa Purificación', img: 'https://cajalahuerta.com/wp-content/uploads/2025/07/VILLA-PURIFICACION-768x479.png' },
  { name: 'Cuautitlán', img: 'https://cajalahuerta.com/wp-content/uploads/2025/07/cuautitlan-768x488.png' },
  { name: 'Tequesquitlán', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/11Sucursal-Tequesquitla%CC%81n-768x438.png' },
  { name: 'Casimiro Castillo', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/12Sucursal-Casimiro-Castillo-768x468.png' },
  { name: 'Etzatlán', img: 'https://cajalahuerta.com/wp-content/uploads/2020/06/13Sucursal-Etzatla%CC%81n-768x490.png' },
  { name: 'Tala', img: 'https://cajalahuerta.com/wp-content/uploads/2022/08/SUCURSAL-TALA-768x542.png' },
  { name: 'Ameca', img: 'https://cajalahuerta.com/wp-content/uploads/2023/02/SUCURSAL-AMECA-768x507.png' },
  { name: 'Tequila', img: 'https://cajalahuerta.com/wp-content/uploads/2024/07/image001.png' },
];
</script>

<template>
  <section id="galeria" class="py-20 bg-base-200">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Nuestras Sucursales</h2>
      <div class="carousel rounded-box">
        <div v-for="branch in branches" :key="branch.name" class="carousel-item">
          <img :src="branch.img" :alt="branch.name" />
        </div>
      </div>
    </div>
  </section>
</template>