# HTTP (Hyper Text Transfer Protocol)
- With the help of these protocol information or data of particular website is exchanged between web server and web browser.
- HTTP is stateless protocol.
- HTTP is client - server protocol.
- Request sent by one entity, the user agent (or proxy)
- Most of the time User Agent is a Web Browser.
- HTTP is stateless but not sessionless
- The use of Cookies allows the use of stateful session
- > Example: Using E-Commerce shopping basket where we need continuos session.

<img src="Images/HTTP.png?raw=true" alt="HTTP">



1. **Client:** 
- The user agent is any tool that acts on the behalf of the user .
- The browser is always the entity that initiating the requests.

2. **Server:**
- A server appears as only a single machine virtually, thet is because it may actually be a collection of servers.

3. **Proxies:**
- Between the web broweser and the server numorous computers and machines ralay the HTTP message those operating at the application layer are generally called proxies.
- Proxies can perform Following Task:
> 1. Caching : Like History, browsing cache...
> 2. Filtering : Like an antivirus scan..
> 3. Load Balancing : To allow multiple server to serve the different request.
> 4. Authentication : To control access to different resources.
> 5. Logging : Allowing the storage of historical information.

## HTTP vs HTTPS
<table>
  <tr>
    <th>HTTP</th>
    <th>HTTPS</th>
  </tr>
  <tr>
    <td>URL begin with http</td>
    <td>URL begin with https</td>
  </tr>
  <tr>
    <td>Insecured</td>
    <td>Secured</td>
  </tr>
  <tr>
    <td>Works at Application Layer</td>
    <td>Works at Transport Layer</td>
  </tr>
  <tr>
    <td>Encryption is Absent</td>
    <td>Encryption is Present</td>
  </tr>
  <tr>
    <td>Does not require any certificate</td>
    <td>It need SSL certificate</td>
  </tr>
  <tr>
    <td>Uses Port 80</td>
    <td>Uses Port 443</td>
  </tr>
</table>

In the next  [Day 18](day18.md) we will see about SSL.

