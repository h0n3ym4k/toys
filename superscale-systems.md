# SuperScaleSystems

```mermaid
    erDiagram;
    super ||--o{ scale : scale;
    scale ||--o{ systems : systems;
    systems ||--o{ super : super;
```

```mermaid
    graph TD;
    super -->|scale| scale;
    scale -->|systems| systems;
    systems -->|super| super;
```
