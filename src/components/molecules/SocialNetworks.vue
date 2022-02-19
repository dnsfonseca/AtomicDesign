<template>
  <div class="social-networks">
    <SocialLink
      name="Github"
      to="https://github.com/dnsfonseca"
      icon="github.svg"
      target="_blank"
    />
    <SocialLink
      name="Twitter"
      to="https://twitter.com"
      icon="twitter.svg"
      target="_blank"
    />
    <SocialLink
      name="Facebook"
      to="https://facebook.com"
      icon="facebook.svg"
      target="_blank"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  components: { SocialLink }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
