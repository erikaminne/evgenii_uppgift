YOLO är en datorseendemodell som snabbt detekterar och lokaliserar objekt i bilder och videor genom ett enda neuralt nätverk, vilket delar upp bilden i ett rutnät och förutsäger objektens positioner och klasser direkt.
YOLO modulen är väldigt användbar i samhället på grund av dens realtids igenkänning. YOLO modulen är användbar i bland annat videoövervakning och skapande samt programmerande av självkörande bilar.

Evgeniis uppgift där python coden ska känna igen object genom en webcam. Till exempel en telefon, bok och person
Den här uppgiften är till långt sätt ganska likadan som den vi fick av Evgenii på första året. 
Jag följde instruktioner på websidan https://dipankarmedh1.medium.com/real-time-object-detection-with-yolo-and-webcam-enhancing-your-computer-vision-skills-861b97c78993 som Anton hade delat med mig.

Jag börjar med att installera och importera alla nödvändiga modules. YOLO modulen gör det möjligt att identifiera och upptäcka objekt i realtid. 
Jag börjar först med att starta webcamen för att kunna identifiera och upptäcka objekt igenom den. Jag hade lite problem i början med att detecta rätt webcam eftersom min dator försökte ansluta till en virtual webcam. 
YOLO har redan massor med objekt inlagda så det ända jag behövde göra var att sätta dem i en class med namn för att sedan kunna kalla på dem när jag printar ut det. 
