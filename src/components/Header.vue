<template>
  <div>
    <b-nav>
      <b-nav-item diasbled><b>Quiz App</b></b-nav-item>
      <b-nav-item disabled>{{numCorrect}}/{{numTotal}}</b-nav-item>
    </b-nav>  
  </div>
</template>

<script>
export default{
  props:[
    'numCorrect',
    'numTotal'
  ]
}
</script>