## Ett problem vi löste

### 1. Vilken fil och rad krockade?

Rad 3 i Main.java krockade pga två helt olika utskrifter.

### 2. Varför uppstod felet?

Felet uppstod för att två grenar ändrade samma rad samtidigt.

### 3. Hur löste ni det?

Vi löste det genom att välja den utskriften vi ville behålla, sedan städade vi bort konfliktmarkörerna och den
utskriftsrad vi inte ville behålla. Efter
ändringen ser Main.java ut som en vanlig fil, helt utan markörer och staket.

### 4. Hur avslutades mergen?

Vi kontrollerade att filerna kompilerade som de ska med javac, sedan körde vi git add, commit och push.
    