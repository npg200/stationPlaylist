# Station Playlist #

* Autori: Geoff Shang, Joseph Lee a ďalší
* Stiahnuť [stabilnú verziu][1]
* NVDA compatibility: 2021.2 and later

Doplnok zlepšuje prístupnosť Station Playlist Studio a ďalších pridružených
aplikácií a tiež umožňuje ovládať Station Playlist mimo hlavného okna
aplikácie. Podporuje tiež aplikácie Studio, Creator, Track Tool, VT
Recorder, Streamer, a tiež SAM, SPL, a AltaCast enkodéri.

For more information about the add-on, read the [add-on guide][2].

Dôležité:

* This add-on requires StationPlaylist suite 5.30 or later.
* Ak používate Systém od verzie Windows 8, odporúčame vám vypnúť funkciu
  automatického stišovania.
* Starting from 2018, [changelogs for old add-on releases][3] will be found
  on GitHub. This add-on readme will list changes from version 21.10 (2021)
  onwards.
* Z okna SPL studio je možné uložiť nastavenia skratkou ctrl+nvda+c. Môžete
  tiež načítať uložené nastavenia skratkou ctrl+nvda+r. Takisto je možné
  obnoviť pôvodné nastavenia skratkou nvda+ctrl+r stlačením trikrát rýchlo
  za sebou. Toto sa týka aj nastavení enkodéra. Tieto je však možné len
  uložiť alebo obnoviť.

## Klávesové skratky

Väčšina skratiek je určených pre Studio, ak nie je uvedené inak.

* alt+shift+T v okne  studio: Oznámy čas do konca práve prehrávanej skladby.
* Ctrl+Alt+T v okne studio (švihnutie dvoma prstami v dotykovom režime):
  Oznámy čas do konca práve prehrávanej skladby.
* nvda+shift+F12 (švihnutie dvoma prstami hore v dotykovom režime) v okne
  Studio: oznámi čas vysielania, napríklad 5 minút do celej hodiny. Stlačené
  dvakrát rýchlo za sebou oznamuje minúty aj sekundy.
* alt+NVDA+1 (švihnutie dvoma prstami doprava v dotykovom režime spl) v okne
  Studio: otvorí kategóriu upozornenia v nastaveniach doplnku.
* alt+nvda+1 pri úprave playlistu v okne creator a Remote VT playlist
  editor: Oznámi plánovaný čas spustenia playlistu.
* Alt+NVDA+2 pri úprave playlistu v okne creator a Remote VT playlist
  editor: Oznámi celkový čas skladieb v playliste.
* alt+NVDA+3 v okne Studio : zapína a vypína prehliadač jinglov.
* Alt+NVDA+3 pri úprave playlistu v okne creator a Remote VT playlist
  editor: Oznámi čas odohratia vybratej skladby.
* Alt+NVDA+4 pri úprave playlistu v okne creator a Remote VT playlist
  editor: Oznámi kategóriu a rotáciu pre načítaný playlist.
* Ctrl+NVDA+f v okne Studio: otvorí okno, v ktorom môžete nájsť skladbu
  podľa názvu alebo interpreta. NVDA+F3 hľadá dopredu, NVDA+shift+F3 hľadá
  dozadu.
* Alt+NVDA+R v okne Studio: Prepína oznamovanie skenovania knižnice.
* Ctrl+Shift+X v okne Studio: Prepína zobrazenie na braillovskom riadku.
* Ctrl+Alt+šípky doľava a doprava (pri zobrazení skladby v oknách Studio,
  Creator, Remote VT, a Track Tool): presunie kurzor na predchádzajúci alebo
  nasledujúci stĺpec.
* Ctrl+Alt+home a end (pri zobrazení skladby v oknách Studio, Creator,
  Remote VT, a Track Tool): presunie kurzor na prvý alebo posledný stĺpec.
* Ctrl+Alt+šípky hore a dole (pri zobrazení skladby v okne Studio): presunie
  kurzor na nasledujúcu alebo predchádzajúcu skladbu a oznámi vybraté
  metadáta.
* Ctrl+NVDA+1 až 0 (Pri zobrazení skladby v okne Studio, Creator (vrátane
  úpravy playlistu), Remote VT, a Track Tool): Oznámi príslušné metadáta
  (prvých 10). Stlačené dvakrát rýchlo za sebou zobrazí metadáta v režime
  prehliadania.
