# Assignment 1.1 — How a Website Works

## 1. Explanation: How a Website Works

When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser finds the IP address of the website using DNS (Domain Name System). The browser then sends an HTTP or HTTPS request to the web server. The server receives the request, processes it, and may communicate with a database to retrieve or store information. After processing the request, the server sends an HTTP response containing the required data, such as HTML, CSS, JavaScript, and images. The browser receives these files and displays the website on the screen. This process is called the request-response cycle. The browser acts as the client, while the server handles requests and provides responses. HTTP stands for Hypertext Transfer Protocol, which is used to transfer data between a browser and a server. HTTPS stands for Hypertext Transfer Protocol Secure, which encrypts communication to protect data from unauthorized access. A static website displays fixed content that generally remains the same for every visitor, whereas a dynamic website can display different content depending on user input, database information, or other conditions.

## 2. Basic Components of a Website

**Browser:** A software application, such as Google Chrome, used to access and display websites.

**Client:** The device or application that sends requests to a server. For example, a laptop using Chrome acts as a client.

**Server:** A computer or system that receives client requests, processes them, and sends responses.

**Database:** A system used to store, organize, retrieve, and manage data, such as user details and product information.

**HTTP:** Hypertext Transfer Protocol is a communication protocol used to transfer data between a client and a web server.

**HTTPS:** Hypertext Transfer Protocol Secure is the secure version of HTTP. It uses encryption to protect data during transmission.

## 3. Request-Response Cycle

The request-response cycle consists of the following steps:

1. The user enters a URL into the browser.
2. DNS translates the domain name into an IP address.
3. The browser establishes a connection with the web server.
4. The browser sends an HTTP or HTTPS request to the server.
5. The server processes the request and may retrieve information from a database.
6. The server sends an HTTP response containing the requested information.
7. The browser processes the received files and displays the website.

## 4. Difference Between Static and Dynamic Websites

| Static Website                                           | Dynamic Website                                                            |
| -------------------------------------------------------- | -------------------------------------------------------------------------- |
| Displays mostly fixed content.                           | Displays content that can change according to conditions or user input.    |
| Usually uses HTML and CSS, with JavaScript where needed. | May use HTML, CSS, JavaScript, and server-side programming.                |
| Often does not require a database.                       | May use a database to store and retrieve information.                      |
| Usually simpler to develop and host.                     | Often requires more complex development and processing.                    |
| Example: A basic personal information page.              | Example: An online shopping website with personalized product information. |

## 5. Practical: Inspecting Network Requests Using Chrome DevTools

**Objective:** To inspect the network requests made when a website loads.

**Procedure:**

1. Open Google Chrome.
2. Visit a website, such as `https://example.com`.
3. Right-click anywhere on the webpage and select **Inspect**.
4. Open the **Network** tab in Chrome DevTools.
5. Reload the webpage while the Network tab is open.
6. Observe the requests generated when the page loads.
7. Click any request to inspect its details, such as the request URL, method, status code, headers, and response.

**Observation:**

The Network tab displays the resources requested by the browser while loading a website. These may include HTML documents, CSS files, JavaScript files, images, and other resources. The Status column shows whether a request succeeded or encountered an error. For example, a status code of `200` generally indicates a successful request.

**Result:**

I learned how a browser communicates with a web server using HTTP or HTTPS requests and responses. I also learned how to inspect website resources and their status codes using Chrome DevTools.

## 6. Screenshot of the Network Tab

**Attach your screenshot here.**

To capture the screenshot:

1. Open `https://example.com` in Google Chrome.
2. Press `F12` or `Ctrl + Shift + I` to open Chrome DevTools.
3. Select the **Network** tab.
4. Reload the webpage using `Ctrl + R`.
5. Ensure the list of network requests is visible.
6. Take a screenshot using `Windows + Shift + S`.
7. Save the screenshot and insert it into your assignment or submit it as a separate file.

**Suggested screenshot filename:** `Network-Tab-Screenshot.png`
