# Design och implementation av en testdriven fullstack-applikation för behovsbaserad hantering och prioritering av utvecklingsprojekt i ideella organisationer

## Projektbeskrivning
Detta examensarbete syftar till att utveckla en testdriven fullstack-applikation för att samla, visa och
prioritera digitala utvecklingsprojekt inom Scouterna. I dagsläget saknas en gemensam plattform där
projekt och idéer presenteras på ett överskådligt och lättförståeligt sätt, vilket leder till bristande
samordning och risk för att liknande lösningar utvecklas parallellt i olika kårer.
Applikationen kommer att innehålla inloggning via ScoutID, ett formulär där medlemmar kan föreslå
nya projekt samt en tydlig och användarvänlig vy över pågående projekt. Projekten presenteras på ett
sätt som är anpassat för både tekniska och icke-tekniska användare, med möjlighet att ta del av mer
teknisk information via länkar till tillhörande GitHub-repositorier. Användare ska även kunna markera
projekt med en “gilla”-funktion för att visa intresse.
Syftet med systemet är att förbättra överblicken över pågående initiativ samt att synliggöra vilka
projekt som engagerar flest medlemmar. Systemet ska fungera som ett stöd för prioritering genom att
balansera medlemmars behov med ideella utvecklares engagemang, snarare än att styra
utvecklingen strikt.
Lösningen utvecklas med Scouterna som kontext, men utformas på ett generellt sätt så att den även
kan användas av andra ideella organisationer med liknande behov av att samla idéer, synliggöra
projekt och skapa bättre överblick.
Projektet genomförs med fokus på testdriven utveckling och innefattar både frontend- och
backend-utveckling.
Målet är att leverera en fungerande applikation med fokus på kärnfunktioner, där centrala delar
såsom autentisering, projektförslag och visning av projekt implementeras och testas.

## Frågeställning
Hur kan en testdriven fullstack-applikation designas för att, genom ScoutID-autentisering,
formulärbaserad insamling av projektförslag, länkning till GitHub-repositorier samt ett
gilla-system för pågående projekt, möjliggöra en tillgänglig och överskådlig hantering av
utvecklingsprojekt som stödjer en balans mellan medlemmarnas behov och ideella
utvecklares engagemang inom Scouterna?

Frågeställningen kan komma att justeras under arbetets gång vid behov, exempelvis baserat på
tekniska avgränsningar eller nya insikter som uppstår under utvecklingsprocessen.

## Stack:
Next.js
Prisma
PostgreSQL
Kubernetes