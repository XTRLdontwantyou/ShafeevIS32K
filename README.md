```mermaid
sequenceDiagram
    participant User
    participant Client
    participant Server
    User->>Client: Отправка запроса на авторизацию
    Client->>Server: Запрос на авторизацию
    Server-->>Client: Ответ с токеном
    Client->>User: Отображение успешного входа
    User->>Client: Запрос списка задач
    Client->>Server: Запрос списка задач
    Server-->>Client: Ответ со списком задач
    Client->>User: Отображение списка задач
    
#dff;dlasjf,asdmfdas,fmdsafl;kdsfjasdkfsaklmfaslk
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
