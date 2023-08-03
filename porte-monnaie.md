---
layout: page
title: Porte-monnaie
carousels:
  - images:  
    - image: assets/shop/portemonnaie_2.jpg
    - image: assets/shop/portemonnaie_3.jpg
    - image: assets/shop/portemonnaie_1.jpg

---

<h3>Un porte monnaie 100% recyclage</h3>
{% include carousel.html height="50" unit="%" duration="7" number="1" images=carousels %}

<div id="donate-button-container">
<div id="donate-button"></div>
<script src="https://www.paypalobjects.com/donate/sdk/donate-sdk.js" charset="UTF-8"></script>
<script>
PayPal.Donation.Button({
env:'production',
hosted_button_id:'2YFZ2MYHUQA9N',
image: {
src:'https://www.paypalobjects.com/fr_FR/FR/i/btn/btn_donate_LG.gif',
alt:'Bouton Faites un don avec PayPal',
title:'PayPal - The safer, easier way to pay online!',
}
}).render('#donate-button');
</script>
</div>
