<template>
  <footer>
    <section class="date-section">
      <h3>J&J</h3>
      <p>Saturday,</p>
      <p>September 20, 2025</p>
    </section>

    <section class="location-section">
      <div class="info-block">
        <h3>• LOCAL DO CASAMENTO</h3>
        <p>
          A CERIMÔNIA E A RECEPÇÃO SERÃO REALIZADAS EM NOSSA PROPRIEDADE FAVORITA EM ST. AUGUSTINE.
          RECOMENDAMOS CHEGAR COM 20 MINUTOS DE ANTECEDÊNCIA PARA APROVEITAR A VISTA DO JARDIM.
        </p>
        <button class="btn-dark">MAPA</button>
      </div>

      <div class="info-block">
        <h3>• DICAS DE HOTÉIS</h3>
        <p>
          SELECIONAMOS ALGUMAS OPÇÕES CHARMOSAS PARA SUA ESTADIA. PARA SUA CONVENIÊNCIA, RESERVAMOS
          UM BLOCO DE QUARTOS COM TARIFAS ESPECIAIS.
        </p>
        <button class="btn-dark">HOTÉIS</button>
      </div>
    </section>
  </footer>
</template>

<style scoped>
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
  background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url('../image/daniel-mcguire-wvLS1x9cCGU-unsplash.jpg');
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

/* === RESPONSIVIDADE === */
@media only screen and (max-width: 600px) {
  .date-section {
    padding: 10vw 5vw;
  }

  .date-section h3 {
    font-size: 1.5rem;
  }

  .date-section p {
    font-size: 1rem;
  }

  .location-section {
    padding: 10vw 5vw; /* Dá mais espaço horizontal para o texto */
    gap: 40px;
  }

  .info-block h3 {
    font-size: 1.3rem;
  }

  .info-block p {
    font-size: 0.9rem;
  }

  .btn-dark {
    padding: 10px 30px;
    font-size: 0.9rem;
  }
}
</style>
