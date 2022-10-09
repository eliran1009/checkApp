<template>
    <div class="home">
        <router-link to="/idan">   
            <button type="button" class="btn btn-light">כניסה</button>
        </router-link>
        <br>
        <br>
        <router-link to="/maneger">   
            <button type="button" class="btn btn-success">כניסת מנהל</button>
        </router-link>

    </div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return { 
        showPopup: false
    }
  },
}
</script>

<style scoped>
.home{
    background-color: #198754;
    padding: 2%;
}
.btn-light{ 
    color: #198754;
}
.btn-success{
    color: #198754;
    background-color: whitesmoke;

}

button{
    position: relative;
    height: 48vh;
    width: 45vw;
    left: 27%;
    border-color: black;
    font-size: 350%;
}
</style>
