<template>
  <div id="HeaderLayout">
    <div class="container">
      <img
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSqBT2XkDgRuW4jV4rTfUk1gqJ0dUnS2Ea11A&s"
        alt=""
        width="80"
        height="80"
      />
      <ul>
        <li @click="$router.push('/')">Menu1</li>
        <li @click="$router.push('/menu2')">Menu2</li>
        <li @click="$router.push('/menu2')">Menu3</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderLayout",
};
</script>
<style scoped>
.container {
  background-color: #808080;
  width: 100%;
  height: 100px;
  padding-right: 3rem;
  padding-left: 3rem;
  display: flex;
  flex-direction: row;
  align-items: center;
}

ul {
  list-style: none;
  display: flex;
}

ul li {
  margin-left: 100px;
  font-size: 20px;
  font-weight: bolder;
}
</style>
