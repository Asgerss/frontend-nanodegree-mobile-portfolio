## Website Performance Optimization portfolio project

Open index.html in a browser. Now you will find yourself browsing the, now optimized, portfolio of Cameron Pittman. From here look through Camerons different projects. When that is done stop by Cam's Pizzeria, fall in love with one of delicious pizzas, just to be frustrated that the pizzaria is fake, but hey at least the scrolling was silk smooth.

------------------Change log-------------------
Minification of js files and optimization of images have been done using Google PageSpeed built in functions. More Readable versions of the js files have been saved as file.old.js.
General changes for page speed:
- Images for index.html resized
- Analytics asynced
- print.css loading delayed with js
- Web fonts removed
- style.css moved to style tag
Specific changes to main.js for the pizza site:
- The resizePizza function have been reworked:
	- Now the new pizza size is based on % rather than calculating a px width.
 	- The randomPizzaContainer stored as variable to avoid accessing the DOM constantly when iterating through pizzas
- Number of background pizzas changed from 200 to be a function of the window height