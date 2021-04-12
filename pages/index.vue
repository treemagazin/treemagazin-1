<template>
<main>
  <IndexElements/>
</main>
</template>

<script>
  import IndexElements from "~/components/home/IndexElements"

  export default {
    name:"index",
    components: {
      IndexElements
    },
    head(){
      return {
        title: "Treemagazin: Herramientas financieras para los mejores profesionales y emprendedores",
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Toma las riendas de tu negocio y alcanza tu máximo potencial'
          }]
      }
    }
  }
</script>
