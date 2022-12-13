<template>
  <h1>Products</h1>
  <div style="display: grid; grid-template-columns: repeat(4, 1fr); margin: auto;">
    <div class="card" v-for="item in arr" :key="item" style="width: 18rem; grid-column: span 1; margin: auto;">
      <img :src="item.imgSrc" class="card-img-top">
      <div class="card-body">
        <h5 class="card-title">{{item.brandName}}</h5>
        <p class="card-text">This is a great {{item.type}}!</p>
        <p>Quantity: {{item.quantity}}</p>
        <div class="btns d-flex">
          <button class="btn btn-dark m-1"  v-on:click="item.quantity++">Increase quantity</button>
          <button class="btn btn-danger m-1"  v-on:click="item.quantity--">Decrease quantity</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Products',

  data (){
    return {
  arr : [
  {
    brandName: 'Adidas',
    type: 'shoe',
    color: 'black',
    imgSrc: 'https://picsum.photos/200/300',
    quantity: 10,
  },
  {
    brandName: 'Reebok',
    type: 'shoe',
    color: 'blue',
    imgSrc: 'https://picsum.photos/200/300',
    quantity: 10,
  },
  {
    brandName: 'New Balance',
    type: 'pants',
    color: 'grey',
    imgSrc: 'https://picsum.photos/200/300',
    quantity: 10,
  },
  {
    brandName: 'Under Armour',
    type: 'socks',
    color: 'white',
    imgSrc: 'https://picsum.photos/200/300',
    quantity: 10,
  }
]
}
  }
}

</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
