<template>
  <div>
    <p>{{ partners }}</p>
    <div v-for="partner in partners" :key="partner.name"></div>
  </div>
</template>

<script>
// import PartnerListItem from '~/components/PartnerListItem.vue'
export default {
  components: {
    // PartnerListItem
  },
  data() {
    return {
      partners: [
        {
          name: 'Cavezzo',
          imageURL: '~/static/logo-cavezzo.png'
        },
        {
          name: 'Tramontina'
        }
      ]
    }
  }
}
</script>

<style></style>
