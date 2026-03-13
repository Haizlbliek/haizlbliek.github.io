---
layout: wiki-item
title: Cactus
infobox_image: /assets/img/cactus.png
infobox_dev_image: /assets/img/devtools-cactus.png
infobox_object: Cactus
---

Cactus is an organic object used for decoration and gameplay. It resembles a real-life cactus and features a distinct, slow-swaying visual effect.

{% include todo.html text="Add dev tools version of thumbnail" %}
{% include todo.html text="Add interactive demostration" %}

## Object Settings

### Seed

Determines the RNG's seed. This directly affects how the cactus is generated.

<div class="wiki-gallery">
	{% include figure.html image="/assets/img/cactus.png" %}
	{% include figure.html image="/assets/img/cactus-alternate.png" %}
</div>

### Size

Adjusts the density of the cactus. Higher values increase the number of nubs and branches generated, while lower values result in a simpler, smoother shape.

<div class="wiki-gallery">
	{% include figure.html image="/assets/img/cactus-intense.png" caption="A cactus with 200% size" %}
	{% include figure.html image="/assets/img/cactus-weak.png" caption="A cactus with 50% size" %}
</div>

### Scale

Changes the overall dimensions of the cactus. This shrinks or enlarges the entire object without changing the number of nubs or its general shape.

<div class="wiki-gallery">
	{% include figure.html image="/assets/img/cactus-large.png" caption="A cactus with 200% scale" %}
	{% include figure.html image="/assets/img/cactus-small.png" caption="A cactus with 50% scale" %}
</div>

### Product

Determines what the cactus grows. You can set it to produce [Cactus Spears](/fwutils/objects/cactusspear.html), [Cactus Fruit](/fwutils/objects/cactusfruit.html), both, or neither.

<div class="wiki-gallery">
	{% include figure.html image="/assets/img/cactus-fruit.png" caption="A Cactus full of Cactus Fruit" %}
	{% include figure.html image="/assets/img/cactus-spear.png" caption="A Cactus with a Cactus Spear" %}
	{% include figure.html image="/assets/img/cactus-both.png" caption="A Cactus with both a Cactus Fruit and a Cactus Spear" %}
</div>

### Hue, Saturation, and Value

Adjusts the color of the Cactus. Offset from the original green color.

{% include figure.html image="/assets/img/cactus-colored.png" caption="A Cactus with custom coloring" %}