# N150-Statiske-metoder
Opgave fra Bogen om CSharp

For at lege lidt med instans- og statiske metoder så prøv at kigge på System.IO.File og System.IO.FileInfo.

- Opret en fil på c:\temp kaldet test.txt og put lidt tekst i
  - PS: Husk at windows kunne finde på at kalde den test.txt.txt (gem som “test.txt” - altså med anførselstegn)
- Opret en ny konsol app
- Skriv kode der benytter (hjælpe)metoder fra System.IO.File
  - Prøv Exists (findes filen)
  - Prøv ReadAllText (henter tekst fra filen)
- Skriv kode der opretter et objekt der repræsenterer filen (System.IO.FileInfo)
  - var fil = new System.IO.FileInfo(@”c:\temp\test.txt”);
  - Udskriv LastAccessTime
  - Udskriv Extension

Bemærk, at de statiske (hjælpe)metoder kan findes på System.IO.File og instans metoderne kræver at du opretter et objekt og kalder metoderne på selve objektet.
