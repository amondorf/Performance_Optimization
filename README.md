Steps to optimize Website Performance and FPS:

* added media="print" to print link href
* made JS analytics async
* compressed images with https://compressor.io/
* for index.html: inlined style.css
* for other CSS: minified CSS with https://cssminifier.com/
* compressed JS with https://jscompress.com/
* further image reduction and resizing with picmonkey.com
* deleted google fonts

* change pizza number from 200 to 80
* function updatePositions: replace querySelectorAll with getElementsByClassName
* function updatePositions: take out the calculation 'document.body.scrollTop / 1250' out of the for loop for a faster run
* function updatePositions: replace left with transform
* pizza.html: put <div id="movingPizzas1" class="col-md-12"> in its own row to center pizzas, as suggested on the Forum
