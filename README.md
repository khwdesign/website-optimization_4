##Readme for updates##

PageSpeed updates made = 
1. inlined print.css
2. style.css inlined as well
3. async load of analytics.js, now selfhosted
4. removed img style tag, resized image to lossless compression using exact specified size


Pizza page =
1. mover query optimized with redundant items deleted
2. pizza image optimized using kraken.io to lossless
3. timing api query optimized line 505
4. framerate optimized using rAF

run index.html via either uploading the file on an http server running apache with java,
an easier way to run the file would be to use a browser such as google chrome or firefox
and open the file by dragging it into the browser


in order to test the framerate, open the pizza.html file located in the views folder using
google chrome canary and run the javascript console using cmd+option+j on a mac to open
the console and then use your mouse to move the page up and down to correctly verify the 
framerate