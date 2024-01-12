<template>
    <div>
      <ProductList />
      <ProductForm />
    </div>
  </template>
  
  <script>
  import ProductList from './components/productList.vue';
  import ProductForm from './components/productForm.vue';
  
  export default {
    components: {
      ProductList,
      ProductForm
    }
  };
  </script>