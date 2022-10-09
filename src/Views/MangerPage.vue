<template>
    <div class="center">
        <h1>התחברות</h1>
        <form>
  <div class="form-group">
    <label for="exampleInputPassword1">תעודת זהות</label>
    <input type="input"  v-model="text" class="form-control" id="exampleInputPassword1" placeholder="ת.ז">
  </div>
  <br>
  <router-link to="/">
    <button type="submit" class="btn return">חזור</button>
  </router-link>
  <button type="submit" class="btn btn-primary" @click="checkID()">התחבר</button>
</form>
    </div>
</template>

<script>

export default {
  data(){
    return { 
        manegers: ["214166860", "214166852"],
        text: ""
    }
  },
  methods: {
    checkID(){
    }
  }
}
</script>

<style scoped>
.center {
  text-align: right;
  margin: auto;
  width: 50%;
  border: 3px solid rgb(0, 0, 0);
  padding: 19px;
}

button{
    border-color: black;
}

.form-control{
    text-align: right;

}
.return{
    position: relative;
   right: 2%;
}

::placeholder {
   text-align: right; 
}
</style>