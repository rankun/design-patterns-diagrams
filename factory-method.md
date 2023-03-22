```mermaid
classDiagram
    class Creator {
        +factoryMethod(): Product
    }
    class ConcreteCreator {
        +factoryMethod(): ConcreteProduct
    }
    class Product
    class ConcreteProduct
    Creator <|-- ConcreteCreator
    Product <|-- ConcreteProduct
```
