# Exercise 0.6
sequenceDiagram

browser->>+server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa <br>
browser->>+server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css <br>
browser->>+server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js <br>
server-->>-browser: HTML-code <br>
server-->>-browser: main.css <br>
server-->>-browser: main.js <br>
browser->>+server: https://studies.cs.helsinki.fi/exampleapp/new_note <br>
server-->>-browser: HTTP 302 "new Note"<br>


![Diagram](0_6.png)
