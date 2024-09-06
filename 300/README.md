# 300 - Managing Our Activity

## 100 - When

```mermaid
flowchart LR
  A[Actor] --> B(When: Monday)
  A[Actor] --> C(When: Tuesday)
  A[Actor] --> D(When: Wednesday)
  A[Actor] --> E(When: Thursday)
  A[Actor] --> F(When: Friday)
  B --> G{Abstract UC: Industriousness}
  C --> G{Abstract UC: Industriousness}
  D --> G{Abstract UC: Industriousness}
  E --> G{Abstract UC: Industriousness}
  F --> G{Abstract UC: Industriousness}
```

## 200 - What

```mermaid
sequenceDiagram
    participant Industriousness
    participant Planner
    participant viewscreen
    Industriousness->>Planner: loads html w/ iframe url
    Planner->>viewscreen: request template
    viewscreen->>Planner: html & javascript
    Planner->>Industriousness: iframe ready
    Industriousness->>Planner: set mermaid data on iframe
    Planner->>Planner: render mermaid
```
