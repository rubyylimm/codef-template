---
layout: "@layouts/ArticleLayout.astro"
title: Matcha Swissroll 
date: 14 July 2022
description: A taste of Japan! 
image: /images/my-second-article/matcha.avif
---

<div class="star-rating">
  <input type="radio" id="star5" name="rating" value="5" />
  <label for="star5">&#9733;</label>
  <input type="radio" id="star4" name="rating" value="4" />
  <label for="star4">&#9733;</label>
  <input type="radio" id="star3" name="rating" value="3" />
  <label for="star3">&#9733;</label>
  <input type="radio" id="star2" name="rating" value="2" />
  <label for="star2">&#9733;</label>
  <input type="radio" id="star1" name="rating" value="1" />
  <label for="star1">&#9733;</label>
</div>

<style>
.star-rating {
  display: inline-block;
  font-size: 25px;
}
.star-rating input[type="radio"] {
  display: none;
}
.star-rating label {
  color: #ddd;
  float: right;
  cursor: pointer;
}
.star-rating input[type="radio"]:checked ~ label {
  color: #ffdd00;
}
</style>

<script>
const starInputs = document.querySelectorAll('.star-rating input[type="radio"]');

starInputs.forEach((input) => {
  input.addEventListener('change', () => {
    const rating = input.value;
    // Perform any desired actions with the selected rating, such as sending it to a server or updating a display.
    console.log('Selected rating:', rating);
  });
});
</script>
<p> How much do you like matcha? (1 star-not so much, 5 star-I love it!) </p>

Indulge in the delicate flavors of our Matcha Swiss Roll, a delightful Japanese-inspired dessert that combines the rich earthiness of matcha with the lightness of a fluffy sponge cake. This elegant and visually appealing treat is as delightful to the eyes as it is to the taste buds.

Most matcha swissrolls come with red bean and whipped cream filling. We see this is different at Sakurado, a chinatown japanese bakery.

<img src=/images/my-second-article/diffrichfilling.jpg
alt="Sakurado's rich matcha filling">

Another one of my favourite cafes would be  <a href="https://www.wacafe.co.uk/"> WA Cafe in Covent Garden </a>. A small cafe with many rich matcha desserts. 

<img src=/images/my-second-article/swisswa.jpg
alt="matcha swiss roll">

<img src=/images/my-second-article/cake.wa.webp
alt="thick cake">


