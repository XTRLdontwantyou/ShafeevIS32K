```mermaid
flowchart TD
    subgraph React Application
        direction TB
        Start --> Authorization
        Authorization --> Routing
        Routing -->|Задача 1| Task1
        Routing -->|Задача 2| Task2
        Routing -->|Задача 3| Task3
    end
