<template lang="">
    <div>
        列表页
        <TitleCom/>
        
    </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import TitleCom from '@/components/TitleCom.vue'

export default defineComponent({
  name: 'IndexView',
  components: {
    TitleCom,
  },
});
</script>
<style lang="">
    
</style>