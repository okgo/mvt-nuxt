<template lang="pug">
  div.c-header
    .container
      a.logo(href="/")
      ul.contacts
        li(v-for="(contact, index) in contacts")
          span.icon(:class="index === 0 ? 'icon--tel' : 'icon--fax'")
          |{{ contact.type }}
          a(:href="`tel:${contact.tel}`") {{ contact.tel }}
</template>
<script>
  export default {
    data() {
      return {
        contacts: [
          { type: "Tel.", tel: "773-691-4361"},
          { type: "Fax", tel: "866-746-9772"},
        ]
      }
    }
  }
</script>
