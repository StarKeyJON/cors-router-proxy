# cors-router-proxy
<h4>CORS router to solve browser => server CORS inflight request errors</h4>
<p>When making an API call using JavaScript (using XMLHTTPRequest, $.ajax, acios, etc...):</p>
<ul>
  <li> Substitute the actual service URL with the Proxy URL </li>

  <li>Set the query parameters, and body as usual</li>

  <li>Set the actual service URL in a header named 'Target'</li>

  <li>Send the request as usual</li>
 </ul>
The proxy currently passes the "Authorization" header to the target endpoint. You can modify the proxy to pass additional headers (or all of them).


Deploy with one click here:
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## Other Implementations

Check out James Ward's [Saleforce CORS Proxy](https://github.com/jamesward/sf-cors-proxy) written in Scala.
And also: https://github.com/ccoenraets/cors-proxy/blob/master/
