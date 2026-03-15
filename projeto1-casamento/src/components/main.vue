<template>
  <main>
    <section class="banner">
      <h2>JENNY & JASON</h2>
      <p class="love-banner">With love, 2025</p>
    </section>

    <section class="grid-section">
      <div class="grid-item registry">
        <span>Registry</span>
      </div>
      <div class="grid-item details">
        <span>The details</span>
      </div>
      <div class="grid-item story">
        <span>Our story</span>
      </div>
      <div class="grid-item rsvp">
        <span>RSVP</span>
      </div>
    </section>

    <section class="registry-banner">
      <h2>REGISTRY</h2>
      <p>SUA VINDA É NOSSA ALEGRIA!</p>
      <button class="btn-dark">REGISTRE-SE</button>
    </section>

    <section class="date-section">
      <h3>J&J</h3>
      <p>Saturday,</p>
      <p>September 20, 2025</p>
    </section>

    <section class="location-section">
      <div class="info-block">
        <h3>• LOCAL DO CASAMENTO</h3>
        <p>A CERIMÔNIA E A RECEPÇÃO SERÃO REALIZADAS EM NOSSA PROPRIEDADE FAVORITA EM ST. AUGUSTINE. RECOMENDAMOS CHEGAR COM 20 MINUTOS DE ANTECEDÊNCIA PARA APROVEITAR A VISTA DO JARDIM.</p>
        <button class="btn-dark">MAPA</button>
      </div>

      <div class="info-block">
        <h3>• DICAS DE HOTÉIS</h3>
        <p>SELECIONAMOS ALGUMAS OPÇÕES CHARMOSAS PARA SUA ESTADIA. PARA SUA CONVENIÊNCIA, RESERVAMOS UM BLOCO DE QUARTOS COM TARIFAS ESPECIAIS.</p>
        <button class="btn-dark">HOTÉIS</button>
      </div>
    </section>
  </main>
</template>

<style scoped>
/* --- BANNER --- */
section.banner {
  text-align: center;
  align-items: center;
  justify-content: center;
  margin-top: 2vw;
}

section.banner h2 {
  font-size: 8vw;
  font-weight: normal;
  margin: 1vw 2vw;
}

.love-banner {
  background-image: url('../image/enrico-bet-IicyiaPYGGI-unsplash.jpg');
  background-size: cover;
  background-position: center;
  padding: 12vw;
  font-weight: bold;
  font-size: 2.5rem;
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* --- GRID DE CARDS --- */
.grid-section {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  padding: 5vw 20vw;
}

.grid-item {
  aspect-ratio: 1;
  background-size: cover;
  background-position: center;
  border-radius: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 2rem;
  font-weight: normal;
  text-decoration: underline solid 1px;
  text-shadow: 1px 1px 5px rgba(0,0,0,0.5);
  cursor: pointer;
}

.registry { background-image: url('../image/jeremy-wong-weddings-K8KiCHh4WU4-unsplash.jpg'); }
.details { background-image: url('../image/hilal-kh-vk2Yjr1p2rY-unsplash.jpg'); }
.story { background-image: url('../image/sandy-millar-8vaQKYnawHw-unsplash.jpg'); }
.rsvp { background-image: url('../image/daniel-mcguire-wvLS1x9cCGU-unsplash.jpg'); }

/* --- REGISTRY--- */
.registry-banner {
  background-image: url('../image/joel-holland-TRhGEGdw-YY-unsplash.jpg');
  background-size: cover;
  background-position: center;
  text-align: center;
  padding: 8vw 2vw;
  color: white;
}

.registry-banner h2 {
  font-size: 3rem;
  font-weight: normal;
  margin-bottom: 10px;
}

.registry-banner p {
  font-size: 1.2rem;
  letter-spacing: 2px;
}

/* --- ESTILO GLOBAL DE BOTÃO --- */
.btn-dark {
  background-color: #414141;
  color: white;
  border: none;
  padding: 12px 40px;
  border-radius: 25px;
  font-size: 1rem;
  margin-top: 20px;
  cursor: pointer;
  opacity: 0.9;
}

.btn-dark:hover {
  opacity: 1;
}

/* --- DATA --- */
.date-section {
  text-align: center;
  padding: 5vw;
}

.date-section h3 {
  font-size: 2rem;
  margin-bottom: 15px;
}

.date-section p {
  font-size: 1.2rem;
  margin: 5px 0;
}

/* --- LOCAL/HOTÉIS --- */
.location-section {
  background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('../image/daniel-mcguire-wvLS1x9cCGU-unsplash.jpg');
  background-size: cover;
  background-position: center;
  color: white;
  text-align: center;
  padding: 6vw 15vw;
  display: flex;
  flex-direction: column;
  gap: 50px;
}

.info-block h3 {
  font-size: 1.8rem;
  margin-bottom: 15px;
}

.info-block p {
  font-size: 1rem;
  line-height: 1.6;
  margin: 0 auto;
  max-width: 600px;
}
</style>