* Ctrl+NVDA+- (pomlčka pri zobrazení skladby v oknách Studio, Creator, a
  Track Tool): Zobrazí všetky metadáta v režime prehliadania.
* NVDA+V while focused on a track (Studio's playlist viewer only): toggles
  track column announcement between screen order and custom order.
* Alt+NVDA+C while focused on a track (Studio's playlist viewer only):
  announces track comments if any.
* Alt+NVDA+0 z okna studio: Otvorí nastavenia doplnku.
* Alt+NVDA+p z okna studio: Otvorí nastavenia vysielacích profilov.
* Alt+NVDA+F1: Otvorí uvítací dialóg doplnku.

## Funkcie bez klávesových skratiek

The following commands are not assigned by default; if you wish to assign
them, use Input Gestures dialog to add custom commands. To do so, from
Studio window, open NVDA menu, Preferences, then Input Gestures. Expand
StationPlaylist category, then locate unassigned commands from the list
below and select "Add", then type the gesture you wish to use.

* Zobrazenie okna Studio odkiaľkoľvek.
* Podpríkazy na ovládanie a informácie stavu SPL.
* Oznamovanie stavových informácií, napríklad prehrávanie odkiaľkoľvek.
* Oznamovanie stavu pripojenia k streamu z iných aplikácií.
* Podmnožina informačných príkazov.
* Oznámiť čas vrátane sekúnd z okna Studio.
* Oznámiť teplotu.
* Oznámiť názov nasledujúcej naplánovanej skladby.
* Oznámiť názov aktuálne prehrávanej skladby.
* Označenie aktuálnej skladby ako počiatočnej na časovú analýzu.
* Spustenie časovej analýzy.
* Zobrazenie štatistiky playlistu.
* Vyhľadanie textu v určených metadátach.
* Vyhľadanie skladieb s určitou dĺžkou.
* Zapnutie a vypnutie vysielania metadát.

## Ďalšie príkazy pre enkodéry

Dostupné sú tieto príkazy:

* F9: Pripojiť zvolený stream.
* F10 (SAM encoder): Odpojí zvolený stream.
* Ctrl+F9: Pripojiť všetky streami.
* Ctrl+F10 (len SAM encoder): odpojí všetky streami.
* F11: Aktivuje a deaktivuje automatické prepnutie do okna Studio po
  pripojení.
* Shift+F11: určuje, či sa automaticky prehrá prvá vybratá skladba po
  pripojení na server.
* Ctrl+F11: Zapína a vypína monitorovanie vybratého pripojenia na pozadí.
* ctrl+F12: Otvorí okno na výber odstráneného streamu (kde môžete zmeniť
  názvy a nastavenia).
* Alt+NVDA+0 and F12: Opens encoder settings dialog to configure options
  such as encoder label.

Dostupné sú tieto príkazy na prezeranie stĺpcov:

* Ctrl+NVDA+1: Pozícia enkodéra.
* Ctrl+NVDA+2: Názov pripojenia.
* Ctrl+nvda+3 z okna Sam Encoder: Formát.
* Ctrl+nvda+3 z aplikácie SPL a AltaCast Encoder: Nastavenia enkodéra.
* Ctrl+nvda+4 z okna SAM Encoder: Stav pripojenia.
* Ctrl+NVDA+4 z aplikácie SPL a AltaCast Encoder: Stav a rýchlosť
  pripojenia.
* Ctrl+NVDA+5 z okna SAM Encoder: stav pripojenia.

## Podmnožina informačných príkazov

Táto podmnožina umožňuje zistiť stav SPL Studio, napríklad prehrávanie
skladby, celkové trvanie skladieb v časovom slote a podobne. Najprv je
potrebné stlačiť skratku podmnožiny príkazov a potom príslušné
písmeno. Väčšina príkazov je určených pre okno Studio a špeciálne pre
zobrazenie playlistu. V nastaveniach doplnku je navyše možné prepnúť skratky
tak, aby simulovali správanie, na ktoré ste zvyknutí z iných čítačov
obrazovky.

Dostupné sú tieto príkazy:

* A: autopylot.
* C (Shift+C v rozložení pre JAWS): Oznámi názov prehrávanej skladby.
* C (Rozloženie JAWS): Zobraziť jingle (len z playlistu).
* D (R v rozložení pre JAWS): Oznámi ostávajúci čas do konca skladby. (Ak
  nefunguje, zopakujte skratku zo zobrazenia playlistu).
* E: Oznámi Stav streamovania metadát.
* Shift+1 až Shift+4: Stav jednotlivých pripojení. Shift+0: Stav pre DSP
  enkodér.
* F: Nájsť skladbu (len zo zoznamu skladieb).
* H: Oznámi Trvanie skladieb v aktuálnom hodinovom slote.
* Shift+H: Oznámi zostávajúci čas skladieb v aktuálnom hodinovom slote.
* I (L v rozložení pre JAWS): Oznámi počet pripojených poslucháčov.
* K: Prejde na záložku (vyznačenú skladbu v zozname skladieb).
* Ctrl+K: Nastaví aktuálnu skladbu ako záložku (v zobrazení playlistu).
* L (Shift+L v rozložení JAWS): Line in.
* M: Mikrofón.
* N: Oznámi Názov nasledujúcej skladby.
* P: Oznámi Stav prehrávania (prehrávanie alebo zastavené).
* Shift+P: Oznámi tóninu skladby.
* R (Shift+E v rozložení JAWS): zapína a vypína nahrávanie do súboru.
* Shift+R: Oznámi stav skenovania knižnice.
* S: Oznámi naplánovaný čas spustenia skladby.
* Shift+S: Oznámi čas do spustenia (začína o).
* T: zapína a vypína editáciu jinglov.
* U: Oznámi čas od spustenia aplikácie Studio.
* W: Oznámi Predpoveď počasia.
* Y: Oznámi stav úpravy playlistu.
* F8: Zobrazí štatistiku playlistu (počet skladieb, trvanie playlistu,
  najkratšia a najdlhšia skladba).
* Shift+F8: Uloží prepis playlistu vo viacerých formátoch.
* F9: Označí skladbu ako počiatočnú pre analýzu (v zobrazení skladieb).
* F10: Analyzuje skladby (zo zobrazenia skladieb).
* F12: Prepína medzi konfiguračnými profilmi.
* F1: Oznámi funkcie a klávesové skratky.
* Shift+F1: Otvorí online používateľskú príručku.

## príkazy na ovládanie SPL

je to množina príkazov, pomocou ktorej môžete SPL ovládať aj ak nemáte
zamerané okno SPL Studio. NVDA Povie "ovládanie". NVDA počká na ďalší
príkaz, ktorým môžete sledovať stav mikrofónu, alebo prehrávanie
nasledujúcej skladby.

Dostupné sú tieto príkazy:

* P: Play the next selected track.
* U: Pause or unpause playback.
* S: Stop the track with fade out.
* T: Instant stop.
* M: Turn on microphone.
* Shift+M: Turn off microphone.
* A: Turn on automation.
* Shift+A: Turn off automation.
* L: Turn on line-in input.
* Shift+L: Turn off line-in input.
* R: Remaining time for the currently playing track.
* Shift+R: Library scan progress.
* C: Title and duration of the currently playing track.
* Shift+C: Title and duration of the upcoming track if any.
* E: Encoder connection status.
* I: Listener count.
* Q: Studio status information such as whether a track is playing,
  microphone is on and others.
* Cart keys (F1, Control+1, for example): Play assigned carts from anywhere.
* H: Layer help.

## Upozornenia na zapnutý mikrofón, intro a koniec skladby

Predvolene NVDA zapípa 5 sekúnd pred koncom skladby alebo pred koncom intra
skladby a tiež upozorňuje, keď je zapnutý mikrofón. Toto nastavenie je možné
zapnúť, vypnúť a upraviť hodnoty po stlačení alt+nvda+1. Je možné nastaviť
upozornenie pípaním, rečou alebo oboje.

## Vyhľadávač skladieb

Ak chcete rýchlo nájsť skladbu podľa názvu interpreta alebo názvu skladby,
stlačte ctrl+nvda+f. Zadajte názov skladby alebo interpreta. NVDA vás
presunie na skladbu, ak sa našla, alebo zobrazí chybu, ak sa skladbu
nepodarilo nájsť. Ak chcete zopakovať to isté hľadanie smerom dopredu,
stlačte nvda+F3. Vyhľadávanie opačným smerom spustíte skratkou
nvda+shift+F3.

Pozor: Hľadanie rozlišuje veľké a malé písmená.

## Prehliadač jinglov

Studio umožňuje uložiť a zaradiť až 96 jinglov, v závislosti od edície,
ktorú používate. Pomocou NVDA môžete zistiť pozície jinglov v prehliadači.

Aby ste zistili pozíciu jingla, v okne studio stlačte alt+NVDA+3. Ak príkaz
stlačíte raz, dozviete sa, ktorý efekt je priradený konkrétnej skratke. Po
dvojitom stlačení sa zvuk prehrá. Prehliadač opustíte opäť skratkou
alt+nvda+3. Podrobnosti nájdete v návode k tomuto doplnku.

## Analyzovanie času

Ak chcete analyzovať čas vybratých skladieb, postupujte nasledovne: Nájdite
požadovanú počiatočnú skladbu. Potom stlačte skratku na spl zložený príkaz
nasledovanú klávesom F9. Potom nájdite koncovú skladbu, opätovne stlačte
skratku na spl zložený príkaz nasledovaný klávesom F10.

## Prehliadač metadát

Skratkami Ctrl+NVDA+1 až 0, môžete čítať metadáta k skladbe. Predvolene je
to v okne studio: interpret, názov, dĺžka, intro, outro, kategória, rok,
album, žáner a nálada. V editoroch playlistu Creator a Remote VT závisí
poradie podľa toho, ako je nastavené usporiadanie na obrazovke. Zobrazené
metadáta sa dajú nastavovať v prehliadači metadát v nastaveniach
doplnku. Tieto nastavenia sa zohľadňujú len pre Studio a Tracktool.

## Track column announcement

You can ask NVDA to announce track columns found in Studio's playlist viewer
in the order it appears on screen or using a custom order and/or exclude
certain columns. Press NVDA+V to toggle this behavior while focused on a
track in Studio's playlist viewer. To customize column inclusion and order,
from column announcement settings panel in add-on settings, uncheck
"Announce columns in the order shown on screen" and then customize included
columns and/or column order.

## Štatistika playlistu

Zloženým príkazom SPL F8 si môžete z okna studio zo zoznamu skladieb
zobraziť štatistiku playlistu. Tu zistíte počet skladieb, najdlhšiu skladbu,
najhranejšieho interpreta a podobne. Ak si priradíte k tejto funkcii vlastnú
skratku, môžete po jej dvojitom stlačení zobraziť informáciu v režime
prehliadania. Okno so štatistikou zatvoríte klávesom ESC.

## Prepisy playlistu

Zložený príkaz SPL shift+F8 umožní uložiť playlist ako prepis v čistom texte
alebo ako tabuľku HTML.

## Nastavenia doplnku

Z okna Studio môžete skratkou alt+nvda+0 otvoriť nastavenia doplnku. Môžete
tiež použiť ponuku NVDA > možnosti. Tu tiež môžete nastaviť profily.

## Profily

Pre rôzne relácie si môžete vytvoriť rôzne profily. Nastavenia vyvoláte
skratkou alt+nvda+p.

## Dotykový režim

Ak máte k dispozícii dotykovú obrazovku, používate Windows od verzie 8 a
NVDA  od verzie 2012.3, môžete na ovládanie doplnku použiť dotykové
príkazy. Najprv je potrebné dotknúť sa obrazovky tromi prstami. Následne
vykonajte gestá spomenúté vyššie v tomto návode.

## Version 22.01

* If add-on specific command-line switches such as "--spl-configinmemory" is
  specified when starting NVDA, NVDA will no longer add the specified
  parameter each time NVDA and/or Studio runs. Restart NVDA to restore
  normal functionality (without command-line switches).

## Version 21.11

* Initial support for StationPlaylist suite 6.0.

## Version 21.10

* NVDA 2021.2 or later is required due to changes to NVDA that affects this
  add-on.

## Staršie verzie

Výpis zmien pre staršie verzie doplnku nájdete na samostatnej stránke
(anglicky).

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=spl

[2]: https://github.com/josephsl/stationplaylist/wiki/SPLAddonGuide

[3]: https://github.com/josephsl/stationplaylist/wiki/splchangelog
