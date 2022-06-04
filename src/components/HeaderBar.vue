<template>
  <b-navbar toggleable type="dark" variant="dark">
    <b-navbar-brand :to="{ path: '/'}">CRUDApp</b-navbar-brand>

    
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>        
        <b-nav-item :to="{ path: '/'}" >Home</b-nav-item>
        <b-nav-item :to="{ path: '/about'}">About</b-nav-item> 
      </b-navbar-nav>
    </b-collapse>

  </b-navbar>
</template>

<script>
export default {
  name: "HeaderBar",
};
</script>