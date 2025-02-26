# WeatherCrew WeatherApp

## Starten der Anwendung

### Fall 1: Repository nicht lokal vorhanden
Falls Sie das Repository noch nicht lokal haben, können Sie es entweder von GitHub klonen oder die `docker-compose.yml` direkt herunterladen:

#### Option A: Repository klonen (mit Git)
1. Stellen Sie sicher, dass Git auf Ihrem System installiert ist
2. Öffnen Sie ein Terminal und führen Sie den folgenden Befehl aus, um das Repository zu klonen:
    ```bash
   git clone https://github.com/WeatherCrew/weather-app.git
   ```
3. Wechseln Sie in das Verzeichnis: cd weather-app
4. Führen Sie folgenden Befehl aus:
   ```bash
    docker compose up
    ```
5. Öffnen Sie einen Browser:
   - UI: `http://localhost:80`
   - API: `http://localhost:8000`

#### Option B: Nur die docker-compose.yml herunterladen
1. Öffnen Sie Ihren Browser und rufen Sie folgende URL auf:
   - `https://github.com/WeatherCrew/weather-app/raw/main/docker-compose.yml`
2. Speichern Sie die Datei lokal als `docker-compose.yml`
3. Öffnen Sie ein Terminal im Verzeichnis, in dem Sie die Datei gespeichert haben
4. Führen Sie folgenden Befehl aus:
   ```bash
    docker compose up
    ```
5. Öffnen Sie einen Browser:
   - UI: `http://localhost:80`
   - API: `http://localhost:8000`

### Fall 2: Repository lokal vorhanden
Falls Sie das Repository bereits lokal auf Ihrem Rechner haben (z. B. als ZIP heruntergeladen oder geklont):
1. Öffnen Sie ein Terminal im Verzeichnis, in dem sich die `docker-compose.yml` befindet
2. Führen Sie folgenden Befehl aus:
   ```bash
    docker compose up
    ```
3. Öffnen Sie einen Browser:
   - UI: `http://localhost:80`
   - API: `http://localhost:8000`

## Beenden
- Drücken Sie `Ctrl+C` im Terminal oder führen Sie
```bash 
docker compose down
```
aus, um die Anwendung zu beenden.