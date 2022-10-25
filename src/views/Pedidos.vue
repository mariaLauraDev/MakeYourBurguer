<template>
  <div class="main-container">
    <h1>This is an pedidos page</h1>
    <p> Pedidos </p>
    <Dashboard />
    
  </div>
</template>

<script>
import Dashboard from "../components/Dashboard.vue"

export default {
  name: 'Pedidos',
  components:{
    Dashboard
  }
}
</script>
