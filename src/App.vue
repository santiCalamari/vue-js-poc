<template>
 <div>
    <my-head></my-head>
    <my-header></my-header>
    <my-main></my-main>
    <my-preview-footer></my-preview-footer>
    <my-footer></my-footer>
 </div>
</template>

<script>
  import Head from './components/Head'
  import Header from './components/Header'
  import Main from './components/Main'
  import PreviewFooter from './components/PreviewFooter'
  import Footer from './components/Footer'

  export default {
     components:{
        'my-head':Head,
        'my-header':Header,
        'my-main':Main,
        'my-preview-footer':PreviewFooter,
        'my-footer':Footer
     }
  }
</script>

<style>
  {
      box-sizing:border-box;
      margin:0;
  }
</style>
