<h1>What is different between Get and POST in PHP?</h1>

<h2>What is GET?</h2>
<br>
GET method is used to appends form data to the URL in name or value pair. If you use GET, the length of URL will remain limited. It helps users to submit the bookmark the result. GET is better for the data which does not require any security or having images or word documents.
<br>
<h2>What is POST?</h2>
POST is a method that is supported by HTTP and depicts that a web server accepts the data included in the body of the message. POST is often used by World Wide Web to send user generated data to the web server or when you upload file.
<h2>Features of GET</h2>
Here, are the important features of GET:
<ul>
<li>It is very easy to bookmark data using GET method.</li>
<li>The length restriction of GET method is limited.</li>
<li>You can use this method only to retrieve data from the address bar in the browser.</li>
<li>This method enables you to easily store the data.</li>
</ul>
<h2>Features of POST</h2>
Here are the important features of POST:
<ul>
<li>POST method request gets input from the request body and query string.</li>
<li>Data passed using the POST method will not visible in query parameters in browser URL.</li>
<li>parameters of POST methods are not saved in browser history.</li>
<li>There is no restriction in sending the length of data.</li>
<li>It helps you to securely pass sensitive and confidential information like login details to server.</li>
</ul>

<h2>GET Method Example</h2>

Here is an example of GET method:

<code>https://www.serajzadeh.com/login.php?user=value1&pass=value2</code>

<h2>POST Method Example</h2>

Here is an example of POST method:

<code>https://www.serajzadeh.com/login.php HTTP/1.1  
Host: www.serajzadeh.com  
user=value1&pass=value2
</code>
<br>
<h2></h2>
<h2>Here are the major differences between GET and POST:</h2>
<table>
<tr>
<th>GET</th>
<th>POST</th>
</tr>
<tr>
<td>In GET method, values are visible in the URL.</td>
<td>In POST method, values are not visible in the URL.</td>
</tr>
<tr>
<td>GET has a limitation on the length of the values, generally 255 characters.</td>
<td>POST has no limitation on the length of the values since they are submitted via the body of HTTP.</td>
</tr>
<tr>
<td>GET performs are better compared to POST because of the simple nature of appending the values in the URL.</td>
<td>It has lower performance as compared to GET method because of time spent in including POST values in the HTTP body.</td>
</tr>
<tr>
<td>This method supports only string data types.</td>
<td>This method supports different data types, such as string, numeric, binary, etc.</td>
</tr>
<tr>
<td>GET results can be bookmarked.</td>
<td>POST results cannot be bookmarked.</td>
</tr>
<tr>
<td>GET request is often cacheable.	</td>
<td>The POST request is hardly cacheable.</td>
</tr>
<tr>
<td>GET Parameters remain in web browser history.	</td>
<td>Parameters are not saved in web browser history.</td>
</tr>
</table>
<h2>Advantages of GET</h2>
Here, are benefits/ pros of using GET:
<ul>
<li>The GET method can retrieve information identified by the request-URl (Uniform Resource Identifier).</li>
<li>GET requests can be viewed in the browser history.</li>
<li>It enables you to save the results of a HTML form.</li>
<li>You can easily use GET method to request required data.</li>
</ul>
<h2>Advantages of POST</h2>
<ul>
<li>This method helps you to determine resource URI.</li>
<li>Specifying a new resource location header is very easy using location header.</li>
<li>You can send a request to accept the entity as a new resource, which is identified by the URI.</li>
<li>You can send user-generated data to the web server.</li>
<li>It is very useful when you do not have any idea about the resource you have to keep in the URL.</li>
<li>Use POST when you need the server, which controls URL generation of your resources.</li>
<li>POST is a secure method as its requests do not remain in browser history.</li>
<li>You can effortlessly transmit a large amount of data using post.</li>
<li>You can keep the data private.</li>
<li>This method can be used to send binary as well as ASCII data.</li>
</ul>
<h2>Disadvantages of GET</h2>
<ul>
<li>GET can&#8217;t be used to send word documents or images.</li>
<li>GET requests can be used only to retrieve data</li>
<li>The GET method cannot be used for passing sensitive information like usernames and passwords.</li>
<li>The length of the URL is limited.</li>
<li>If you use GET method, the browser appends the data to the URL.</li>
<li>You can easily bookmark Query string value in GET</li>
</ul>
<h2>Disadvantages of POST</h2>
<ul>
<li>It is not possible to save data as the data sent by the POST method is not visible in the URL.</li>
<li>You cannot see POST requests in browser history.</li>
<li>This method is not compatible with many firewall setups.</li>
<li>You cannot use spaces, tabs, carnage returns, etc.</li>
<li>This method is not compatible with some firewall setups.</li>
<li>POST method takes lots of time when uploading the large binary file.</li>
</ul>
<h2>KEY DIFFERENCE:</h2>
<ul>
<li>In GET method, values are visible in the URL while in POST method, values are NOT visible in the URL.</li>
<li>GET has a limitation on the length of the values, generally 255 characters whereas POST has no limitation on the length of the values since they are submitted via the body of HTTP.</li>
<li>GET method supports only string data types while POST method supports different data types, such as string, numeric, binary, etc.</li>
<li>GET request is often cacheable while POST request is hardly cacheable.</li>
<li>GET performs are better compared to POST.</li>
</ul>
