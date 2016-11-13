<template>
<div>
 
  
      
    
    <p class="fire-p"><slot></slot></p>
    
   
</div>
</template>
<script>

export default {
data () {
return {

}
}
}
</script>
<style type="text/eqcss">

  

  @element '.fire-p'{

  $this {
    display: block;
    overflow: hidden;
    max-width: 75ch;
    float: left;
    border: 1px solid violet;
    background:black;
    color:white;
    max-width: calc(100% / eval("parentNode.children.length") );
  }
}


      
</style>
