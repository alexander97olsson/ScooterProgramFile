# ScooterProgramFile
Länk till docker-compose filen: https://drive.google.com/file/d/1SMhEPOr0hLStIhgTGTvMLBNN19QvtGiz/view?usp=sharing

1. Ladda ner docker-compose filen.
2. Starta programmet med kommandot:
```
    docker-compose up
```
3. Stäng av programmet med kommandot:
```
    docker-compose down
```

Vill man starta separata delar från docker-compose filen kan man köra:

Starta backend:
```
    docker-compose up -d server
```
Starta webbclient:
```
    docker-compose up -d webbclient
```
Starta cykel simulering:
```
    docker-compose up -d bike
```
Starta appen:
```
    docker-compose up -d app
```

För appen ger terminalen en QR-kod som måste skannas med mobilen för att köra.

Stäng av allting genom: docker-compose down

Github:

Webbgränssittet:
https://github.com/othorde/projekt

Appen:
https://github.com/jontepson/pattern

API:
https://github.com/alexander97olsson/Scooter-API

Cykelns program / simulering:
https://github.com/jjohannaPersson/scooter_program
