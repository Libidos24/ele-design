<demo>
禁止选择switch
</demo>
<template>
  <ele-switch v-model:value="checked" disabled />
</template>

<script>
import Switch from '../../lib/switch/Switch.vue'
import { ref } from 'vue'
export default {
  components: {
    'ele-switch': Switch,
  },
  setup() {
    const checked = ref(false)
    return { checked }
  },
}
</script>
