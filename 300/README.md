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
    participant Communication
    participant Channels
    participant Planning
    participant Workspaces
    Industriousness->>Communication: Open Communication
    Communication->>Channels: Monitor "Industriousness" Channel
    Channels->>Channels: Interact
    Industriousness->>Planning: Open Planning
    Planning->>Workspaces: Monitor "Industriousness" Workspace
    Workspaces->>Workspaces: Interact
    Workspaces->>Planning: Ready
    Planning->>Industriousness: Ready also
    Channels->>Communication: Ready
    Communication->>Industriousness: Ready also
    Industriousness->>Communication: Do something else
    Communication->>Communication: Repeat
```

## 300 - How

### 100 - Open Communication

See [README.md](./300/100/README.md)

### 200 - Monitor "Industriousness" Channel

See [README.md](./300/200/README.md)

### 300 - Open Planning

See [README.md](./300/300/README.md)

### 400 - Monitor "Industriousness" Workspace

MORE
