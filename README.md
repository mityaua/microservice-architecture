## 1. Monolith vs. Microservices
- Архітектура та нефункціональні вимоги
- Модульний та розподілений моноліти
- Сервісно-орієнтована архітектура (SOA)
- Мікросервіси: переваги,недоліки, порівняння з монолітом
- Наносервіси

## 2. Microservice modeling
- Метрики об’єктно-орієнтованого дизайну (cohesion, coupling)
- Вступ до доменно-орієнтованого дизайну (DDD)
- Агрегати, обмеження контексту (Bounded contexts)
- DDD для проєктування мікросервісів
- Використання спільних бібліотек
- C4 діаграми
- Практика

## 3. Decomposition strategies
- Принципи декомпозиції мікросервісів
- Пошарова декомпозиція
- Декомпозиція за потребами бізнесу
- Декомпозиція за DDD
- Декомпозиція та організаційна структура
- Патерни декомпозиції (ACL, strangler application, feature flag)
- Проблеми з розподіленням даних

## 4. Microservices communication p. 1
- Використання спільних даних (Common data)
- Синхронна та асинхронна моделі комунікації
- Модель request / response
- Виклик віддалених процедур та використання gRPC
- REST та GraphQL
- Діаграми послідовностей (Sequence diagram)

## 5. Microservices communication p. 2
- Подійно-орієнтована комунікація (event-driven)
- Брокери повідомлень (push та pull моделі, Apache Kafka, RabbitMQ)
- Серіалізація
- Реєстр сервісів
- Зворотно несумісні зміни

## 6. Transactions management
- ACID
- Двофазний коміт (2PC)
- Локи (Locks)
- Sagas
- Відстежування зміни даних (CDC)

## 7. Microservices patterns
- Монолітний фронтенд, мікрофронтенди та page based декомпозиція
- BFF
- CQRS
- Sidecar
- Aggregator
- Chained microservices
- Proxy

## 8. API Gateway and Testing
- Service meshes
- API Gateway
- Gateway маршрутизація
- Сервісні тести
- Тести e2e та flakiness
- Тести контрактів

## 9. Resilience
- Проблеми мережевої комунікації
- Модель BASE та CAP теорема (AP vs CP)
- Таймаути та повторні спроби
- Патерн Circuit breaker
- Патерн Bulkhead
- Надлишковість

## 10. Deployment
- Інфраструктура як код (IaC)
- Фізичні та віртуальні сервери
- Kubernetes та Docker Swarm
- Serverless
- Continuous integration
- Blue/green deployment та Progressive delivery (Canary)

## 11. Scaling
- Осі масштабування
- Автоматичне масштабування
- Serverless scaling
- Стратегії кешування

## 12. Monitoring and Observability
- Агрегування логів
- Розподілення трасування
- Метрики
- Alerting та Anomaly detection
- SLA та SLO
- Метрики інцидентів (MTBF, MTTR, MTTF, MTTA)

## 13. Authentication and Security
- Базові принципи та OWASP
- Шифрування at rest / in transit
- Міжсервісна аутентифікація
- SSO
- JWT

## 14. Organizational structure
- Закон Конвея
- Agile та архітектура
- Моделі відповідальності
- Платформа
