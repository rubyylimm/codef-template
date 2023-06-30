---
layout: "@layouts/ArticleLayout.astro"
title: Lemon tart
date: 28 July 2023
description: Thinking of trying one of these? Click read more to see where you can find them!
image: /images/my-first-article/lemontart.avif
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
<p> How much do you like lemon tarts? (1 star-not so much, 5 star-I love it!) </p>

<span style="font-family: 'Times new roman', bold;"> As a huge fan of lemon tarts, I have tried mastering the technique of replicating this Lemon Meringue Tart from <a href="https://lechouxlondon.com/products/copy-of-lemon-meringue-tart"> Le Croux in London. </a> This elegant dessert showcases the vibrant flavors of fresh lemons combined with a buttery, flaky crust, resulting in a delightful treat that will captivate your taste buds. </span> 

Le Choux, located at Lambroke Grove, is mostly known for their choux and puff pastries. However their lemon tart is very overrated and not many people know about it. 

<img src=/images/my-first-article/lechoux.webp
alt="lechoux">

<img src=/images/my-first-article/meringue.webp
alt="lemon meringue pie">



