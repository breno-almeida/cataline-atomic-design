<template>
  <div class="services">
    <Service title="Front End " description="Lorem" />
    <Service title="Back End " description="Lorem" />
    <Service title="Manutenção " description="Lorem" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
