# Mobilní aplikace pro analýzu dat ze Spotify
Mobilní aplikace bude brát data ze spotify, konkrétně nejposlouchanější umělce, skladby a žánry.
Pro lepší pochopení a orientaci [celý návrh ve figmě](https://www.figma.com/file/KKZG3fChmsIYhZAAC23vjs/Untitled?node-id=0%3A1&t=3qd5shw1x59gCdfh-1)
## Získání dat
[Spotify API možnosti](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-users-top-artists-and-tracks)
## Funkce aplikace
Aplikace si bere a zpracovává různé informace
* Nejposlouchanější žánry 
* Nejposlouchanější umělci - jejich žánry
* Nejposlouchanější skladby
* User info (profilovka, spotify username, jméno)

Ve všech katergoriích lze nastavit časové úseky (1 mešíc, 3 měsíce, půl roku a rok). Kdekoliv přetéka text přes width containeru zobrazí se ... za posledním možným slovem
## Login page
Při přihlášení se uživatel přihlásí přes Spotify a následně ve vyskakovacím okně odklikne souhlas se zpracováním údajům z aplikace.

![loginpage](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/login.png)
![Pop up okno](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/popup.png)
## Home page
Na home page se zobrazují různé statistiky
* V první části jsou vždy nejposlouchanější písníčky a vždy top 3. Může se měnit období (poslední měsíc, týden atd.)
* V druhé části je nejposlouchanější autor měsíce, společně s žánrem autora

![Homepage](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Home.png)
## Track a artist list
Nachází se zde dva seznamy - skladby a umělci. V obou se dá nastavovat počet zobrazených itemů a období. Lze měnit mezi textovým zobrazením v seznamu a zobrazením s covery skladeb/profily umělců.

![Track list text](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Stats_text.png)

![Track list cover](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Stats_covers.png)
![button](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/button.png)
## Pie chart
Koláčový graf, který bere 100 nejposlouchanějších písniček za poslední rok. Zobrazuje max 5 žánrů, zbytek jde do other. Lze zakliknout pro zobrazení procent.

![Pie chart](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Pie-chart.png)
![Pie chart s %](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Pie-chart_%25.png)
## Profil page
Profil page obsahuje fotku, uživatelské jméno a počet followeru. Pod followery se zobrazí 3 nejvíce lajkované playlisty vytvořené autorem - pokud mají všechny stejné číslo, zobrazí se od nejnovějšího, pokud nemá uživatel playlisty vůbec nezobrazí se nic.  Dále zobrazuje shrnující informace z posledního roku - nejhranější track, autor + žánr nejhranějšího autora. Tyto informace lze exportovat a sdílet. Při exportu je vždy stejné rozpoložení - year summary z profilu + gradient barev jednoho z coverů

![Profil page](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Profile.png)

Příklady exportu

![Example 1](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Share1.png)
![Example 2](https://github.com/pslib-cz/2022l4web-app-mockup-Lukas-Martinek/blob/main/Share2.png)
