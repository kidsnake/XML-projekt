# XML-projekt

Link na github: https://github.com/kidsnake/XML-projekt

Link na demonstraciju: https://youtu.be/vrXTU5t9xYE  --- bolje preuzmite video iz zipa ili s Github repozitorija.


#Napomena!!!!

S obzirom na to da se učitava lokalna JSON datoteka, CORS neće dozvoliti ispravno učitavanje iz sigurnosnih razloga. Ukoliko želite lokalno isprobati rad projekta, možete instalirati ekstenziju Live Server za Visual Studio Code, otvoriti projektnu mapu, te desni klik na Index.html i odabrati opciju "Open with Live Server". Tek tada će se podaci ispravno validirati.

#Opis:

Index stranica sadrži polja za upis korisničkog imena i lozinke, te se isti uspoređuju s podacima izvučenim iz lokalne JSON datoteke. Ukoliko se podaci poklapaju, učitava se Home stranica.

#Sadržaj:

   Index.html  - početna stranica gdje se unose i provjeravaju podaci.

   Home.html - stranica koja se učitava ukoliko su uneseni ispravni podaci. 

   styles.css - datoteka korištena za izgled prethodno navedenih stranica.

   demonstracija projekta.mp4 - videoprikaz rada projekta. Prikazuje unos ispravnih i pogrešnih podataka, te dodavanje novog korisnika u JSON datoteku, te njegov login. 

   useri.JSON - datoteka iz koje se čitaju podaci pomoću jQuery, te spremaju u JS objekt na Index.html stranici, kako bi se usporedili s unesenim podacima. Podaci korišteni za usporedbu su username i password.


