## Mermaid Practice File

I can use mermain on github now, this markdown is practice.

[Mermaid Docs](https://mermaid-js.github.io/mermaid/#/)

### Flowchart LR

```mermaid
flowchart LR;
 Lucky[Lucky]
 Alex(Alex)
 Lucky-- Mother Of -->Alex
```

```
flowchart LR;
 Lucky[Lucky]
 Alex(Alex)
 Lucky-- Mother Of -->Alex
```

### Erdiagram

```mermaid
erDiagram
  OWNERS {
  int id
  string name
  int age
  }
  DOGS {
  int id
  string name
  int age
  int owner_id
  }
  OWNERS ||--|{ DOGS : owns
```
