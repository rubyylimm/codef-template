---
layout: "@layouts/ArticleLayout.astro"
title: burnt cheesecake 
date: 28 June 2023 
description: Japanese style burnt cheesecake that melts in your mouth. Click here to find out more. 
image: /images/my-third-article/cheesecake.avif
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


<span style="font-family: 'Times new roman', bold;"> 
Indulge in the delightful flavors of a Burnt Cheesecake, a unique and delicious twist on the classic cheesecake. This unconventional dessert captures the essence of a perfectly caramelized exterior with a creamy and luscious interior.

Whether you're a cheesecake enthusiast or simply looking to explore new desserts, the Burnt Cheesecake will surprise and delight your taste buds with its unique combination of flavors and textures. My favourite place in London to get a good creamy burnt cheesecake is from a Japanese cake shop at Chinatown, London - <a href="https://lechouxlondon.com/products/copy-of-lemon-meringue-tart"> Sakurado </a>
</span>

Other desserts at Sarukado: 


<img 
height="1000"
width="1000"
src=/images/my-third-article/stensil.jpg
alt="Sakurado's fluffy japanese cheese cake"
class="rounded-md h-fit self-center justify-self-center"
/>

<img 
height="1000"
width="1000"
src=/images/my-third-article/crepe.webp
alt="Sakurado's milicrepe slices"
class="rounded-md h-fit self-center justify-self-center"
/>

<img 
height="1000"
width="1000"
src=/images/my-third-article/circlecake.webp
alt="Sakurado's milicrepe slices"
class="rounded-md h-fit self-center justify-self-center"
/>
