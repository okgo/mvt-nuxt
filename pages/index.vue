<template lang="pug">
  div.wrap

    section.main-section
      .container.wide
        .text
          h1 GET A FREE FREIGHT QUOTE
          p
            b POLTRANS logistic
            |— is an agent for Truckalocity. Truckalocity is a licensed (MC# 360363) and Bonded, ($75,000 Bond @ Pacific Financial) and insured 3rd Party Logistics Provider who has met and exceeded all government requirements and is in good standing with the FMCSA. We have a 30 Day payment record with thousands of contracted carriers. Truckalocity owners have over 30 years of experience.
          .discount
          nuxt-link.button(to="/#contacts") CONTACT US

    section.features-section
      .container.wide
        h2 Our Features
        ul.features-list
          li.features-list__item
            .text-block
              h3 We deliver your loads in time, every time.
              p At <b>Poltrans Brokerage</b> we offer the most reliable carriers at the best rates possible. Don’t worry about checking loads and dealing with claims. Our Certified Master Brokers will handle ANY freight. Put your shipment in good hands. Get a FREE freight quote right away. Quick and Easy. With carriers GUARANTEED to match and exceed all MAP-21 guidelines.
            .image-block
              img(src="~/static/feature-1.jpg", alt="POLTRANS Logistic")
          li.features-list__item.features-list__item--reversed
            .text-block
              h3 BEFORE SECURING YOUR FREIGHT, WE ENSURE
              ul
                li - Insurence Coverage
                li - Safety Protocols
                li - Authorized Carriage
                li We are your top choice for freight shipping!
            .image-block
              img(src="~/static/feature-2.jpg", alt="POLTRANS Logistic")
          li.features-list__item
            .text-block
              h3 TELL US THE RATE RIGHT FOR YOU, WE’LL FIND THE CARRIER RIGHT FOR YOUR FREIGHT.
              p With <b>Poltrans Logistics</b>, you can easily manage all your truckload shipping needs on one platform. It doesn’t matter what trailer you need or what freight you have. In seconds, our team can list all available carriers. We can track your freight movements to ensure the most efficient, effective delivery possible. We know how many trucks are available at any given time in any city in the country, and we find Backhaulers headed home because they provide the lowest rate.

            .image-block
              img(src="~/static/feature-3.jpg", alt="POLTRANS Logistic")

    section.about-section
      .container
        h2 GET A CARRIER
        p Select <b>SUPREME EXPRESS TRUCKING</b> (MC#951832 USDOT# 2841775) and ensure your business is always making the right moves. Get your regional and cross-country shipping done on time, when you need it. <b>SUPREME EXPRESS TRUCKING</b> recognizes the importance of partnership. With our logistic expertise and industry experience, we have the partnerships that last. We match every shipper with the transportation services that fit. You deserve the best rates for the most reliable carriers. Don’t settle for anything less. Our services are second-to-none. Get your goods transported on time, every time. Let our service make your success. Meet your every shipping need without worry. You focus on your business goals, we’ll take care of the rest. If you need responsive, effective and efficient freight brokerage, look no further. Our clients trust us for a reason. Find out why and make your move with <b>SUPREME EXPRESS TRUCKING</b> today. 
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
