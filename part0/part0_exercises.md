# Part0 exercises
### Exercise 0.4: Mermaid Diagram for creating new note on regular browser
```mermaid
graph TD
    A[User submits new note] --> B[POST new_note to server]
    B --> C[Server redirects to notes]
    C --> D[GET notes]
    D --> E[GET main.css]
    E --> F[GET main.js]
    F --> G[GET data.json]
    G --> H[Browser shows updated notes]
```
Page will reload with new data

### Exercise 0.5: Mermaid Diagram for using single page app
```mermaid
graph TD
    A[GET spa document] --> B[GET main.css]
    B --> C[GET spa.js]
    C --> D[GET data.json]
```
 Page will dynamically load new note
 
### Exercise 0.6: Mermaid Diagram for creating new note on single page app
```mermaid
graph TD
    A[User submits new note] --> B[POST new_note_spa to server]
    B --> C[Server confirms submission]
    C --> D[Page is dynamically updated with new note]
```
