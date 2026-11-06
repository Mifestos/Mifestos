**Data Engineer | Python-разработчик | Data Scientist / ML Engineer**

23 года. Выпускник **НГТУ им. Р.Е. Алексеева** по специальности **«Прикладная математика и информатика»**. Специализируюсь на разработке решений в области машинного обучения и инженерии данных. Обладаю прочной математической базой и практическим опытом применения алгоритмов для решения прикладных задач.

---




| Тема проекта / Год | Название проекта | Описание | Стек и методы |
|---|---|---|---|
| Data Engineering / 2026 | [tinvest-flow](https://github.com/Mifestos/tinvest-flow) | Гибридная Data Platform (Lambda) для обработки биржевых данных T-Invest API в real-time и пакетно. Построены сквозные пайплайны по паттерну Medallion Architecture (MinIO S3 -> PostgreSQL -> ClickHouse). Реализован JDBC UPSERT для Spark Streaming (через Staging), Dead Letter Queue (DLQ) и Data Quality-гейты (Great Expectations). Внедрены автоматические миграции схемы БД (Alembic + SQL-runner). Настроен Observability-стек (Prometheus, Grafana, метрики Airflow через StatsD), BI-визуализация (Metabase) и Production-grade CI/CD. | Python, Apache Airflow, Apache Spark (Batch & Streaming), Apache Kafka, PostgreSQL (партиционирование), ClickHouse, MinIO (S3), Alembic, Great Expectations, Prometheus, Grafana, Metabase, Docker, GitHub Actions, Pydantic, Pytest, Mypy (strict), Ruff |
| Full-stack ML / 2026 | [CineRec](https://github.com/Mifestos/CineRec) | Рекомендательная система (Two-Stage: ALS + LTR). REST API (FastAPI), UI (Next.js), Nginx, PostgreSQL, Redis. NLP (RuBERT) для анализа отзывов. Оценка качества (NDCG), CI/CD. | Python, FastAPI, Next.js, TypeScript, PostgreSQL, Redis, ALS, LightGBM, PyTorch, RuBERT, Docker, Nginx |
| Кредитный скоринг / 2026 | [AlfaBattle2.0](https://github.com/Mifestos/AlfaBattle2.0) | Предсказание дефолта клиента | Python, Pandas, PyArrow, LightGBM, Scikit-learn, Jupyter Notebook |
| Машинное обучение / 2026 | [ML_Seminars](https://github.com/Mifestos/ML_Seminars) | Практические задания по курсу ML (семинары Воронцова) | ML Base |
| LLM & AI-агенты / 2026 | [GigaChatAgent](https://github.com/Mifestos/GigaChatAgent) | AI-агент для анализа данных. Безопасный код (E2B), самокоррекция (LangGraph), лимиты токенов, оценка качества (Pass@1). | Python, LangGraph, GigaChat API, E2B Sandbox, Pandas, Typer, Rich |
| Data Engineering / 2026 | [PetEarthquake](https://github.com/Mifestos/PetEarthquake) | Сквозной ETL/ELT-пайплайн: REST API → S3 (Raw) → PostgreSQL (ODS) → витрины → Metabase (BI). Оркестрация в Airflow, развёртывание в Docker Compose. | Python, Apache Airflow, PostgreSQL, S3/MinIO, Metabase, Docker, Docker Compose |