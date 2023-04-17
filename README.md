# Mobilní aplikace pro analýzu dat ze Spotify
Mobilní aplikace bude brát data ze spotify, konkrétně nejposlouchanější umělce, skladby a žánry.
[Celý návrh ve figmě](https://www.figma.com/file/KKZG3fChmsIYhZAAC23vjs/Untitled?node-id=0%3A1&t=3qd5shw1x59gCdfh-1)
## Získání dat
[Spotify API možnosti](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-users-top-artists-and-tracks)
## Funkce aplikace
Aplikace si bere a zpracovává různé inforamce
* Nejposlouchanější žánry 
* Nejposlouchanější umělci
* Nejposlouchanější skladby

Ve všech katergoriích lze nastavit časové úseky (1 mešíc, 3 měsíce, půl roku a rok).
## Login page
Při přihlášení se uživatel přihlásí přes Spotify a následně ve vyskakovacím okně odklikne souhlas se zpracováním údajům z aplikace.
## Home page
Na home page se zobrazují různé statistiky
* V první části jsou vždy nejposlouchanější písníčky a vždy top 3. Může se měnit období (poslední měsíc, týden atd.)
* V druhé části je nejposlouchanější autor měsíce, společně s žánrem autora
* Hop back - poslední přehrávaný playlist.
## Track a artist list
Nachází se zde dva seznamy - skladby a umělci. V obou se dá nastavovat počet zobrazených itemů a období. Lze měnit mezi textovým zobrazením v seznamu a zobrazením s covery skladeb/profily umělců.
## Pie chart
Koláčový graf, který bere 100 nejposlouchanějších písniček za poslední rok. Zobrazuje max 5 žánrů, zbytek jde do other. Lze zakliknout pro zobrazení procent.
## Profil page
Profil page obsahuje fotku, uživatelské jméno a počet followeru. Pod followery se zobrazí 3 nejvíce lajkované playlisty vytvořené autorem - pokud mají všechny stejné číslo, zobrazí se od nejnovějšího, pokud nemá uživatel playlisty vůbec nezobrazí se nic.  Dále zobrazuje shrnující informace z posledního roku - nejhranější track, autor + žánr nejhranějšího autora. Tyto informace lze exportovat a sdílet.
