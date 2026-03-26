### Setup
- Starte `gradlew setupDecompWorkspace`
- Starte `gradlew idea`
- Starte `gradlew genIntellijRuns`
- Öffne das Projekt in IntelliJ IDEA

### Building
- Starte `gradlew build`

### Features
- unendlich, konfigurierbare Hologramme
- unendlich, einstellbare Hauptgewinne/Jacpots
- Discord Webhook/Nachrichten
- Einstellbare Nachrichten mit Platzhaltern

### Platzhalter
- Hologramme
  - Jackpot
    - {price} = Wert des HGWs
    - {amount} = Anzahl der bisheringen Ankäufe
    - {player} = Name des letzten Spielers
  - Umsatz
    - {wager} = Umsatz des Spielers
    - {position} = Position im Ranking
    - {player} = Name des Spielers
- Nachrichten
  - Ingame & Discord
    - {price} = Wert des HGWs
    - {amount} = Anzahl der bisheringen Ankäufe
    - {player} = Name des letzten Spielers
    - {purchase_amount} = Anzahl im letzten Ankauf

### Ingame-Commands
- /ggstats - Öffnet die Ingame-Command Übersicht

### Contributors
- [Doppelbemme](https://github.com/FelixSche)