---
title: RSVP
slug: "/rsvp"
featured_image: ''
omit_header_text: true
type: page
menu:
  main:
    weight: 5
---

Use this form to RSVP.

<form class="black-80 sans-serif" name="contact" method="POST" action="/rsvp-thank-you/" role="form" name="rsvp" data-netlify="true" data-netlify-recaptcha="true">
    <label class="f6 b db mb1 mt3 sans-serif mid-gray" for="rsvp-name">Name</label>
    <input type="text" id="rsvp-name" name="name" class="w-100 f5 pv3 ph3 bg-light-gray bn" aria-labelledby="rsvp-name"/>
    <label class="f6 b db mb1 mt3 sans-serif mid-gray" for="rsvp-email">Email</label>
    <input type="email" id="rsvp-email" name="email" class="w-100 f5 pv3 ph3 bg-light-gray bn" aria-labelledby="rsvp-email"/>
    <label class="f6 b db mb1 mt3 sans-serif mid-gray" for="rsvp-total">Total</label>
    <input type="text" id="rsvp-total" name="total" class="w-100 f5 pv3 ph3 bg-light-gray bn" value="1" aria-labelledby="rsvp-total"/>
    <div class="requirements f6 gray glow i ph3 overflow-hidden">Total number in your party, including yourself. Enter 0 if you are able to attend.</div>
    <label class="f6 b db mb1 mt3 sans-serif mid-gray" for="rsvp-message">Message (optional)</label>
    <textarea id="message" name="message" class="w-100 f5 pv3 ph3 bg-light-gray bn h4" aria-labelledby="message"></textarea>
    <div data-netlify-recaptcha="true"></div>
    <input class="db w-100 mv2 white pa3 bn hover-shadow hover-bg-black bg-animate bg-black" type="submit" value="Submit" />
</form>

If you need to make changes to your reservation, please email <a href="mailto:rsvp@nickandmattie.love">rsvp@nickandmattie.love</a>.
