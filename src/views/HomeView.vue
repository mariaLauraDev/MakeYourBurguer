<template>
<banner />
  <div class="main-container">
    <h1> monte seu burguer </h1>
    <BurguerForm />

  </div>
</template>

<script>
import Banner from "../components/Banner.vue"
import BurguerForm from "../components/BurguerForm.vue"

export default{
  name: 'HomeView',
  components:{
    Banner,
    BurguerForm
  }
}

</script>
