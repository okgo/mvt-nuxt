<template lang="pug">
  div.c-header
    .container
      a.logo(href="/")
      ul.contacts
        li(v-for="(contact, index) in contacts")
          span.icon.icon--tel
          |{{ contact.type }}
          a(:href="`tel:${contact.tel}`") {{ contact.tel }}
</template>
<script>
  export default {
    data() {
      return {
        contacts: [
          { type: "Tel.", tel: "267-460-4433"},
          { type: "Tel.", tel: "215-863-7776"},
        ]
      }
    }
  }
</script>
