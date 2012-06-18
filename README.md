# PHONEGAP BUILD JS
 
### A client interface for the Phonegap Build API using javascript


##Dependencies:
* nodejs  Documentation available at http://nodejs.org
		  This tool was developed using v0.6.19, but previous versions might be supported.
* request (nodejs module).  Visit https://github.com/mikeal/request for additional details.
* mime    (nodejs module).  Visit https://github.com/bentomas/node-mime for additional details.

##Description
Phonegap Build JS is a client interface for the Phonegap Build API.  Given that the API interacts using JSON-formatted strings, Javascript seems like the logical choice to process its input and output.

A commandline interface that partially implements the API has been provided.  
<pre>
   node interface.js
</pre>

The interace allows you to interact with the API, but it is mainly provided to serve as an example on how to use the tool.  You are encouraged to implement your own driver that fits your needs.
