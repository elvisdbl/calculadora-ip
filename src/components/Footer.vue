<template>
  <div class="container">
    <footer class="py-5">
      <div class="row">
        <div class="col-2">
          <h5>Integrantes</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2">
              <a href="https://github.com/elvisdbl" class="nav-link p-0 text-muted">Elvis Bonilla</a>
            </li>
            <li class="nav-item mb-2">
              <a href="https://github.com/Alexandracp" class="nav-link p-0 text-muted">Alexandra Cardenas</a>
            </li>
            <li class="nav-item mb-2">
              <a href="https://github.com/ricardoramirez22" class="nav-link p-0 text-muted">Ricardo Ramirez</a>
            </li>
          </ul>
        </div>

        <div class="col-4 offset-6">
          <form>
            <h5>Ponte en contacto con nosotros</h5>
            <div class="d-flex w-100 gap-2">
              <label for="newsletter1" class="visually-hidden"
                >Direccion de Correo</label
              >
              <input
                id="newsletter1"
                type="text"
                class="form-control"
                placeholder="Direccion de Correo"
              />
              <button class="btn btn-primary" type="button">Enviar</button>
            </div>
          </form>
        </div>

        <p class="text-center text-muted">© 2022 UNEFA</p>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style scoped></style>
