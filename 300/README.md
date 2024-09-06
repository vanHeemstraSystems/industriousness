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
    participant Communications
    participant Channels
    participant Planning
    participant Workspaces
    Industriousness->>Communications: Open Communications
    Communications->>Channels: Monitor "Industriousness" Channel
    Channels->>Channels: Interact
    Industriousness->>Planning: Open Planning
    Planning->>Workspaces: Monitor "Industriousness" Workspace
    Workspaces->>Workspaces: Interact
    Workspaces->>Planning: Ready
    Planning->>Industriousness: Ready also
    Channels->>Communications: Ready
    Communications->>Industriousness: Ready also
    Industriousness->>Communications: Do something else
    Communications->>Communications: Repeat
```

## 300 - How

### 100 - Open Communications

See [README.md](./300/100/README.md)

### 200 - Monitor "Industriousness" Channel

See [README.md](./300/200/README.md)

### 300 - Open Planning

See [README.md](./300/300/README.md)

### 400 - Monitor "Industriousness" Workspace

MORE
