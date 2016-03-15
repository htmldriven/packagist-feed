# Packagist Feed

Simple JavaScript-driven HTML widget for displaying list of published packages as defined in packagist.org.

## Examples

[![Packagist Feed Example](http://www.htmldriven.com/assets/images/projects/packagist-feed.png)](http://www.htmldriven.com/)

Full demo is available at [www.htmldriven.com](http://www.htmldriven.com/).

## Installation

Installing the Packagist Feed is easy, simply download the source code and add link to it in your HTML:

```html
<!-- packagist-feed CSS theme -->
<link rel="stylesheet" href="link/to/packagist.feed.css">

<!-- packagist-feed JS -->
<script type="text/javascript" src="link/to/packagist.feed.js"></script>
```

## Usage

Once you linked the required files, you simply call:

```html
<script type="text/javascript">
Packagist.feed({
	vendor: 'htmldriven', // package vendor name
	selector: '#packagist-feed' // element which serves as a container for Packagist Feed HTML
});
</script>
```

You can create packagist feed several times, it's up to you how many feeds you want to show.
Example of multiple Packagist Feeds being used on the same page is available at [www.htmldriven.com](http://www.htmldriven.com/).

## License

Packagist Feed is licensed under the [The MIT License](./LICENSE).
