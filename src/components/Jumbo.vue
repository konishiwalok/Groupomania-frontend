<template>
    <div class="jumbotron p-2">
		<h1 class="h2">Bienvenue sur Groupomania! </h1>

	</div>
</template>

<script>
export default {
    name: 'Jumbo',

  data() {
    return {
      
      userId: parseInt(localStorage.getItem("userId")),
      pseudo: "",
    
    };
  },

}
console.log(document.cookie)
</script>

<style  scoped>
.jumbotron{
margin-top:102px;
color:#17a2b8;
}

</style>
