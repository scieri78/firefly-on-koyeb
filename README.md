# Firefly III on Koyeb

Docker Compose per deploy rapido di Firefly III con MariaDB e cron.

## Servizi
- `app`: Firefly III
- `db`: MariaDB
- `cron`: esegue lo scheduler ogni giorno alle 03:00

## Deploy su Koyeb
1. Crea un nuovo repository su GitHub
2. Aggiungi i file `docker-compose.yml` e `.env` (o inserisci le variabili su Koyeb)
3. Crea un nuovo **service** su [Koyeb](https://app.koyeb.com)
