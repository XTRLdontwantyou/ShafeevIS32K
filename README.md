SigmaShop – это современный и надежный интернет-магазин, предлагающий широкий ассортимент виртуальных валют для различных нужд. Мы стремимся предоставить нашим клиентам удобные и безопасные способы приобретения цифровых активов, обеспечивая максимально комфортное пользовательское опыт.

Основные преимущества SigmaShop:
Широкий выбор: Наш магазин предлагает различные виды виртуальной валюты, включая Bitcoin, Ethereum, Litecoin и другие популярные криптовалюты.
Безопасность: Мы используем передовые технологии защиты данных и обеспечиваем высокий уровень безопасности всех транзакций.
Удобство использования: Простой и интуитивно понятный интерфейс позволяет легко находить нужную валюту и совершать покупку всего за несколько кликов.
Поддержка клиентов: Наша команда специалистов всегда готова помочь вам с любыми вопросами, связанными с покупкой и использованием виртуальной валюты.
Гибкие методы оплаты: Мы принимаем различные способы оплаты, чтобы обеспечить максимальную доступность наших услуг для каждого клиента.

Как работает покупка?
Регистрация: Создайте учетную запись на нашем сайте, заполнив простую форму регистрации.
Выбор валюты: Выберите интересующую вас виртуальную валюту из нашего каталога.
Оплата: Оплатите выбранную валюту удобным для вас способом.
Получение: После подтверждения оплаты ваша виртуальная валюта будет зачислена на ваш кошелек.


```mermaid
sequenceDiagram
  participant Пользователь
  participant Веб-приложение
  participant Сервис аутентификации
  participant Платежный шлюз
  participant Сервис кошельков

  Пользователь->>Веб-приложение: Открыть страницу входа
  Веб-приложение->>Сервис аутентификации: Запросить токен аутентификации
  Сервис аутентификации->>Веб-приложение: Вернуть токен
  Веб-приложение->>Пользователь: Отобразить форму входа

  Пользователь->>Веб-приложение: Ввести логин/пароль
  Веб-приложение->>Сервис аутентификации: Отправить данные для проверки
  alt Проверка успешна
      Сервис аутентификации->>Веб-приложение: Проверка успешна
      Веб-приложение->>Пользователь: Перенаправление на главную страницу
  else Проверка не успешна
      Сервис аутентификации->>Веб-приложение: Проверка не успешна
      Веб-приложение->>Пользователь: Сообщение об ошибке
  end

  Пользователь->>Веб-приложение: Выбрать товар (виртуальную валюту)
  Веб-приложение->>Платежный шлюз: Инициировать платеж
  Платежный шлюз->>Пользователь: Перенаправление на страницу оплаты
  Пользователь->>Платежный шлюз: Ввод данных карты
  Платежный шлюз->>Пользователь: Подтверждение платежа

  Платежный шлюз->>Сервис кошельков: Уведомление о платеже
  Сервис кошельков->>Веб-приложение: Обновить баланс пользователя
  Веб-приложение->>Пользователь: Отобразить обновленный баланс
   ```


На диаграмме показана выручка с момента открытия до конца 2023 год

```mermaid
xychart-beta
    title "Выручка SigmaShop за 2023 год"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis " (in $)" 0 --> 11000
    bar [000, 6000, 7500, 8200, 9800, 1050, 0, 1220, 12000, 11500, 3500, 6000]
    line [000, 6000, 7500, 8200, 9500, 1050, 0, 1220,1200, 11500, 3500, 6000]
```


вот диаграмма компонентов из чего наши повара делают пиццы

```mermaid
mindmap
  root((trollpizza))
    Origins
      bacon
      human meat
       papaya
        pineapples
          
    cobblestone
      fish
```
