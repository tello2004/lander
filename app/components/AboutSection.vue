<template>
  <section id="quienes-somos" class="py-20 bg-base-200">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Nuestra Esencia</h2>
      <div class="flex flex-col lg:flex-row gap-8 items-center">
        <div class="lg:w-1/2">
          <p class="mb-6">
            Somos una sociedad de personas sin ánimo de lucro, que teniendo
            necesidades de ahorro, crédito y educación, y contando con algunos
            recursos para resolverlos, decidimos reunirnos formando una empresa
            cooperativa financiera. Nuestra filosofía se sustenta en elevar el
            nivel de vida de nuestros socios y de la comunidad en general.
          </p>
          <div class="tabs tabs-lifted">
            <input
              type="radio"
              name="my_tabs"
              role="tab"
              class="tab"
              aria-label="Misión"
              checked
            />
            <div
              role="tabpanel"
              class="tab-content bg-base-100 border-base-300 rounded-box p-6"
            >
              <h3 class="font-bold text-lg mb-2">MISIÓN</h3>
              <p>
                Promover el ahorro y crédito con educación financiera, elevando
                la calidad de vida de los socios.
              </p>
            </div>

            <input
              type="radio"
              name="my_tabs"
              role="tab"
              class="tab"
              aria-label="Visión"
            />
            <div
              role="tabpanel"
              class="tab-content bg-base-100 border-base-300 rounded-box p-6"
            >
              <h3 class="font-bold text-lg mb-2">VISIÓN</h3>
              <p>
                Ser una Cooperativa líder, innovadora y eficiente, que
                satisfaga necesidades financieras de los socios en el occidente
                del país.
              </p>
            </div>
          </div>
        </div>
        <div class="lg:w-1/2">
          <div class="collapse collapse-plus bg-base-100 shadow-lg">
            <input type="checkbox" />
            <div class="collapse-title text-xl font-medium">
              Nuestra Historia
            </div>
            <div class="collapse-content">
              <p class="text-sm">
                <strong>Enero de 1991:</strong> Nace la idea por el grupo de
                mujeres UAIM.
              </p>
              <p class="text-sm">
                <strong>25 de Noviembre de 1991:</strong> Inicio oficial de
                operaciones.
              </p>
              <p class="text-sm">
                <strong>1993:</strong> UNISAP nos asesora como grupo en
                formación.
              </p>
              <p class="text-sm">
                <strong>1996:</strong> Se obtiene la figura jurídica como
                Sociedad Cooperativa.
              </p>
              <p class="text-sm">
                <strong>1997:</strong> Se abre la primera ventanilla en La
                Concepción y se adquieren los terrenos de la oficina matriz.
              </p>
              <p class="text-sm">
                <strong>19 de Noviembre de 1999:</strong> Inauguración oficial
                de la oficina matriz.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>