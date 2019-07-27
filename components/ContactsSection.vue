<template lang="pug">
  section#contacts.c-contacts-section
    .container
      .inline-block.half-width
        .c-contacts-section__message
          h2.with-lines Talk to us
          form.c-contacts-section__form(method="POST")
            .row
              label Name
              input(name="name" placeholder="Your Name" required="required" type="text")
            .row
              label E-mail
              input(name="_replyto" placeholder="Your E-mail" required="required" type="email")
            .row
              label Message
              textarea(name="message" placeholder="Message" required="required")
            .row
              button.black(type="submit") Send

      .inline-block.half-width.clearfix
        .c-contacts-section__content.pull-right
          h4
            |MVT HOLDING
            span Cargo transportation company
          ul.contacts-list
            li
              label Phone
              p
                a(href="tel:773-691-4361") 773-691-4361
            li
              label Fax
              p
                a(href="tel:773-691-4361") 773-691-4361
            li
              label Adress
              p 2725 Thatcher Ave unit 307 River Grove, IL 60171
</template>
<script>
  export default {

  }
</script>
