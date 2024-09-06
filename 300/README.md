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
    participant Planner
    Industriousness->>Communications: Open communications
    Communications->>Channels: Monitor "Industriousness" channel
    Channels->>Channels: Interact
    Industriousness->>Planner: Open planner
    Channels->>Communications: Ready
    Communications->>Industriousness: Ready also
    Industriousness->>Communications: Do something else
    Communications->>Communications: Repeat
```

## 300 - How

### 100 - Open Communications

See [README.md](./300/100/README.md)

### 200 - Monitor "Industriousness" channel

See [README.md](./300/200/README.md)

### 300 - Open Planner

See [README.md](./300/300/README.md)

MORE
