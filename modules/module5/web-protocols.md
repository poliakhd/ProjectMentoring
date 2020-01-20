# Module5 - Protocols

## HTTP

The **Hypertext Transfer Protocol** (**HTTP**) is an application protocol for distributed, collaborative, hypermedia information systems. **HTTP** is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.

You should focus on such themes:
* **HTTP** flow;
* **HTTP** message formats;
* **HTTP** authentication;
* **HTTP** vs **HTTPS**;

### Links to internet resources

* [An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) - here you can find basic information of **HTTP** protocol; **(EN/RU)**;
* [What is HTTP?](https://www.w3schools.com/whatis/whatis_http.asp) - here you can find basic information of **HTTP** protocol; **(EN)**;
* [HTTP authentication](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication) - here you can find information about **HTTP authentication**; **(EN/RU)**
* [What’s the Difference between HTTP and HTTPS?](https://www.globalsign.com/en/blog/the-difference-between-http-and-https/) - here you can find differences between **HTTP** and **HTTPS**; **(EN)**

## HTTP/2

**HTTP/2** (originally named HTTP/2.0) is a major revision of the HTTP network protocol used by the World Wide Web.

You should focus on such themes:
* **HTTP** vs **HTTP/2** differences;

## Links to internet resources

* [HTTP/2](https://en.wikipedia.org/wiki/HTTP/2) - here you can find basic information of **HTTP/2** protocol; **(EN/RU)**;
* [Introduction to HTTP/2](https://developers.google.com/web/fundamentals/performance/http2) - here you can find basic information of **HTTP/2** protocol; **(EN)**;
* [HTTP/2](https://hpbn.co/http2/) - here you can find a bit more information about **HTTP/2** and how it works; **(EN)**
* [HTTP vs HTTP/2](https://www.digitalocean.com/community/tutorials/http-1-1-vs-http-2-what-s-the-difference) - here you can find information about major changes between **HTTP** and **HTTP/2**; **(EN)**

## WebSocket

WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. 

WebSocket is distinct from HTTP. Both protocols are located at layer 7 in the OSI model and depend on TCP at layer 4. Although they are different, RFC 6455 states that WebSocket "is designed to work over HTTP ports 80 and 443 as well as to support HTTP proxies and intermediaries," thus making it compatible with the HTTP protocol. To achieve compatibility, the WebSocket handshake uses the HTTP Upgrade header to change from the HTTP protocol to the WebSocket protocol.

The WebSocket protocol enables interaction between a web browser (or other client application) and a web server with lower overhead than half-duplex alternatives such as HTTP polling, facilitating real-time data transfer from and to the server. This is made possible by providing a standardized way for the server to send content to the client without being first requested by the client, and allowing messages to be passed back and forth while keeping the connection open. In this way, a two-way ongoing conversation can take place between the client and the server. The communications are done over TCP port number 80 (or 443 in the case of TLS-encrypted connections), which is of benefit for those environments which block non-web Internet connections using a firewall. Similar two-way browser-server communications have been achieved in non-standardized ways using stopgap technologies such as Comet.

You should focus on such themes:
* **WebSocket** overview;
* **HTTP** vs WebSocket differences;
* **HTTP/2** vs WebSocket differences;
* When to use WebSocket instead of **HTTP** (**HTTP/2**);

### Links to internet resources

* [How Do Websockets Work?](https://sookocheff.com/post/networking/how-do-websockets-work/) - here you can find basic information of **WebSocket** protocol; **(EN)**;
* [When to use a HTTP call instead of a WebSocket](https://blogs.windows.com/windowsdeveloper/2016/03/14/when-to-use-a-http-call-instead-of-a-websocket-or-http-2-0/) - here you can find information about when to use **WebSocket** and **HTTP** (**HTTP/2**); **(EN)**;

## TLS

You should focus on such themes:
* **SSL** overview;
* **TLS** overview;
* **SSL** vs **TLS** differences;

### Links to internet resources

* [What is Transport Layer Security (TLS)?](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/) - here you can find basic information of **Transport Layer Security (TLS)** protocol; **(EN)**;
* [What is Secure Sockets Layer (SSL)?](https://www.cloudflare.com/learning/ssl/what-is-ssl/) - here you can find basic information about  **Secure Sockets Layer (SSL)** protocol; **(EN)**;
* [SSL vs. TLS - What's the Difference?](https://www.globalsign.com/en/blog/ssl-vs-tls-difference/) - here you can find basic information about main differences between **SSL** and **TLS** protocols; **(EN)**;