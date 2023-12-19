# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

`POST /createitem`: Erstellen eines neuen Elements

`DELETE /deleteitem/{itemId}`: Löschen eines Elements

`PUT /updateitem/{itemdId}`: Aktualisieren eines Elements
