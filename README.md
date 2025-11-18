# CountyControl – Pure JavaScript Remote Console für ER:LC Private Server

**Die leichteste, schnellste und 100 % PHP-freie Remote-Console für Roblox ER:LC Private Server**  
Funktioniert perfekt mit Links wie:  
`roblox://placeId=2534724415&launchData={"psCode":"NRWNET"}`

Keine Datenbank · Kein PHP · Nur Node.js + WebSocket · Unter 5 Sekunden gestartet!

<img src="https://i.imgur.com/2fF9qWj.png" alt="CountyControl Screenshot" width="100%"/>

## Features

- Extrahiert automatisch den `psCode` aus jedem Roblox Private-Server-Link  
- Live-Befehle an deinen ER:LC Server senden  
- 100 % JavaScript / TypeScript ready  
- Keine Installation von PHP, Apache, MySQL  
- Läuft auf Windows, Linux, VPS, Raspberry Pi – überall wo Node.js läuft  
- Auto-Reconnect bei Verbindungsabbruch  
- Minimaler Fußabdruck (unter 50 KB)

## Schnellstart (unter 30 Sekunden)

```bash
git clone https://github.com/dein-name/CountyControl.git
cd CountyControl
npm install
npm start
