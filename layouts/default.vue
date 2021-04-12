<template>
  <div>
  <MainNav/>
  <Nuxt />
  </div>

</template>

<script>
import MainNav from "~/components/MainNav"

export default {
  name: "default",
  components:{
    MainNav
  },
 
  head(){
    return {
      
      link : [{rel: "stylesheet ",type:"text/css", href:"https://unpkg.com/jam-icons/css/jam.min.css"},
      {rel: "stylesheet ",type:"text/css", href:"https://necolas.github.io/normalize.css/8.0.1/normalize.css"}]
    
    }
  }
}
</script>
