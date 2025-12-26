# web_cognitive_hse

Web-платформа для когнитивных исследований:
- participant web
- researcher web
- backend API
- ML runtime (browser inference)

- apps/
- participant-web/ # интерфейс участника (задачи, ответы, RT)
- researcher-web/ # интерфейс исследователя (протоколы, QC, результаты)
- api/ # backend (сессии, события, экспорт)

- ml/
- runtime/ # ML-инференс в браузере (gaze, blinks, emotions)
- training/ # обучение и экспорт моделей (опционально)
- tests/ # тесты ML

- packages/
- shared/ # общие типы и форматы событий
- ui/ # общий UI-kit (если нужен)

- db/
- migrations/ # SQL миграции
- seed/ # тестовые данные

- docker/ # локальный запуск через docker-compose
- docs/ # краткая документация
- scripts/ # dev-скрипты
