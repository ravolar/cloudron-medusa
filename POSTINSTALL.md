Настройки магазина — `/app/data/env.sh` (File Manager), секреты `JWT_SECRET` и `COOKIE_SECRET` — `/app/data/.secrets/secrets.env`
(Web Terminal). Без ключей обязательных функций (Stripe live, Omniva, письма SMTP, R2) Medusa не стартует и пишет в журнал,
каких переменных нет. Порядок — README пакета `app/deploy/cloudron/` в репозитории проекта.
