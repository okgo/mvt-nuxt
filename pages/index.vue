<template lang="pug">
  div.wrap
    section.main-section
      .container.wide
        .text
          h1 We deliver your loads in time, every time.
          p
            b MVT Holding
            |— is a staple in the industry. Making logistics less hectic while achieving consistently reliable delivery of goods. Always on time. Above the competition.
          nuxt-link.button(to="/#contacts") CONTACT US
    section.about-section
      .container
        h2.with-lines About us
        p Our company provides your business with efficient delivery of goods throughout Mid-West and East Coast regions. Rest assured, team of professionals always strive to deliver your freight on time, every time, and in an immaculate condition. Always the best service in the industry with highest customer satisfaction!
    section.features-section
      .container
        .inline-block
          h3.with-lines Our Features
          ul.features-list
            li
              span.icon.icon--delivery
              h5 Fast Delivery
            li
              span.icon.icon--arrival
              h5 Timely Arrival
            li
              span.icon.icon--gps
              h5 GPS Tracking
            li
              span.icon.icon--repair
              h5 Repair
    contacts-section
</template>

<script>
  import ContactsSection from "@/components/ContactsSection";
  export default {
    data() {
      return {

      }
    },
    components: {
      ContactsSection
    },
    mounted () {

    },
    methods: {

    }
  }
</script>
