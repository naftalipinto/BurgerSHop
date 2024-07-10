<template>
    <nav>
        <router-link to="/">Home</router-link> |
        <router-link to="/request">Request</router-link>
      </nav>
      <router-view/>
</template>
<script>
export default{
    name:'NavBar'
}
</script>