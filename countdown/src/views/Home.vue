<template>
  <div class="home">
   <div> Hello World</div>
   <Counter
   :year="2021"
   :month="4"
   :date="25"
   :hour="23"
   :minute="59"
   :second="59"
   :millisecond="31"/>
  </div>
  
</template>

<script>
import Counter from '@/components/Counter.vue';
// @ is an alias to /src
export default {
  components: {
    Counter 
  }
};
</script>
