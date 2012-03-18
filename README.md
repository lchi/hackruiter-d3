Quick and dirty implementation of a bubble visualization of the hackruiter json api.

Size is determined by the number of employees at the company as listed by the api.  As you can probably tell, I didn't change much from the original bubble in d3.  [Original](http://mbostock.github.com/d3/ex/bubble.html).

Usage
-----

Requires d3 - js is included but d3 has its own dependencies (npm, node and vows).  Check out [d3's installation instructions](https://github.com/mbostock/d3).

	$ git clone git://github.com/lchi/hackruiter-d3.git
	$ python -m SimpleHTTPServer 8888 

Then navigate to localhost:8888 and look for bubble.html.  

Output
------

![screenshot](https://github.com/lchi/hackruiter-d3/raw/master/sample.png)