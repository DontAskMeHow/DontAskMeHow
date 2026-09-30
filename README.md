# Привет, я Александр

Руководитель разработки с инженерной базой: строю инфраструктуру, инструменты и агентные
системы. Руководил разработкой платформы управления сетью устройств (промышленный IoT):
собрал команду с нуля, построил практики QA, CI/CD и DevOps, выполнял функции CTO.

С 2024 года плотно в LLM: локальные модели и инференс-серверы (vLLM на паре DGX Spark),
агентные системы с долговременной памятью, MCP-инструменты. Настраивал и эксплуатировал
модели YOLO (Ultralytics) для распознавания людей по камерам.

## Что я делаю

### AI/LLM и агенты

- [agent-memory-search](https://github.com/DontAskMeHow/agent-memory-search) — гибридный
  поиск для баз знаний ИИ-агентов: BM25 + векторы BGE-M3 + RRF + реранкинг; CLI и MCP
- [llm-infra-benchmarks](https://github.com/DontAskMeHow/llm-infra-benchmarks) — бенчмарки
  LLM-инференса на 2× DGX Spark (vLLM): контекст 512K, карта NIAH, QA-батареи,
  спекулятивный декодинг
- [chrome-cdp-client](https://github.com/DontAskMeHow/chrome-cdp-client) — управление
  Chrome из Python поверх CDP: WebSocket-клиент без Selenium, копии профилей с сессиями
- [agent-automation](https://github.com/DontAskMeHow/agent-automation) — автоматизация
  воркспейса ИИ-агента: демон периодических задач, каталог проблем, health-чеки
- [telegram-acp-bridge](https://github.com/DontAskMeHow/telegram-acp-bridge) — управление
  ИИ-агентом кодинга с телефона через Telegram

### Инфраструктура и CI/CD

- [infra-compose-stacks](https://github.com/DontAskMeHow/infra-compose-stacks) — Docker
  Compose-стеки: GitLab CE, Rancher, ELK, Semaphore, VictoriaMetrics, Postgres
- [ci-cd-demo](https://github.com/DontAskMeHow/ci-cd-demo) — полный цикл CI/CD на GitLab CI:
  сборка → тесты → реестр → Ansible-деплой → релиз
- [demo-app-helm](https://github.com/DontAskMeHow/demo-app-helm) — Helm-чарты для k3s
- [demo-app-ci](https://github.com/DontAskMeHow/demo-app-ci) — конвейер GitLab CI для k3s
  через GitLab Kubernetes Agent
- [planfix-exporter](https://github.com/DontAskMeHow/planfix-exporter) — экспортёр метрик
  задач Planfix в VictoriaMetrics
- [k6-load-tests](https://github.com/DontAskMeHow/k6-load-tests) — фреймворк нагрузочного
  тестирования k6: 4 сценария, ~200 метрик, time compression, VictoriaMetrics + Grafana

### Инструменты

- [cmos](https://github.com/DontAskMeHow/cmos) — сканер QR/Data Matrix с веб-камеры на OpenCV
- [git_loader](https://github.com/DontAskMeHow/git_loader) — синхронизация локальной
  коллекции Git-репозиториев

## Стек

Python · TypeScript · C# / C (embedded) · Kubernetes (k3s/Rancher) · Docker · GitLab CI ·
Ansible · Prometheus / Grafana / VictoriaMetrics · ELK · PostgreSQL · NATS / MQTT ·
vLLM / LLM-serving

## Роли

Team Lead / Head of Development · DevOps · QA Automation · MLOps / LLM-инфраструктура