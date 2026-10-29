**Data Engineer | Python-разработчик | Data Scientist / ML Engineer**

23 года. Выпускник **НГТУ им. Р.Е. Алексеева** по специальности **«Прикладная математика и информатика»**. Специализируюсь на разработке решений в области машинного обучения и инженерии данных. Обладаю прочной математической базой и практическим опытом применения алгоритмов для решения прикладных задач.

---




| Тема проекта / Год | Название проекта | Описание | Стек и методы |
|---|---|---|---|
| Data Engineering / 2026 | [tinvest-flow](https://github.com/Mifestos/tinvest-flow) | Гибридная Data Platform (Lambda/Kappa) для обработки биржевых данных T-Invest API в режиме реального времени и пакетно. Построены сквозные пайплайны с использованием Medallion Architecture (Bronze -> Silver -> Gold). Реализован паттерн JDBC UPSERT для Spark Streaming (через Staging-таблицы) для обеспечения идемпотентности. Настроены Production-grade CI/CD, строгая типизация и оркестрация в Airflow. | Python, Apache Airflow, Apache Kafka, Apache Spark (Batch & Streaming), PostgreSQL, ClickHouse, MinIO (S3), Docker, GitHub Actions, Pydantic, Mypy, Ruff |
| Full-stack ML / 2026 | [CineRec](https://github.com/Mifestos/CineRec) | Рекомендательная система (Two-Stage: ALS + LTR). REST API (FastAPI), UI (Next.js), Nginx, PostgreSQL, Redis. NLP (RuBERT) для анализа отзывов. Оценка качества (NDCG), CI/CD. | Python, FastAPI, Next.js, TypeScript, PostgreSQL, Redis, ALS, LightGBM, PyTorch, RuBERT, Docker, Nginx |
| Кредитный скоринг / 2026 | [AlfaBattle2.0](https://github.com/Mifestos/AlfaBattle2.0) | Предсказание дефолта клиента | Python, Pandas, PyArrow, LightGBM, Scikit-learn, Jupyter Notebook |
| Машинное обучение / 2026 | [ML_Seminars](https://github.com/Mifestos/ML_Seminars) | Практические задания по курсу ML (семинары Воронцова) | ML Base |
| LLM & AI-агенты / 2026 | [GigaChatAgent](https://github.com/Mifestos/GigaChatAgent) | AI-агент для анализа данных. Безопасный код (E2B), самокоррекция (LangGraph), лимиты токенов, оценка качества (Pass@1). | Python, LangGraph, GigaChat API, E2B Sandbox, Pandas, Typer, Rich |
| Data Engineering / 2026 | [PetEarthquake](https://github.com/Mifestos/PetEarthquake) | Сквозной ETL/ELT-пайплайн: REST API → S3 (Raw) → PostgreSQL (ODS) → витрины → Metabase (BI). Оркестрация в Airflow, развёртывание в Docker Compose. | Python, Apache Airflow, PostgreSQL, S3/MinIO, Metabase, Docker, Docker Compose |