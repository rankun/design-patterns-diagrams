```mermaid
classDiagram
    class LazyInit {
        -instance: LazyInit
        -LazyInit()
        +getInstance(): LazyInit
    }
    LazyInit --|> LazyInit: instance
```
