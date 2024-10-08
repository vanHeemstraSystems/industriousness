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
    participant Weekly
    participant Daily
    Industriousness->>Communication: Open Communication
    Communication->>Channels: Monitor "Industriousness" Channel
    Channels->>Channels: Interact
    Industriousness->>Planning: Open Planning
    Planning->>Workspaces: Monitor "Industriousness" Workspace
    Workspaces->>Weekly: Schedule Weekly Calender Events for This Week
    Weekly->>Workspaces: Ready
    Workspaces->>Daily: Manage Daily Calender Events for Today
    Daily->>Stories: Work on User and Job Stories for Today
    Stories->>Stories: Work
    Stories->>Daily: Ready
    Daily->>Workspaces: Ready also
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

See [README.md](./300/400/README.md)

### 500 - Schedule Weekly Calender Events for This Week

See [README.md](./300/500/README.md)

### 600 - Manage Daily Calender Events for Today

See [README.md](./300/600/README.md)

### 700 - Work on User and Job Stories for Today

See [README.md](./300/700/README.md)

MORE
