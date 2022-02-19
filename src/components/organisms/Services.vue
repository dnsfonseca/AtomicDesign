<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cupiditate vero voluptatibus corrupti dignissimos dicta commodi modi, rem cumque distinctio, quaerat eum tempora ad iste repudiandae consequatur quis excepturi et fugit!"
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cupiditate vero voluptatibus corrupti dignissimos dicta commodi modi, rem cumque distinctio, quaerat eum tempora ad iste repudiandae consequatur quis excepturi et fugit!"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cupiditate vero voluptatibus corrupti dignissimos dicta commodi modi, rem cumque distinctio, quaerat eum tempora ad iste repudiandae consequatur quis excepturi et fugit!"
    />
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
