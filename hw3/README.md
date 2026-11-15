# ДЗ 3 Проектирование API поиска отелей

[Текст работы](report.md). Сравниваются REST с GET, unary gRPC через gRPC-Web и SSE. Итоговый выбор – REST.

| Вариант | Успешный сценарий | Сценарий ошибки |
|---|---|---|
| REST | [PlantUML](diagrams/01_rest_happy.puml) · [PNG](export/01_rest_happy.png) | [PlantUML](diagrams/02_rest_error.puml) · [PNG](export/02_rest_error.png) |
| gRPC | [PlantUML](diagrams/03_grpc_happy.puml) · [PNG](export/03_grpc_happy.png) | [PlantUML](diagrams/04_grpc_error.puml) · [PNG](export/04_grpc_error.png) |
| SSE | [PlantUML](diagrams/05_sse_happy.puml) · [PNG](export/05_sse_happy.png) | [PlantUML](diagrams/06_sse_error.puml) · [PNG](export/06_sse_error.png) |
