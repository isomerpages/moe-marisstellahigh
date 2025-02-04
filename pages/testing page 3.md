---
title: testing page 3
permalink: /testing-page-3/
variant: markdown
description: ""
---
<style>
.accordion > input[type="checkbox"] {
  position: absolute;
  left: -100vw;
}

.accordion .content {
  overflow-y: hidden;
  height: 0;
  transition: height 0.3s ease;
}

.accordion > input[type="checkbox"]:checked ~ .content {
  height: auto;
  overflow: visible;
}

.accordion label {
  display: block;
}

/*
 Styling
*/
body {
  font: 16px/1.5em "Overpass", "Open Sans", Helvetica, sans-serif;
  color: #333;
  font-weight: 300;
}

.accordion {
  margin-bottom: 1em;
}

.accordion > input[type="checkbox"]:checked ~ .content {
  padding: 15px;
  border: 1px solid #e8e8e8;
  border-top: 0;
}

.accordion .handle {
  margin: 0;
  font-size: 1.125em;
  line-height: 1.2em;
}

.accordion label {
  color: #333;
  cursor: pointer;
  font-weight: normal;
  padding: 15px;
  background: #e8e8e8;
}

.accordion label:hover,
.accordion label:focus {
  background: #d8d8d8;
}

.accordion .handle label:before {
  font-family: 'fontawesome';
  content: "\f054";
  display: inline-block;
  margin-right: 10px;
  font-size: .58em;
  line-height: 1.556em;
  vertical-align: middle;
}

.accordion > input[type="checkbox"]:checked ~ .handle label:before {
  content: "\f078";
}


/*
 Demo purposes only
*/
*,
*:before,
*:after {
  box-sizing: border-box;
}

body {
  padding: 40px;
}

a {
  color: #06c;
}

p {
  margin: 0 0 1em;
}

h1 {
  margin: 0 0 1.5em;
  font-weight: 600;
  font-size: 1.5em;
}

.accordion {
  max-width: 65em;
}

.accordion p:last-child {
  margin-bottom: 0;
}

</style>

<h1>BJCP Style 26. Trappist Ale</h1>
<section class="accordion">
  <input checked="checked" id="handle1" name="collapse" type="checkbox">
  <h2 class="handle">
    <label for="handle1">26A. Trappist Single</label>
		
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A pale, bitter, highly attenuated and well carbonated Trappist ale, showing a fruity-spicy Trappist yeast character, a spicy-floral hop profile, and a soft, supportive grainy-sweet malt palate.</p>
    <p><strong>History:</strong> While Trappist breweries have a tradition of brewing a lower-strength beer as a monk’s daily ration, the bitter, pale beer this style describes is a relatively modern invention reflecting current tastes. Westvleteren first brewed theirs in 1999, but replaced older lower-gravity products.</p>
  </div>
</section>
<section class="accordion">
  <input id="handle2" name="collapse2" type="checkbox">
  <h2 class="handle">
    <label for="handle2">26B. Belgian Dubbel</label>
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A deep reddish-copper, moderately strong, malty, complex Trappist ale with rich malty flavors, dark or dried fruit esters, and light alcohol blended together in a malty presentation that still finishes fairly dry.</p>
    <p><strong>History:</strong> Originated at monasteries in the Middle Ages, and was revived in the mid-1800s after the Napoleonic era.</p>
  </div>
</section>
<section class="accordion">
  <input id="handle3" name="collapse2" type="checkbox">
  <h2 class="handle">
    <label for="handle3">26C. Belgian Tripel</label>
  </h2>
  <div class="content">
    <p><strong>Overall Impression:</strong> A pale, somewhat spicy, dry, strong Trappist ale with a pleasant rounded malt flavor and firm bitterness. Quite aromatic, with spicy, fruity, and light alcohol notes combining with the supportive clean malt character to produce a surprisingly drinkable beverage considering the high alcohol level.</p>
    <p><strong>History:</strong> Originally popularized by the Trappist monastery at Westmalle.</p>
  </div>
</section>

<p><small>Source: <cite><a href="https://www.bjcp.org/stylecenter.php">BJCP Style Guidelines</a></cite></small></p>

