<template>
    <div>
   <h1>Helo Bilal</h1>
   <test />
   <Data />
   <Form />
    </div>
</template>

<script>

import test from './test.vue'
import Data from './Data.vue'
import Form from '@/components/Form.vue'

    export default {
       name:'Home',
       components:{
           test,
           Data,
           Form
        
       } 
    }
</script>

<style scoped>

</style>