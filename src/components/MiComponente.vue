<template>
    <div id="mi-compoente">
        <hr>
        <h1>Componente nuevo</h1>
        <h3>{{ mensaje2 }}</h3>
        <h5>{{ mensaje3 }}</h5>
        <hr>
    </div>
</template>

<script>
export default {
    name: 'MiComponente',
    data(){
        return{
            mensaje2:'Hola este es un nuevo compoente',
            mensaje3: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industrys standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.'
        }
    }
}
</script>