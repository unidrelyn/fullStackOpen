# Exercise 0.4
sequenceDiagram

browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note <br>
server-->browser: HTTP 302 <br>
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes <br>
server-->browser: HTML Code <br>
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css <br>
server-->browser: main.css <br>
browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js <br>
server-->browser: main.js <br>


![Diagram](0_4.png)
