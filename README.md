# MSA-GoFuture


GoFuture переходит к глобальной платформе: микросервисной и событийной архитектуре с
контурами обработки данных и машинного обучения (ML), бизнес-аналитикой (BI) и
поддержкой нескольких арендаторов. Ниже собраны основные результаты для проверки.

- **Task 1 — целевая архитектура.** Зафиксированы НФТ, C2 To-Be, порядок
  декомпозиции и план миграции: [ADR-01](Task1/ADR-01.md) и
  [C2 To-Be](Task1/diagrams/c2-to-be.puml).
- **Task 2 — событийная платформа.** Описаны C2, мониторинг, инструменты и
  метрики: [ADR-02](Task2/ADR-02.md) и
  [C2 event platform](Task2/diagrams/c2-event-platform.puml).
- **Task 3 — глобальное развертывание.** Выбраны регионы, схемы репликации,
  геомаршрутизация и аварийное переключение; описаны сценарии отказа и требования
  законодательства: [ADR-03](Task3/ADR-03.md), [global deployment C2](Task3/diagrams/global-deployment-c2.puml),
  [replication](Task3/diagrams/replication.puml), [geo-routing](Task3/diagrams/geo-routing.puml),
  [failover C4](Task3/diagrams/failover-c4.puml).
- **Task 4 — данные, ML и BI.** Спроектированы конвейер обработки данных (C4) и контроль
  качества данных: [ADR-04](Task4/ADR-04.md) и
  [C4 data/ML/BI](Task4/diagrams/c4-data-ml-bi.puml). Контроль качества описан в ADR-04;
  отдельная диаграмма для него не поставляется.
- **Task 5 — мультитенантность.** Определены C2 платформы, IAM, мониторинг,
  подключение арендаторов, роли и права доступа: [ADR-05](Task5/ADR-05.md),
  [C2 multitenant IAM](Task5/diagrams/c2-multitenant-iam.puml),
  [onboarding flow](Task5/diagrams/onboarding-flow.puml) и
  [roles and access](Task5/roles-access.md).

