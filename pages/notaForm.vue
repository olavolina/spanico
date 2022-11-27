<template>
    <main>
        <h1>Anade nueva nota</h1>
        <div class='button2'>
            <NuxtLink to="/">&lt; volver</NuxtLink>
        </div>
        <form action="">
            <div>
                <input type="text">
            </div>
            <div>
                <textarea name="" id="" cols="30" rows="10"></textarea>
            </div>
            <div>
                <input type="submit" value="Vale">
            </div>
        </form>

    </main>
</template>
  
<script>
export default {
    name: 'notaForm'
}
</script>
  
<style>
.button2 {
    text-align: left;
    max-width: 90%;
    margin: 0 auto;
}

form {
    display: block;
    text-align: center;
    max-width: 90%;
    margin: 0 auto;
}

input[type=text]{
    margin-top: 30px;
    padding: 6px 12px;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    appearance: none;
    border-radius: 4px;
    transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out;
    min-width: 80%;
}

textarea {
    min-width: 80%;
    margin-top: 15px;
    border-radius: 4px;
}

input[type="submit"] {
    width: 10%;
    float: right;
    margin-right: 10%;
    padding: 7px !important;
    font-size: 18px;
    border-radius: 4px;
    background-color: gray;
}

</style>
  