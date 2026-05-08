# Fullstack-Helsinki-Part0
Just need to use the read me portion for a code block??

```mermaid
sequenceDiagram
    participant browser
    participant server

browser->>server: POST
https://studies.cs.helsinki.fi/exampleapp/new_note
activate server
server->>browser: HTTP Status Code 302 (URL Redirect)

```
