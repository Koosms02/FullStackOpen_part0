```mermaid

sequenceDiagram
    participant browser
    participant server
    
    browser->>server: POST https://fullstack-exampleapp.herokuapp.com/new_note
    server-->>browser: { "content": "HTML is easy", "date": "2023-1-1" }
    Note right of browser: The browser dynamically updates the DOM with the new note without reloading the page
  
   
```
