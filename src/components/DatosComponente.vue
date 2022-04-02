<template>
    <div>
        <h3>{{ datos }}</h3>
        <h4> {{ datos1 }}</h4>
    </div>
</template>

<script>
export default {
    name: 'DatosComponente',
    data(){
        return{
            datos: 'cargado de datos desde otro componente',
            datos1: 'hola Mexico'
        }
    }
}
</script>