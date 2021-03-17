<template>
  <div>
      <button  v-if="count>=1" class=" btn btn-success mr-2" v-on:click="count=1">{{1}}
      </button>
      <button v-if="count<2" class=" btn btn-outline-success disabled mr-2" v-on:click="count=2">{{2}}
      </button>
      <button v-if="count>=2"  class=" btn btn-success mr-2" v-on:click="count=2">{{2}}
      </button>
      <button v-if="count<3" class=" btn btn-outline-success disabled mr-2" v-on:click="count=3">{{3}}
      </button>
      <button v-if="count>=3"  class=" btn btn-success mr-2" v-on:click="count=3">{{3}}
      </button>
  </div>
   <Step1 v-if="count===1" class="mt-5"/>
   <Step2 v-if="count===2" class="mt-5"/>
   <Step3 v-if="count===3" class="mt-5"/>
   <button  class=" btn btn-primary mt-5 mr-2" v-on:click="count>1?count--:count=1">Previous Step
      </button>
      <button class="btn btn-info disabled mt-5 mr-2">{{count}}</button>
   <button  class=" btn btn-primary mt-5 mr-2" v-on:click="count>=3?count=3:count++">Next Step
      </button>
</template>

<script>
import Step1 from "./Step1.vue"
import Step2 from "./Step2.vue"
import Step3 from "./Step3.vue"
export default {
data(){
    return{count:1}
},
components: 
{Step1,Step2,Step3}
}
</script>
