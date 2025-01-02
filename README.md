Group Assignment for the course Frontend 2 - JavaScript-bibliotek och ramverk at Nackademin

Assignement: 
Ni ska skapa en applikation som ska underlätta produktivitet i vardagslivet. Användare ska bland annat kunna hålla koll på sina dagliga rutiner, ärenden, och händelser. Det ska krävas att man är inloggad för att kunna använda applikationen.
Inloggning (Endast VG)
Man ska kunna registrera flera olika användare med användarnamn samt lösenord.
Varje användare ska kunna logga in och logga ut ur applikationen.
Vid lyckad inloggning - Ska en användare mötas av en hälsning samt ett slumpat citat från följande API: https://api.quotable.io/)
Varje användare ska ha tillgång till alla sina ärenden, rutiner och händelser den skapat när den loggar in.
Startsida
Visa ut en översikt över applikationen. Följande ska visas ut.
De tre senaste ej utförda ärenden som användaren lagt till. Länk för att navigera till lista med samtliga ärenden.
De tre rutiner med högst antal repetitioner. Länk för att navigera till lista med samtliga rutiner.
De tre nästkommande händelserna. Länk för att navigera till lista med samtliga händelser.
Todos & Activities
Användare ska kunna se en lista med ärenden att utföra, samt skapa nya ärenden. 
Varje ärende ska innehålla följande:
Titel
Beskrivning
Status - om den är utförd eller ej.
Tidsestimat - Hur lång tid ärendet tar att utföra
Kategori - (ha bestämda kategorier man kan välja mellan, till exempel hälsa, hushåll, jobbrelaterat, nöje etc.)
Deadline - Datum som det senast ska vara utfört.
Användaren ska kunna klicka på ett ärende och gå till en unik route (t.ex /todo/4). Här ska användaren kunna:
Markera ärendet som slutfört.
Ta bort ärendet.
Redigera ärendet.
Användare ska kunna filtrera och sortera listan på följande sätt:
Filtrering ska kunna ske baserat på:
Status - Slutförd / Ej utförd
Kategorier - Man ska kunna välja vilken/vilka kategorier som man vill kunna se.
Sortering - ska kunna sorteras baserat på (stigande och fallande):
Deadline
Tidsestimat
Status - Slutförd / Ej utförd
Habits
Användare ska kunna se en lista av valda rutiner som ska kunna spåra framsteg i form av antal repetitioner.
Användaren ska kunna skapa en ny rutin och ta bort existerande rutiner.
Varje rutin ska innehålla följande:
Titel - t.ex “Träning, läsa bok, meditera etc.”
Repetitioner - En siffra på hur många gånger användaren utfört rutinen.
Prioritet - (låg,mellan,hög)
Man ska kunna öka, minska och nollställa repetitioner för varje rutin.
Filtrering - Ska kunna filtreras på prioritet.
Sortering - Ska kunna sorteras på (stigande och fallande):
Repetitioner
Prioritet
Event calendar
Användaren ska kunna skapa tidsspecifika händelser. En lista på samtliga händelser ska visas ut.
Varje händelse ska innehålla följande:
Start (datum och tid)
Slut (datum och tid)
Namn på händelse
Det ska vara möjligt att lägga till, ta bort och redigera händelser.
Händelserna ska alltid vara sorterade på vilken som infaller närmast i tid.
Det ska framgå vilka händelser som redan infallit (t.ex genom utgråad text/visas i en separat lista eller liknande)
Filtrering baserat på:
Kommande händelser/Tidigare händelser

Information about the program: https://nackademin.se/utbildningar/webbutvecklare-fullstack-open-source/
