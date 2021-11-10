README

SÅDAN REDIGERER DU TEKSTERNE PÅ DIN HJEMMESIDE



***************************************************************************



OVERSIGT OVER REDIGERBARE HTML-FILER

"blok1.html" er den første af de tre små blokke

"blok2.html" er den anden af de tre små blokke

"blok3.html" er den tredje af de tre små blokke

"nyheder.html er blokken dedikeret til nyheder"

"beskrivelse.html" er den tekst, der står i den store blok forneden,
dedikeret til en beskrivelse af projektet.

"footer.html" er den lille blok nederst, hvor man som regel skriver det med småt,
f.eks. adresse, copyright, hjemmesideudvikler og sådan noget.

OBS! Hvis du ser ekstrafiler med mystiske fortegn eller i form af foldere, f.eks.
blok1.fld
~$blok1.html
~$yheder.html
...og lignende, så bare lad dem være. Det er noget, der dukker op, når man
redigerer. Rediger kun den fil, der hedder "originalnavnet", altså filnavn.html



***************************************************************************



METODE 1 - REDIGER I WORD

Find den html-fil, du vil redigere i zirkusrevsbech/tekster/
Højreklik på filen og åbn den i Word
Du kan bruge følgende til at formatere tekst:
- heading (2 eller 3)
- linjeskift
- alignment/justering (det med om teksten er i midten eller i siden)
- fed, kursiv, understreget

Du kan ikke sætte billeder ind her. Kun redigere selve teksten.
Pas på, at teksten i dem, der hedder "blok" ikke bliver for lang. Det kommer
bare til at se dumt ud.

Gem filen - tryk kun "gem" eller ctrl+S. Pas på med "gem som", for filen må ikke
skifte navn eller format til f.eks. .docx. Det skal være .html og den
skal hedde det, den hele tiden har heddet. Hvis den hed "blok3.html", skal den
fortsat hedde det, for koden er afhængig af det. Hvis du kommer til at ændre navn
eller format til noget andet (f.eks. "blok3.docx" eller "ny tekst.html"), så kan
du altid med "gem som" ændre filnavnet og formatet tilbage igen, og så skal koden
nok forstå det.

Åbn Netlify, som jeg har vist dig, og træk hele zirkusrevsbech folderen ind i
drag-drop-området.



***************************************************************************



METODE 2 - CODE EDITOR

Åbn html-filen med en code editor.
Gå til denne hjemmeside:  https://html-online.com/editor/
Rediger din tekst. Kopier outputtet og indsæt det i filen til det sted,
du vil ændre.
Du kan bruge knapperne med bold, italic, align osv. I "formats" kan du
finde forskellige størrelser af headings.
Jeg vil anbefale heading 2 eller 3 til overskrifter.
Når du vil skifte tekst, så husk at slette det gamle ;-)
Gem html-filen.
Træk hele zirkusrevsbech folderen ind i Netlify i drag-drop området.



***************************************************************************



OM HTML

Al tekst er omringet af "tags". F.eks. er <p></p> rundt om et afsnit, så
teksten rykker ned på sin egen linje.
<strong></strong> er rundt om fed tekst og <img src=""> bruges til billeder.
Hvis du studerer outputtet, når du har skrevet, kan det være, du ender med
at blive så skrap til HTML, at du ikke behøver tekst-editoren mere.


