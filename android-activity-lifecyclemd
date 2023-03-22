```mermaid
graph TB
    A[onCreate] --> B[onStart]
    B --> C[onResume]
    C --> D[onPause]
    D --> E[onStop]
    E --> F[onDestroy]
    D --> C
    E --> B
    F --> A
    subgraph Activity Lifecycle
        A --> B --> C --> D --> E --> F
    end
```
