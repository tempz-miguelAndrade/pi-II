<template>
  <header>
    <div>
      <h1>J&J</h1>
      <p>June 23rd, 2025</p>
    </div>
    <nav>
      <ul>
        <li>
          <a href="#">HOME</a>
        </li>
        <li>
          <a href="#">OUR STORY</a>
        </li>
        <li>
          <a href="#">DETAILS</a>
        </li>
        <li>
          <a href="#">RSVP</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  background-color: #414141;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1vw 3vw;
}

div {
  display: flex;
  gap: 15px;
  align-items: center;
}
div h1 {
  font-weight: bold;
  font-size: 2.5rem;
}

nav ul {
  display: flex;
  gap: 20px;
}
h1,
p,
a {
  color: white;
}
a {
  text-decoration: underline solid 1px;
}

/* === RESPONSIVIDADE === */
@media only screen and (max-width: 600px) {
  header {
    flex-direction: column;
    gap: 15px;
    padding: 5vw;
  }

  div h1 {
    font-size: 2rem;
  }

  nav ul {
    gap: 15px;
    flex-wrap: wrap;
    justify-content: center;
  }

  nav ul li a {
    font-size: 0.9rem;
  }
}
</style>
