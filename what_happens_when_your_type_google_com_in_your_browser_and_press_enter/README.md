# What Happens When You Type `google.com` in Your Browser and Press Enter?

## General

This project is a classic interview question used for many software engineering positions. It tests your general understanding of how the web stack works on top of the internet. Depending on the specific role, interviewers may ask you to focus on particular aspects of the workflow, such as the rendering of the DOM for a front-end role or the load balancing mechanism for an SRE role.

Understanding the process that takes place when you type a URL like `https://www.google.com` and press Enter is crucial, especially for demonstrating your grasp of DNS—a common area where candidates struggle. A solid explanation of this concept can set you apart from other candidates. Moreover, writing an excellent article on this topic can help attract the attention of potential employers.

## Tasks

### 0. What Happens When...

Write a blog post explaining what happens when you type `https://www.google.com` in your browser and press Enter.

Your post must cover:

- **DNS Request**: How the browser resolves the domain name to an IP address.
- **TCP/IP**: Establishing a connection with the server using the TCP/IP protocol.
- **Firewall**: The role of firewalls in managing and securing network traffic.
- **HTTPS/SSL**: The process of encrypting data using SSL/TLS.
- **Load-Balancer**: How load balancers distribute the traffic to different servers.
- **Web Server**: The web server's role in handling the HTTP request.
- **Application Server**: How the application server processes the request.
- **Database**: Fetching the necessary data from the database to serve the request.

#### Publish Your Blog Post

Publish your blog post on a platform such as Medium or LinkedIn. Share the URL of your blog post in your answer file and in the field below.

- **Repo**:
  - GitHub repository: `holbertonschool-network`
  - Directory: `what_happens_when_your_type_google_com_in_your_browser_and_press_enter`
  - File: `0-blog_post`

### 1. Everything's Better with a Pretty Diagram

Add a schema to your blog post illustrating the flow of the request created when you type `https://www.google.com` in your browser and press Enter.

Your diagram should show:

- **DNS Resolution**: The process of resolving the domain name to an IP address.
- **Request Hitting Server IP on the Appropriate Port**: The request reaching the server via the correct port.
- **Encrypted Traffic**: The traffic being encrypted through SSL/TLS.
- **Firewall**: The role of the firewall in filtering traffic.
- **Load Balancer**: Distributing the request to different servers.
- **Web Server**: Handling the HTTP request and serving a web page.
- **Application Server**: Generating the web page.
- **Database**: Requesting data from the database.

#### Requirements

- **Repo**:
  - GitHub repository: `holbertonschool-network`
  - Directory: `what_happens_when_your_type_google_com_in_your_browser_and_press_enter`
  - File: `1-what_happen_when_diagram`

## Conclusion

By completing this project, you will gain a deeper understanding of the web stack and how the internet works, enhancing your technical knowledge and preparing you for software engineering interviews. Remember to take your time and write a thorough and clear explanation!

Happy blogging!
