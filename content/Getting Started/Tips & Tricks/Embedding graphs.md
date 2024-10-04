Graphs can be embedded into a page using a code block and entering the syntax to create a mermaid diagram as demonstrated below.

```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```

Further if you would like to create a graph that contains clickable links, they can be included by using the keyword "internal-link." Below is an example using the first three pages from the Getting Started guide.

```mermaid
graph TD

A[1. Welcome]
B[2. Creating a Github account]
C[3. Install Git]

A --> B --> C

class A,B,C internal-link
```

Syntax reference: https://mermaid.js.org/intro/syntax-reference.html

#tips