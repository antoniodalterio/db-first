# Auto Usate

tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

![table](/db-AutoUsate.png)

## caratterische auto da inserie

- il dato VIN (Vehicle Identification Number) e LIcense plate sono state gestite con l'attributo <b>"UNIQUE"</b> visto che sono dati univoci.

- la License plate è stata gestita con un varchar visto che le targhe non hanno lo stesso numero di caratteri in tutti i paesi

- il VIN (Vehicle Identification Number) è stato gestito con un <b>char(17)</b> essendo composto per convenzioni internazionali da 17 caratteri (cifre e lettere).
