# Countable

Countable is a JavaScript function to add **live paragraph-, word- and character-counting** to an HTML element. Countable does not rely on any libraries and is very small in size.

## Usage

You can define your own callback function that Countable should use. If you don't pass such a function, the results are simply logged to the console.

```js
new Countable(elem, function (counter) {
  alert(counter.paragraphs, counter.words, counter.characters);
});
```

Countable takes the value from an HTML element and counts paragraphs, words and characters. Those numbers are then returned in an object, accessible by a single parameter in the callback function. In the above example, `counter` holds all numbers returned from Countable.

## Browser Support

Countable has been tested in Chrome (latest), Safari (latest), Firefox (latest), Opera (latest) and Internet Explorer (7+). It is built to support both newer and older browsers. Should you find an error, please submit [an isssue](https://github.com/RadLikeWhoa/Countable/issues) describing the error, including your browser version and operating system.

## About the Author

My name is [Sacha Schmid](http://sachaschmid.ch). I'm a front-end engineer from Switzerland. I am the creator of [SSGS](http://github.com/RadLikeWhoa/SSGS) and [other open source projects](http://github.com/RadLikeWhoa).