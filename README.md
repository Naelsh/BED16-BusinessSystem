# BED16-BusinessSystem
School assignment

BED16 - Projekt “Affärssystemet”

Deadline på alla inlämningar är söndag vecka 3 kl 22:00.

Kravspecifikation för affärssystemet
Affärssystemet ska innehålla: klasser, generiska listor, for-loopar, arrayList

Börja med att ta fram de klasser som behövs. Företaget säljer flera produkter. Varje produkt har ett namn, ett artikelnummer och ett pris. När någon beställer produkter skapas en order. En order har en lista över vilka produkter som ska säljas och hur många av varje produkt. Företaget har ett visst antal produkter i lager och om någon försöker beställa fler produkter än det finns i lager ska man få en varning om att leveransen kan bli försenad.
Användaren ska kunna göra följande i systemet;

lägga till en ny produkt
ändra pris för en produkt
lager - ändra antal produkter i lager
registrera en ny kund (namn, adress)
lägga till en ny order för en kund
ändra en befintlig order (antal produkter)
visa alla ordrar för en viss kund
avbryta (ta bort) en order
Detta ska göras med hjälp av en konsolapplikation. När programmet startas ska en meny med olika val visas för användaren. Hämta data från användaren med t.ex. Console.ReadLine. Det är viktigt att programmet är robust, så att om användaren skriver in ett felaktigt alternativ ska programmet inte krascha; utan antingen fråga igen eller gå vidare med ett standardalternativ.
