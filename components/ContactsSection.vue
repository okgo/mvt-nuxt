<template lang="pug">
  section#contacts.c-contacts-section
    .container
      .inline-block.half-width
        .c-contacts-section__message
          h2 Get a truck
          form.c-contacts-section__form(method="POST" action="https://formspree.io/julie@poltranslogistics.com")
            .row
              label Name
              input(
                type="text"
                name="name"
                placeholder="Your Name"
                required="required")
            .row
              label E-mail
              input(
                name="_replyto"
                placeholder="Your E-mail"
                required="required"
                type="email")
            .row
              label Message
              textarea(
                name="message"
                placeholder="Message"
                required="required")
            .row
              button.black(type="submit") Send

      .inline-block.half-width.clearfix
        .c-contacts-section__content.pull-right
          h4
            |Poltrans logistic
            span Cargo transportation company
          ul.contacts-list
            li
              label Phone
              p
                a(href="tel:267-460-4433") 267-460-4433
            li
              label Phone
              p
                a(href="tel:215-863-7776") 215-863-7776
            li
              label Email
              p
                a(href="mailto:julie@poltranslogistics.com") julie@poltranslogistics.com
            li
              label Adress
              p 611 Alburger Ave Philadelphia PA 19115
</template>
<script>
  export default {

  }
</script>
