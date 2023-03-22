```mermaid
classDiagram
    class Client {
        -target: Target
        +doWork(): void
    }
    class Target {
        +request(): void
    }
    class Adaptee {
        +specificRequest(): void
    }
    class Adapter {
        -adaptee: Adaptee
        +request(): void
    }
    Client -- Target
    Target <|-- Adapter
    Adapter o-- Adaptee
    ```
