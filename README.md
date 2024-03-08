# FastApi Todos mit MySQL-Datenbank

### Ziel: Die Applikation in einem DevContainer weiterentwickelt werden
- api  (das ist die API, die etwickelt wird)
- db (MySQL Datenbank)
- dbtool (phpmyadmin Tool zur Verwaltung der Datenbank)
- Es besteht schon ein docker-compose.yml File und ein Dockerfile für die api aus denen zusätzliche Informationen gewonnen werden können.

#### Startbefehl der API:
uvicorn main:app --host 0.0.0.0 --reload

