# Pure-Javascript-Bootstrap-Masonry

This is a basic example of Masonry Grid in Javascript for beginners. This example uses Bootstrap framework and demonstrates how Masonry Grid is applied after loading of Images.
  
Define the container in which Masonry Grid has to be applied. A web page may contains many images containers but as per project requirement only specific container(s) needs Masonry Grid to be applied. By setting class "masonry" to each container where Masonry Grid need to be applied, container(s) for Masonry Grid is ready.

e.g.:
  &lt;div class="row masonry"&gt;&lt;/div&gt;

Once container is defined, every images inside container should be wraped within a div with class "item".

e.g.:
  &lt;div class="row masonry"&gt;
    &lt;div class="item"&gt;&lt;img src="http://icegroupindia.com/img/events.jpg" class="img-fluid" /&gt;&lt;/div&gt;
  &lt;/div&gt;
  
You can add bootstrap classes to define max image width on the page which can be col-lg-2/col-lg-3/col-lg-4/col-lg-6 which will eqaully distribute images on the page.

e.g.:
   &lt;div class="row masonry"&gt;
    &lt;div class="col-lg-3 item text-center"&gt;&lt;img src="http://icegroupindia.com/img/events.jpg" class="img-fluid" /&gt;&lt;/div&gt;
  &lt;/div&gt;
  
Now declare the Masonry container for js script to identify the area where Masnry grid has to be applied.

e.g.:
  &lt;script&gt;
	var container = document.querySelector(".masonry");   //Name of variable container should not be changed
  &lt;/script&gt;

After declaring container, to use this Masonry Grid in the project "jsMasonry.js" to be included. To include js:
  
  &lt;script src="jsMasonry.js"&gt;&lt;/script&gt;

Thats all. Now the project is ready with Masonry grid.
