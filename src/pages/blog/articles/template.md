---
layout: "@layouts/ArticleLayout.astro"
title: template
# description: example
date: 00 July 2022
image: /images/...
imageDescription: template text
draft: true
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
<p> How much do you like cheesecakes? (1 star-not so much, 5 star-I love it!) </p>

content here