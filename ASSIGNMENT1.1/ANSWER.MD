Name : Onashe Shaun Tsambatare
Section: I
Department : B.Tech Civil Engineering
Student ID : BEE2026024

# Assignment 1.1 — How a Website Works

## 1\. Understand the Basic Roles of Browser, Client, Server, and Database

- **Browser:** A browser such as Google Chrome is software used to access and display websites.
- **Client:** The client is the user's device or application, such as a laptop running Chrome, that sends requests to a server.
- **Server:** A server is a computer or software that receives requests, processes them, and sends responses to the client.
- **Database:** A database stores and organizes information, such as user details, product information, and website content. The server communicates with the database when information is required.

## 2\. Write the Meanings of HTTP and HTTPS

- **HTTP:** Hypertext Transfer Protocol. It is a protocol used for communication between a browser and a web server. HTTP does not encrypt the data exchanged.
- **HTTPS:** Hypertext Transfer Protocol Secure. It is the secure version of HTTP that uses encryption through TLS to protect data exchanged between the browser and the server.

**Difference:** HTTP is not encrypted by default, whereas HTTPS protects data during transmission and helps verify the website's identity.

## 3\. Explain the Request-Response Cycle

The request-response cycle is the process through which a browser communicates with a web server. When a user enters a URL, the browser identifies the server's IP address using DNS (Domain Name System). The browser then sends an HTTP or HTTPS request to the server. The server processes the request and may retrieve information from a database. After processing, the server sends an HTTP response containing the requested content or an error message. Finally, the browser processes the response and displays the website on the screen.

**Steps in the request-response cycle:**

1. The user enters a URL in the browser.
2. The browser finds the server's IP address using DNS.
3. The browser sends an HTTP or HTTPS request.
4. The server processes the request and may access a database.
5. The server sends a response to the browser.
6. The browser loads the resources and displays the website.

## 4\. Write the Differences Between a Static and a Dynamic Website

| Static Website | Dynamic Website |
| --- | --- |
| Displays fixed content. | Content can change based on user input or other conditions. |
| Usually uses HTML and CSS, with optional JavaScript. | Often uses JavaScript and may use server-side programming and databases. |
| Usually delivers pre-created files to the browser. | May generate content when a request is received. |
| Generally simpler to develop and host. | Often requires more complex development and processing. |
| Example: A simple personal portfolio page. | Example: An online shopping website with personalized products. |

## 5\. Open Chrome DevTools and Inspect Requests in the Network Tab
![alt text](<ASSIGNMENT1.1 IMAGE.png>)
