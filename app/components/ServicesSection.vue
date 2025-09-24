<script setup>
const services = [
  { name: 'Ahorro Adulto', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/AHORRO-ADULTO-768x499.png' },
  { name: 'Ahorro Productivo', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/AHORRO-PRODUCTIVO-768x417.png' },
  { name: 'Tanda Ahorro', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/TANDA-AHORRO-768x633.png' },
  { name: 'Ahorro Infantil', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/AHORRO-INFANTIL-768x390.png' },
  { name: 'Ahorro Joven', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/AHORRO-JOVEN-768x718.png' },
  { name: 'Mi Ahorro Escolar', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/MI-AHORRO-ESCOLAR-768x583.png' },
  { name: 'Préstamo Agropecuario', img: 'https://cajalahuerta.com/wp-content/uploads/2020/08/PR%C3%89STAMO-ORDINARIO-AGROPECUARIO-768x738.png' },
  { name: 'Préstamo Ordinario', img: 'https://cajalahuerta.com/wp-content/uploads/2020/08/PR%C3%89STAMO-ORDINARIO-768x410.png' },
  { name: 'Crediopción', img: 'https://cajalahuerta.com/wp-content/uploads/2020/08/CREDI-OPCI%C3%93N-768x496.png' },
  { name: 'Credinegocio', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/CREDI-NEGOCIO-768x315.png' },
  { name: 'Préstamo Automático', img: 'https://cajalahuerta.com/wp-content/uploads/2020/08/PR%C3%89STAMO-AUTOM%C3%81TICO-768x346.png' },
  { name: 'Préstamo Despensa', img: 'https://cajalahuerta.com/wp-content/uploads/2020/08/PR%C3%89STAMO-DESPENSA-768x540.png' },
  { name: 'Credi-Check', img: 'https://cajalahuerta.com/wp-content/uploads/2020/01/CREDI-CHEK-768x350.png' },
  { name: 'Préstamo Hipotecario', img: 'https://cajalahuerta.com/wp-content/uploads/2020/08/PR%C3%89STAMO-ORDINARIO-HIPOTECARIO-768x690.png' },
  { name: 'Crece Express', img: 'https://cajalahuerta.com/wp-content/uploads/2022/08/crecexpress-png-768x593.png' },
  { name: 'Eco Credit', img: 'https://cajalahuerta.com/wp-content/uploads/2022/08/Logo-EcoCredit-05-768x390.png' },
]
</script>

<template>
  <section id="servicios" class="py-20 bg-base-100">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">
        Productos Financieros a tu Medida
      </h2>
      <div
        class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6"
      >
        <div v-for="service in services" :key="service.name" class="card card-compact bg-base-200 shadow-xl">
          <figure>
            <img :src="service.img" :alt="service.name" />
          </figure>
          <div class="card-body">
            <h2 class="card-title">{{ service.name }}</h2>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>