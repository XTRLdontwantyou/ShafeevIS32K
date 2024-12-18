# SigmaShop это онлайн магазин где можно купить донатную валюту в игре Fortnite намного дешевле чем в самой игре , каждая купленная единица валюта делает вас на 0.1 % круче. Наш магазин имеет хорошую репутацию и известен многим людям. Наш магазин лицензирован и абсолютно легален
# Вот как выглядит форма авторизаций
```mermaid
sequenceDiagram
    participant User
    participant Shop
    participant Server
    User->>Shop: Отправка запроса на авторизацию
    Shop->>Server: Запрос на авторизацию
    Server-->>Shop: Ответ
    Shop->>User: Отображение успешного входа
    Shop->>Server: Запрос 
    Server-->>Shop: Ответ запроса
    Shop->>User: Отображение запроса
```
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
