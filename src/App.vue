<template>
  <div class="container">
    <appHeader></appHeader>  
    <hr>
    <div class="row">
      <appServers></appServers>
      <appServerDetails></appServerDetails>
    </div>
    <hr>
    <appFooter></appFooter>
  </div>
</template>

<script>
import Header from './components/global/Header.vue';
import Servers from './components/servers/Servers.vue';
import ServerDetails from './components/servers/ServerDetails.vue';
import Footer from './components/global/Footer.vue';

export default {
  components: {
    appHeader: Header,
    appServers: Servers,
    appServerDetails: ServerDetails,
    appFooter: Footer
  }
}
</script>

<style>

</style>
