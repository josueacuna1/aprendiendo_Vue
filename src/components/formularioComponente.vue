<template>
    <div>
        <h4> {{ms10}} </h4>
        <form action="">
            <label for="">escribe tu nombre</label>
            <input type="text" placeholder="escribe tu nombre">
            <input type="button" value="enviar">
        </form>
    </div>
</template>
<script>
export default {
    name: 'formularioV',
    data(){
        return{
            ms10: 'Hola que tal contesta las preguntas'
        }
    }
}
</script>