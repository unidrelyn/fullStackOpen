# Exercise 0.5

sequenceDiagram

browser->>+server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa <br>
browser->>+server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css <br>
browser->>+server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js <br>
server-->>-browser: HTML-code <br>
server-->>-browser: main.css <br>
server-->>-browser: main.js <br>

![Diagram](0_5.png)
