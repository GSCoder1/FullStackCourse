# Part0 exercises
### Exercise 0.4: Mermaid Diagram for creating new note
```mermaid
  graph TD;
      Create new note-->Post: new_note;
      Post: new_note-->Get: notes;
      Get: notes-->Get main.css;
      Get main.css-->Get main.js;
      Get main.js-->data.json;
```
