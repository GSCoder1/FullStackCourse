# Part0 exercises
### Exercise 0.4: Mermaid Diagram for creating new note on regular browser
```mermaid
graph TD
    A[Create new note] --> B[Post new_note]
    B --> C[Get notes]
    C --> D[Get main.css]
    D --> E[Get main.js]
    E --> F[Get data.json]
```
### Exercise 0.5: Mermaid Diagram for using single page app
```mermaid
graph TD
    A[spa document] --> B[main.css]
    B --> C[spa.js]
    C --> D[data.json]
```
### Exercise 0.6: Mermaid Diagram for creating new note on single page app
```mermaid
graph TD
    A[Create new note] --> B[Post new_note_spa]
```
