<template>
  <main>
    <h1>Spanico</h1>
    <div class="notas">
      <div class="nota">
        <h3 class="titulo">Leccion 1</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id natus, veniam magni ratione voluptas quod perferendis quidem, esse optio veritatis obcaecati cupiditate aliquid ipsam nemo cum quisquam eius impedit sapiente.</p>
      </div>

      <div class="nota">
        <h3 class="titulo">Leccion 2</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id natus, veniam magni ratione voluptas quod perferendis quidem, esse optio veritatis obcaecati cupiditate aliquid ipsam nemo cum quisquam eius impedit sapiente.</p>
      </div>

      <div class="nota">
        <h3 class="titulo">Leccion 3</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id natus, veniam magni ratione voluptas quod perferendis quidem, esse optio veritatis obcaecati cupiditate aliquid ipsam nemo cum quisquam eius impedit sapiente.</p>
      </div>

      <div class="nota">
        <h3 class="titulo">Leccion 4</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id natus, veniam magni ratione voluptas quod perferendis quidem, esse optio veritatis obcaecati cupiditate aliquid ipsam nemo cum quisquam eius impedit sapiente.</p>
      </div>

      <div class="nota">
        <h3 class="titulo">Leccion 4</h3>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id natus, veniam magni ratione voluptas quod perferendis quidem, esse optio veritatis obcaecati cupiditate aliquid ipsam nemo cum quisquam eius impedit sapiente.</p>
      </div>
    </div>
    <div class='button'>
      <NuxtLink  to="/notaForm">+ anadir nota</NuxtLink>      
    </div>
  </main>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&display=swap');

* {
  font-family: 'Libre Baskerville', serif;
  box-sizing: border-box;
}

h1 {
  text-align: center;
}

.button {
  text-align: right;
  max-width: 90%;
}

.notas{
  max-width: 90%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 3%;
}

.nota {
  background-color:beige;
  flex-basis: 22.5%;
  margin-bottom: 3%;
  padding: 5px;
}



</style>
