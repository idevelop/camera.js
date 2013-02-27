Camera.js
============

This library offers access to browser camera input using the HTML5 getUserMedia API.

## Usage

	camera.init({
		width: 160,
		height: 120,
		fps: 30,
		mirror: true,

		onFrame: function(canvas) {
			// do something with canvas
		},

		onSuccess: function() {
			// stream succesfully started, yay!
		},

		onError: function(error) {
			// something went wrong on initialization
		},

		onNotSupported: function() {
			// instruct the user to get a better browser
		}
	});


## Examples

* [ASCII Camera](http://idevelop.github.com/ascii-camera/)
* [Predator Vision](http://idevelop.github.com/predator-vision/)

## Supported browsers

* Chrome &ge; 21
* Firefox &ge; 17 (requires `media.navigator.enabled = true` in `about:config`)
* Opera &ge; 12

## Author

**Andrei Gheorghe**

* [About me](http://idevelop.github.com)
* LinkedIn: [linkedin.com/in/idevelop](https://linkedin.com/in/idevelop)
* Twitter: [@idevelop](http://twitter.com/idevelop)

## License

- This code is licensed under the MIT License.
