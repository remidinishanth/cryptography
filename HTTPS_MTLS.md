The **Hypertext Transfer Protocol (HTTP)** is the basic communication protocol that both clients and servers must implement in order to be able to communicate. It covers things such as requests and responses, sessions, caching, authentication and more. 

The protocol transfers information between the browser and the server in clear text, allowing the network, through which the information passes, to see the information transmitted. This is a security concern, so **HTTP Secure (HTTPS)** was introduced, allowing the client and the server to first establish an encrypted communication channel, and then pass the clear text HTTP messages through it, effectively protecting them from eavesdropping.

Browser to Youtube.com

![image](https://user-images.githubusercontent.com/19663316/116873789-e038e000-ac35-11eb-84f0-7ffea094363c.png)

How Youtube.com creates his cert and how it is signed by Google CA. Every computer maintains a list of certificates which it trusts and are known to be legitimate.

![image](https://user-images.githubusercontent.com/19663316/116874052-49205800-ac36-11eb-8938-3147947d097a.png)

Managing our own CA

![image](https://user-images.githubusercontent.com/19663316/116874430-f1362100-ac36-11eb-8d98-46fab9eb6fae.png)
