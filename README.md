## Marianne Moore's website

A simple Jekyll build.

### Adding new images

A new collection of images can be added using the following include:

	{% include grid-row.html layout="" image-1="" image-2="" image-3="" %}

This `grid-row.html` include accepts the following parameters:

* `layout` - be either: `tall-left`, `tall-right` or `three-col`
* `image-1`, `image-2`, `image-3` - paths to each image

In addition to using blocks for images, square blocks can be used to display text:

* `block-1-title` and `block-1-copy` - create a text block in the first square
* `block-2-title` and `block-2-copy` - create a text block in the second square

### Adding new services

Services are added in the `/prices/index.html` front matter. There are currently 2 list types (`bridal` and `lessons`) which follow the same structure:

	bridal:
	  - service: NAME
	    description: DESCRIPTION
	    price: PRICE

or

	lesson:
	  - service: NAME
	    description: DESCRIPTION
	    price: PRICE

These are then passed into the prices include:

	{% include prices.html list="" %}

Where list accepts either `bridal` or `lesson`.

### Intro blocks

'Intro blocks' are used on the home and prices pages. A new instance can be added anywhere using the following include:

	{% include intro.html title="TITLE" copy="DESCRIPTION" %}

That will produce a text-only block, if a button is required, the following parameters can be included:

* `button-url=""`
* `button-text=""`

This will include a button with the URL described by `button-url=""` and text as described by `button-text=""`.

### Pull blocks

'Pull blocks' are used as break-points between image collections. A new instance can be added anywhere using the following include:

	{% include pull.html title="TITLE" copy="DESCRIPTION" %}