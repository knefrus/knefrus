<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img src="banner-light.svg" alt="Никита Кубарев — ML Engineer">
</picture>

Занимаюсь прикладным ML: веду полный пайплайн, объясняю результаты.

Москва · [Telegram @mrknef](https://t.me/mrknef)

---

## Проекты

### Прогнозирование отказов серверов

Прогноз отказа веб-сервиса примерно за 100 секунд. Реальные данные, проверка по времени и на незнакомой машине. В одинаковом режиме мониторинга модель дала 4 полезные тревоги из 5, порог по одной метрике — 0 из 12. Recall 13 %, ограничения описаны в README.

`Prometheus` `CatBoost` `SHAP` `aiogram` `systemd`

### Прогрессия после гамма-ножа

Прогноз повторного роста метастазов после радиохирургии. Клинические данные НМИЦ им. Бурденко, 583 пациента, работа в команде научной студии. **PR-AUC 0.899** при базовом уровне 0.657. Нашел и устранил утечку при подборе порога, проверил результат вложенной кросс-валидацией.

`CatBoost` `LightGBM` `XGBoost` `Optuna` `SHAP`

### PRIME

Проект под заказчика — Telegram мини-приложение и бот для клуба мероприятий: регистрация, профили, механики для участников, админка.

`FastAPI` `aiogram 3` `SQLAlchemy async` `PostgreSQL`

### Своя сетевая инфраструктура

VPS под полным управлением: ноды, бот, веб-панель, мониторинг. Администрирование, домены, поддержка пользователей.

`Linux` `systemd` `Docker` `Nginx` `Prometheus`

---

## Навыки

| Область | Инструменты |
|---|---|
| **ML** | CatBoost, LightGBM, XGBoost, scikit-learn, Optuna, SHAP |
| **Методы и данные** | feature engineering, вложенная кросс-валидация, дисбаланс классов, pandas, NumPy, Matplotlib |
| **Backend и БД** | Python, FastAPI, aiogram 3, SQLAlchemy async, PostgreSQL, MongoDB, Redis |
| **Инфраструктура** | Linux, Bash, Docker, Git, Nginx, systemd, Prometheus |
| **Языки** | Python, SQL, Bash · English B1 |

---

## Еще

Двукратный чемпион России в соревнованиях «Профессионалы»  
Играю в большой теннис 13 лет  
Arch Linux как вторая система, сторонник
