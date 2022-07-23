<template>
  <div class="nav">
    <div class="logo">
      <h1>HUDA~</h1>
    </div>
    <div>
      <ul>
        <li>Home</li>
        <li>About us</li>
        <li>contact us</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav {
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-content: center;
  background: rgb(179, 245, 193);
}
h1 {
  color: rgb(70, 70, 70);
  text-shadow: 3px 3px #05fc05;
}

ul {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
li {
  list-style: none;
  color: rgb(70, 70, 70);
  font-size: 1.2rem;
  padding: 5px;
  margin: 5px;
  border: 1px solid rgb(6, 119, 16);
  border-radius: 10px;
}
li:hover {
  background: rgb(6, 119, 16);
  color: white;
}
@media screen and (max-width: 512px) {
  .nav {
    padding: 5px;
    flex-direction: column;
  }
  h1 {
    text-align: center;
    font-size: 30px;
    margin-bottom: 3px;
  }
  ul {
    padding: 0 5px;
    align-items: normal;
    display: block;
    text-align: center;
  }
  li {
    font-size: 0.8rem;
  }
}
</style>
