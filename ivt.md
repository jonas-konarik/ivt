### 1. Informatika teoretická, aplikovaná, pojmy
- **teoretická informatika** přebírá některé znalosti z matematiky, studuje je a aplikuje je na konkrétní teoretické problémy v informatice - většinou algoritmy na cokoliv prostě
- **aplikovaná informatika** bere znalosti teoretické informatiky a aplikuje je na konkrétní praktické problémy co se počítačů týče (teoretická informatika navrhne algoritmus na nějakou třeba komunikaci v síti, aplikovaná veyme tenhle algoritmus a udělá ho na nějaký opravdový síti, třeba školních počítačů nebo tak). 
- Aplikovaná verzus teoretická -vědní disciplína- se rozlišuje často, i u matiky nebo stavařiny, ale ta linie mezi tim co je aplikovany a co je teoreticky je dost nejasná, často jen pocitová
- **teoretická informatika zahrnuje**
	- trochu spojité matematiky, jako je matematická analýza
	- geometrii v počítačové grafice
	- diskrétní matematiku (teorie grafů, kombinatorika, logika, algebra) obecně v teorii, programování a algoritmech
	- pravděpodobnost a statistiku opět v algoritmech
- **aplikovaná informatika zahrnuje**
	- všechny (alespoň většinu) znalostí teoretické informatiky které aplikuje například na:
	- návrh konkrétní databáze pro konkrétní firmu
	- tvorba firemních webových stránek
	- naprogramování konkrétního algoritmu v konkrétním jayzyce
	- návrh konkrétního hardwaru (thinkpad t480, základová deska MSI, ...)
	- vývoj jakýkoliv aplikace a hry
	- nebo aplikace na jiné než informatické-počítačové věcy
		- bioinformatika - řeší prostě počítače ve zdravotnictví
		- výpočtové systémy pro stavitelství - nikdo nepočítá baráky v ruce...
		- jakákoliv jiná vědní disciplína taky potřebuje počítače (fakt jakákoliv, klidně pajda a počítače ve výuce a takový pičoviny. Cokoliv řekneš bude dobře)
- **Výpočetní technika zahrnuje**
	- opět některý věci z matematiky a informatiky, ale taky spousta elektrotechniky, protože lidi co dějak výpočetní techniku fakt navrhujou elektrický pičovinky v těch počítačích (Jakub Kares)
	- je to věda o tom jak prostě udělat počítač/drona/autíčko/něco se senzorama a dalsi kokotinky, opět příkladů spousta, nemůžeš se splést
		- pravděpodobně pokud postavi nejakyho drona tak ho budou chtit i ridit, to taky muze spadat pod vypocetni techniku ale je to hodne okrajovy, teorie rizeni se studuje jinde vetsinou
- **Informace**
	- abstraktni pojem, neco co se da uchovavat a šířit (lepsi definice jde blbe)
	- abychom ji ale mohli sdilet a uchovavat a treba i cist tak tu informaci musime nejak zakodovat. Kodovanim se mysli treba to, ze prirozeny cislo prevedes do binarni soustavy a uchovas v pocitaci jako jednicky a nuly.
	- Opacny pohled je, ze pocitac umi pracovat jen s binarni soustavou a i pres to umi nejakym zpusobem zachytit koncepty mimo binární soustavu, jako je skin z lolka, akce zmáčknutí myši, obrázek nyan cat ...
	- Pointa je takova ze jsme skin z lolka / obrazek zakodovali do binarni soustavy aby s tim mohl pocitac pracovat a uchovat to.
	- Pro hlubší pochopení se podívejme na nějaký **příklady kódování**
		- **Přirozená čísla** v počítači
			- nejjednodušší příklad, prostě je převedeme do binární soustavy a uchováme v počítači jako nuly a jedničky
			- Jde o to, že jsme něco matematickýho, nějakou informaci, převedli do řeči počítače aka zakódovali
		- **Písmena ASCII**
			- správně se jim neříká písmena, ale spíš charaktery, protože celý ASCII neobsahuje jenom písmena ale to je detail
			- Jak zadat do počítače písmeno když počítač zná jen jedničky a nuly? Jednoduše! Prostě si někdo v minulosti vymezil na jedno písmeno 1 Byte (8 bitů). 
			- V jednom bytu se dá uchovat určitej počet informací, souvisí to s kombinatorikou, třeba přes kombinatorický pravidlo součinu máš 8 pozic a na každý můžou bejt 2 číslice, to je celkem 2^8 různejch možností, celkem 256.
			- A lidi si v minulym století prostě řekli, že 00000000=a, 00000001=b, 00000010=c, 00000011=d, ...
			- Je to fakt jen o tom, že si o nějaký sekvenci nul a jedniček řekneš že něco znamenaj.
			- V tom je taky jedinej zádrhel kódování. sekvence 01001011 může znamenat 15 když o tom přemýšlíš jako o přirozenym číslu, může to znamenat písmeno 'ů' v kódování ASCII a může to bejt třeba pixel, cokoliv
			- Je teda důležitý, abys s danou zakódovanou informací měl i znalost jak je zakódovaná, nebo "co je v ní schovaný"
		- **Písmena UNICODE**
			- další kódování písmen, o něco složitější ale je v něm víc znaků, třeba čínský blbosti a emoji
			- funguje jako nadstavba pro ASCII, ale to je detail
			- konkrétní tabulku ASCII/UNICODE najdes treba [tady](https://web.alfredstate.edu/faculty/weimandn/miscellaneous/ascii/ascii_index.html), ty priklady co jsem daval byly samozrejme jen ilustrativni a jsou blbe
		- **Obrázky zjednodušeně**
			- s celym obrázkem je to složitější, ale naučim tě jeden ze způsobů jak zakódovat pixel, obrázek pak bude víc pixelů
			- barevnej RGB pixel (se budes ucit s tatou) se da reprezentovat trojicí čísel (Red, Green, Blue). 
			- Přirozený čísla už umíme kódovat, a tedy pixel budou prostě 3 binární čísla za sebou, tedy šedej pixel bude 000001110000011100000111 třeba
		- vyjadřovali jsme všechno v binární soustavě, ale samozřejmě je to teoreticky možný v každý soustavě a nebo jakýkoliv jiný blbosti. Klíčem je to, že něčemu "přiřadíš takhle význam"
- **Ergonomie**
	- udává, jak bys měl bejt postavenej u práce s počítačem a jak bz měl bejt postavenej ten počítač
		- pravidelné přestávky, cvičení
		- monitor bez závad co kazí oči
		- klávesnice tak, aby si šlo opřít zápěstí
		- to samý s myší
		- sedět rovně a koukat rovně
		- lokty pravej úhel
- **Hygiena a bezpečnost**
	- zdravotní rizika
		- tenisový loket - při dlouhodobé práci se špatně umístěnou klávesnicí, bolí to i guess
		- onemocnění páteře - když sedíš blbě u kompu dlouho tak z toho bolí záda
		- onemocnění zraku - dlouho koukáš do monitoru a pak bolí oči/hlava
	- negativní vlivy
		- závislost na počítačových hrách
		- závislost na sociálních mediích a internetu
- Využití osobami s **handicapem**
	- pico co **TODO
### 2. Počítačová sestava
- **desktop
	- krabice 
		- zakladova deska - k cemu slouzi, co je na ni
		- pamet RAM - ruzny generace, k cemu slouzi
		- pevny disk - dva hlavni druhy
		- Processor - k cemu slouzi, co je na ni
		- Graficka karta - k cemu slouzi
		- Zdroj
		- ...
	- periferie
		- monitor
		- mys
		- klavesnice
		- reproduktory, mikrofon, ...
	- exoticky prvky pocitace
		- CD/ROM
		- ctecka jakejchkoliv jinejch medii
		- sitova karta, zvukova karta - dneska na zakladovy desce
- **Laptop** - ma vsechno v sobe a vypada jako notebook zejo
- **All-in-one** - ma v sobe vsechno krome klavesnice a mysi (vetsinou)
- **Princip chodu**
	- Pocitac dostane input (zmacknes mys nebo klavesnici nebo tak), to se kabelem dostane do zakladovy desky a tam na ty uz to dokaze nacist operacni system, kterej ten vstup posle nejakymu programu (treba lolko) ten program se rozhodne ze s tim vstupem neco udela (to rozhodnuti je nejaka instrukce processoru) a na zaklade toho rozhodnuti treba vykresli neco na monitor (pomoci graficky karty) posle neco na servery lolka pres ethernet port a ulozi si treba neco na disk.
	- Po celou dobu se vsechny soucastky nabiji ze zdroje a po celou dobu je momentalni stav ty hry (programu) a operacniho systemu ulozenej v pameti RAM
- **Periferní zařízení** - viz další kapitola
- **Software** v sestavě
	- bios na základový desce
	- operační systém
	- programy stažené uživatelem - hry, office, prohlizec, ...
### 3. Periferní zařízení
- obecně se prej dělí na vstupní, výstupní a multifunkční
- **Vstupní** zařízení
	- _Klávesnice_ - slouží k zadávání znaků (ASCII), připojená přes USB, pod klávesamy jsou snímače které při stisknutí pošlou signál přes to USB
	- _Myš_ - určuje polohu kurzoru na obrazovce, také připojená přes USB, jsou různé druhy, například  kuličková, optická a laserová
	- _Tablet_ - to co má táta na stole, určuje polohu kurzoru pomocí tabletu a pera
	- _Skener_ - digitalizuje danej dokument, dnes součástí tiskáren.
	- _Mikrofon_ - mění zvuk na elektrický signál, který je potom přeměněn na signál digitální a do počítače jde většinou zase přes USB (většinou)
	- _Webkamera_ - Digitalizuje obraz v ```x``` snímcích za sekundu, z toho video
	- _Gamepad_ - několik tlačítek co fungují jako klávesnice, 2 joysticky, případně jakýkoliv složitější gamepad
- **Výstupní** zařízení
	- _Monitor_ - zobrazuje informace, dnes je používána technologie LCD, velikost daná uhlopříčkou (palce, cm) a poměrem stran. Má nějaké rozlišení pixelů (1920x1080) a nějakou obnovovací frekvenci (60hz) (potom odezva, jas...)
	- _Dataprojektor_ - taky zobrazuje, ale přes žárovku, obvykle pro vic lidi
	- _Reproduktory_ - převádějí digitální signál na elektrický a ten na zvuk pomocí elektromagnetů, slouží k přehrávání
	- _Tiskárny_ - tisknou na papír, druhy jsou například
		- jehličkové
			- tisknou malejma tečkama, maj je třeba na poště jak jsme makali
			- jsou hlučné a pomalé
			- ale levné na provoz a mohou tisknout více papírů najednou
		- inkoustové
			- rychle a poměrně kvalitně, mohou být barevné
			- vyšší pořizovací cena i cena tisku
		- Laserové tiskárny
			- laserová tiskárna vykreslí laserem obrázek na speciální válec, na jehož povrch se pak nanese toner a obtiskne se na papír
			- nejlíp tiskne, neni to uplne pomaly a ani tak drahy
			- ale ma vysokou porizovaci cenu
- **Multifunkční** zařízení
	- sluchátka s mikrofonem
	- tiskárna se skenerem
- **Paměťová média
	- **TODO
### 4. Datová úložiště, archivace, komprese
- slouží k uchování zakódovaných informací
- **magnetická** úložiště
	- první byly magnetické pásky, kazety a diskety, které ale měly malou kapacitu a malou rychlost
	- po nich přišly pevné disky (HDD) - kotouč potažený magnetickou vrstvou, na které jsou pak stopy a sektory. Pevný disk může mít i víc kotoučů a čtení/zápis je prováděn přes pohyblivou ručičku. Výhodou HDD je velká kapacita a slušná rychlost
- **optická** úložiště
	- CD, DVD a BD. Čtení a zápis je prováděn laserem, který zapisuje stav do speciální vrstvy. 
	- CD má kapacitu ~700MB, DVD má kapacitu ~5GB. BD má až 700GB.
	- Výhodou je relativně nízká cena a objem, nevýhodou je špatná přepsatelnost dat, malá rychlost a možnost poškrábání.
- **elektronická** úložiště
	- fungují na principu flash paměti, která má buňky kam jdou zapisovan nuly a jedničky
	- USB Flash disky - malá 3cm pičovinka co se zapíchne do USB portu na počítači, je na ní několik těhle flash úložišť a malej čip co je spravuje. Obvykle mají 16/32GB, ale lze i míň i víc.
	- Pamťové karty SD - také je v ní flash úložiště, jen je to jinej tvar a nepřipojuje se přes USB. Prostě se zapíchne do portu. Obvykle používaná u kamer, mobilů a foťáků, mají desítky až stovky GB
	- SSD disk - nejnovější nejlepší a nejdražší disk, prodávaj se i několika TB, jsou extrémně rychlý, jakože fakt nesrovnatelně i s HDD, ale platí se za to. Nevýhodou je prej životnost, ale reálně to neni pravda, háka se šlajsovou prostě jen živou před 10 lety, kdy se o to lidi báli
- **Kapacita** - množství informací, které se na disk vejde
- **Životnost** - jak dlouho disk vydrží
- **Komprese** (divný lidi říkaj komprimace)
	- máš nějaký data, což je zakódovaná informace, a ty s ní uděláš nějakej trik aby zabírala míň místa. Konkrétně jí komprimuješ (to je ten trik) a uložíš jí jako komprimovanou, aby ji potom mohl člověk zase otevřít. Ve svý podstatě je to zase jen zakódování informace, tentokrát za účelem zmenšení místa na disku.
	- a to jak to uděláš je zase na tobě, ale je mega těžký vymyslet něco co bude fakt efektivní
	- příklad komprese:
		- budou li za sebou víc než 3 stejné znaky/číslice, nahradíme je počtem a znakem/číslicí, tedy AAAAOOADDDBFDDDD -> 4AOOA3DBF4D
		- nic extra, je to jen začátečnická komprese, ale příklad hezkej
	- programy na kompresi - Zip, Tar, GZip, Rar (stačí zip, rar)
	- dělí se na ztrátovou a bezztrátovou kompresi. Bezztrátová je běžnější a dá se tim komprimovat všechno, to je zip, rar. Ztrátová komprese je většinou jen u médií. Malá ztráta kvality je pro velkou úsporu místa. (nejde vrátit)
	- kompresní poměr je podíl velikosti dat před a po komprimaci, čím větší tím lepší. ušetřené místo je pak rozdíl velikosti před a po, pak se to dá vyjádřit v procentech
### 5. Matematické soustavy
- číselných soustav je nekonečně mnoho, ale ty nejznámější jsou 2, 8, 10, 16.
- **(n -> 10)** převod ze soustavy o základu ```n``` do desítkové soustavy :
	- rozepíšu číslo s ciframa 7234 jako 7n^3 + 2n^2 + 3n + 4, vynásobím a sečtu
- **(10 -> n)** převod desítkové soustavy do soustavy o základu ```n``` :
	- číslo v desítkové soustavě opakovaně dělím základem ```n``` a zapisuji si celočíselný výsledek a zbytek
	- jakmile dojdu k celočíselnému výsledku rovnému nule, tvoří zbytky v opačném pořadí cifry čísla v soustavě o základu ```n```
- **Využití**
	- duh co
	- asi že dvojková je v počítačích častá, takže převod 10 -> 2 je v IVT essential
### 6. Operační systém
- základní software počítače, stojí mezi hardwarem (noťas) a aplikacemi (lolko)
- **stará se o** téměř všechny věci co ten počítač dělá - připojení k internetu, kreslení na obrazovku, ovládání procesoru a grafický karty, zapisování na disk ...
- při **spuštění** počítače se automaticky zapne BIOS, kterej ne nainstalovanej v základový desce, a spustí operační systém, případně ti nabídne nějaký menu kdybys jich měl víc. Tomuto procesu se říká **bootování**
- architektur, jak navrhnout operační systém je celá řada, je to věda, ale ta nejznámější architektura je UNIXová (je na ní postavenej MacOS i Linux)
- Každej operační systém musí dělat následující věci
	- **komunikace s hardware**, na každý zařízení v počítači má speciální **driver**, česky ovladač, kterej nějakej požadavek (připoj se k wifi) převádí na konkrétní instrukce (jedničky a nuly) kterým tenhle konkrétní síťovej čip rozumí
	- **spravuje procesy** (proces je jeden bežící program, viz task manager)
		- procesum je přidělená nějaká paměť, maj prioritu atd atd
	- **spravuje prostředky** počítače - paměť, procesor, síť, přiděluje je procesům atd
	- poskytuje **knihovny** pro základní funkce - když bys třeba programoval hru, tak jí nechceš psát tak, že řekneš ok, tak teď sáhni do paměti na tuhle adresu x8276D7, přečti 10B, pošli instrukci 1001010 do processoru... Takovýhle funkce jsou předdefinovaný v systémovejch knihovnách, aby programátoři aplikací mohli psát spíš "a=5, b=10, vypočti ```a*b```, nakresli tohle na displej"...	
	- **API** je programovací rozhraní toho počítače, basically standardizovanej způsob, jakym používáš ty věci v systémovejch knihovnách
	- **Shell** je základní způsob komunikace s počítačem. Ukáže se ti okýnko kam zadáš příkaz, třeba "ukaž mi všechny složky" a on to udělá. Shellů je spousta, na windows je to CMD a PowerShell, na Linuxu jsou jich kvanta, například Sh, Bash, já používám NuShell.
- Některý operační systémy můžou poskytovat i víc funkcí. Na Linuxu a jinejch dobrejch operačních systémech jsou tyhle funkce ve formě programů, který si můžeš normálně stáhnout a změnit a odinstalovat, Windows a MacOS maj většinu přednastavenou
	- **Grafické rozhraní** -  to na co klikáš myší, včetně plochy, grafickejch aplikací a tak. Počítač bez grafickýho rozhraní má jen textový rozhraní který vypadá jako cmd ve fullscreenu
	- Sada **defaultních aplikací** - Microsof Edge, Prohlížeč souborů, Safari, Microsoft Store, ...
- Všechny tyhle věci jsou dost modulární. Aplikace komunikuje se systémem kterej komunikuje s jádrem který komunikuje se základovou seskou pomocí nějakýho driveru. V Linuxu třeba jde vyměnit jádro, smazat driver atd... tyhle prvky se prostě staví na sebe až vznikne něco čemu se dá říkat moderní OS
- **základní operace** v shellu
	- **TODO
### 7. Bezpečnost a ochrana dat
- počítačové viry
- antiviry
- licence, autorské právo, pirátství
### 8. Internet
- historie
- komunikace
- sdílení dat
- IP, IPv4, IPv6
- protokol HTTP
- protokol FTP
- protokol WWW
- PING shell utility
- TRACERT shell utility

### 9. Informace, jednotky, bity
- **Odstavec co už znáš**
	- abstraktni pojem, neco co se da uchovavat a šířit (lepsi definice jde blbe)
	- abychom ji ale mohli sdilet a uchovavat a treba i cist tak tu informaci musime nejak zakodovat. Kodovanim se mysli treba to, ze prirozeny cislo prevedes do binarni soustavy a uchovas v pocitaci jako jednicky a nuly.
	- Opacny pohled je, ze pocitac umi pracovat jen s binarni soustavou a i pres to umi nejakym zpusobem zachytit koncepty mimo binární soustavu, jako je skin z lolka, akce zmáčknutí myši, obrázek nyan cat ...
	- Pointa je takova ze jsme skin z lolka / obrazek zakodovali do binarni soustavy aby s tim mohl pocitac pracovat a uchovat to.
	- Pro hlubší pochopení se podívejme na nějaký **příklady kódování**
		- **Přirozená čísla** v počítači
			- nejjednodušší příklad, prostě je převedeme do binární soustavy a uchováme v počítači jako nuly a jedničky
			- Jde o to, že jsme něco matematickýho, nějakou informaci, převedli do řeči počítače aka zakódovali
		- **Písmena ASCII**
			- správně se jim neříká písmena, ale spíš charaktery, protože celý ASCII neobsahuje jenom písmena ale to je detail
			- Jak zadat do počítače písmeno když počítač zná jen jedničky a nuly? Jednoduše! Prostě si někdo v minulosti vymezil na jedno písmeno 1 Byte (8 bitů). 
			- V jednom bytu se dá uchovat určitej počet informací, souvisí to s kombinatorikou, třeba přes kombinatorický pravidlo součinu máš 8 pozic a na každý můžou bejt 2 číslice, to je celkem 2^8 různejch možností, celkem 256.
			- A lidi si v minulym století prostě řekli, že 00000000=a, 00000001=b, 00000010=c, 00000011=d, ...
			- Je to fakt jen o tom, že si o nějaký sekvenci nul a jedniček řekneš že něco znamenaj.
			- V tom je taky jedinej zádrhel kódování. sekvence 01001011 může znamenat 15 když o tom přemýšlíš jako o přirozenym číslu, může to znamenat písmeno 'ů' v kódování ASCII a může to bejt třeba pixel, cokoliv
			- Je teda důležitý, abys s danou zakódovanou informací měl i znalost jak je zakódovaná, nebo "co je v ní schovaný"
		- **Písmena UNICODE**
			- další kódování písmen, o něco složitější ale je v něm víc znaků, třeba čínský blbosti a emoji
			- funguje jako nadstavba pro ASCII, ale to je detail
			- konkrétní tabulku ASCII/UNICODE najdes treba [tady](https://web.alfredstate.edu/faculty/weimandn/miscellaneous/ascii/ascii_index.html), ty priklady co jsem daval byly samozrejme jen ilustrativni a jsou blbe
		- **Obrázky zjednodušeně**
			- s celym obrázkem je to složitější, ale naučim tě jeden ze způsobů jak zakódovat pixel, obrázek pak bude víc pixelů
			- barevnej RGB pixel (se budes ucit s tatou) se da reprezentovat trojicí čísel (Red, Green, Blue). 
			- Přirozený čísla už umíme kódovat, a tedy pixel budou prostě 3 binární čísla za sebou, tedy šedej pixel bude 000001110000011100000111 třeba
		- vyjadřovali jsme všechno v binární soustavě, ale samozřejmě je to teoreticky možný v každý soustavě a nebo jakýkoliv jiný blbosti. Klíčem je to, že něčemu "přiřadíš takhle význam"
- **Jednotky
	- základní jednotka je bit. Bit jo logická hodnota True/False 1/0. Tak jak jste se učili v matice ve výrokový logice
	- spoustukrát se to hodí, ale na spoustu věcí je to malá jednotka, třeba na písmeno ASCII máš 8 bitů. Proto se rozhodlo, že bude i jednotka Byte, kde 1 Byte = 8 bitů
	- Byty i bity se značí B a b/bit a normálně se k nim dávaj předpony GB, Mbit kde se postupuje po 1024 násobku
	- Na tuhle otázku by asi bylo dobrý si nastudovat (až na místě) tabulku ascii a nějakej třeba emoji symbol na [symbl.cc](https://symbl.cc) a něco o tom kecnout

### 10. Word
- tvorba dokumentů
- formuláře
- typografická pravidla
### 11. Excel
- dokumenty v excelu?
- formátování tabulek 
- vzorce
- relativní a absolutní odkazování
- funkce
- statistika
### 12. Spolupráce wordu a excelu
- hromadná korespondence
- makra
- formuláře v excelu
- kontingenční tabulka
### 13. Prezentace
- tvorba
- časování
- přechody
- animace
- zásady
### 14. Databáze
- princip
- tvorba
- SQL
- formulář
- dotaz
- sestavy
### 15. Komunikace přes internet
- online
- offline
- email
- fóra
- chatovací aplikace
- aplikace na volání
- sociální sítě
- sdílení dokumentů
### 16. Rastrová grafika
- pixel
- obrázek
- dpi
- koláž, fotomontáž, retuš, layout webové stránky
### 17. Vektorová grafika
- vektor
- vektorová funkce
- křivka
- plocha
- souřadné systémy
- logo, vizitka, dopravní značka
### 18. Barvy, barevné modely
- barevný model
- RGB
- CMYK
- HSL
- HSV
- Přímé barvy
- psychologie barev
- barevná hloubka

### 19. 3D grafika
- definice
- proces tvorby 3D obrázku
- materiály, textury
### 20. Počítačová síť, topologie, druhy zapojení
- **zařízení**
	- Aktivní síťové prvky - basically všechny zařízení
		- Repeater (opakovač) 
			- pracuje s elektrickým signálem
			- příjmá zkreslený, zašuměný, počkozený elektrický signál
			- vysílá opravený, zesílený a správně načasovaný signál
			- umožňuje zvýšit dosah elektrického signálu bez ztráty kvality
		- Hub (rozbočovač)
			- umožňuje větvení sítě
			- veškerá příchozí data rozešle do všech ostatních portů
			- přesně z toho důvodu není vždy ideální, protože nechceš vždy data poslat do všech počítačů
		- Switch (přepínač)
			- propojuje jednotlivé části sítě
			- je na něj připojeno více zařízení, ale umožňuje poslat data z jednoho zařízení do druhého bez sdílení se všemi zařízeními
			- -> lepší bezpečnost sítě
		- Bridge (most)
			- spojuje dvě části sítě na druhé vrstvě OSI modelu
			- v paměti má tabulku MAC adres rozdělenou na "segmenty" (prostě různý grupy zařízení) a mezi těma segmentama přeposílá data
		- Router (směrovač)
			- přeposílá data k jejich cíli ve třetí vrstvě OSI modelu
			- může to dělat skoro každej počítač, ale často se používaj routery se specialnim HW a SW
	- Pasivní síťové prvky
		- kabely
		- konektory
		- zásuvky
		- rozvaděče (idk)
- **protokoly**
	- Sada protokolů TCP/IP
		- _IP, IPv4, IPv6_ - ip adresy ruznejch verzi
		- _TCP, UDP_ - protokoly pro přenos dat mezi počítačema
		- _DNS_ - systém doménových jmen - abys mohl do prohlizece psat google.com misto IP adresy
		- _DHCP_ - vubec netusim
		- _HTTP(S)_ - protokol pro sdileni webovejch stranek (S kdyz je zabezpecenej)
		- _SMTP_ - protokol pres kterej se posila email
		- _SSH_ - šifrované vzdálené připojení k počítači, lze přes to i posílat soubory (ukazu)
		- ...
- **rozdělení** sítí
	- podle velikosti
		- _LAN_ (local) - do stovek metrů, umožňují sdílet tiskárny, soubory a zpravy apod
		- _MAN_ (metropolitan) - do několika kilometrů, dneska se podobaj LAN, jsou i veřejný někdy
		- _WAN_ (world) - po celym světě, zařízení WAN jsou jednotlivé MAN a WAN připojený přes nějakej výkonnej počítač co všechno možný řídí a přeposílá (asi ne vzdycky), internet je v zásadě WAN, ale asi může bejt víc WANů, takže se po WANu můžou posílat zpávy, soubory, přístup na stránky, ...
		- _PAN_ (personal)
	- podle "topologie"
		- _Kružnice_ - lehký rozšířit, málo drátů
		- _Sběrnice_ - acnient, vsechny zarizeni pripojeny na jeden spesl kabel. Kdyz vypadne stanice tak to neni problem ale kdyz vypadne kabel je to vpici
		- _Hvězda_ - zarizeni ve stredu je kinda like a server co hodne preposila, kdyz vypadne je to blby ale je hodne lehky k nemu pripojit dalsi
		- jakejkoliv jinej obrázek, klidně jen rovná čára, tyhle jsou jen ty "nejznámější"
	- propojení sítí LAN
		- máme několik sítí LAN a chceš aby mohli okmunikovat lidi mezi sítěma nebo sítě mezi sebou
		- a jedinej trik co se udělá je, že si představíš celou síť jako jedno zařízení a zase je zapojíš do "topologií" co znáš
		- takže můžeš mít LANky ve hvězdě nebo v kružnici nebo tak
	- podle úlohy zařízení
		- _client/server_ - máš servery třeba lolka a k nim se připojujou hráči a hrajou, posílaj tam informace a server posílá jiný informace zpátky
		- _peer to peer_ - to je složitější, v roce 2023 je vic zpusobu jak to řešit, ale to zakladni si muzes predstavit ze kazdej ucastnik je zaroven klient a zaroven server a ze jsou vsichni na stejny urovni (počítač máš furt zaplej a někomu může něco posílat a zároveň můžeš na ten počítač přijít a říct jinýmu počítači ať ti něco pošle)
- **OSI** model
	- _fyzická_ vrstva - kabely, elektronika - Hub, Repeater
	- _linková_ vrstva - spojení mezi dvěma sousedními systémy - Bridge a Switch
	- _síťová_ vrstva - směrování a adresování - switch
	- _transportní_ vrstva - zajišťuje přenos dat - protokoly TCP, UDP
	- _relační_ vrstva - relace je aktuální spojení mezi dvěma zařízeníma, se propojí a dokud jsou propojený a dokud jsou propojeni tak je to ono
	- _prezentační_ vrstva - transformuje data který se posílaj v síti do nějakejch předepsanejch trvarů a blbostí
	- _aplikační_ vrstva - umožňuje aplikacím využívat síť - všechny ostatní protokoly HTTP(S), FTP, DNS, SSH, SMTP
### 21-22. Matematika v ICT
- konstrukční úlohy v geogebře
- trojúhelníky, rovnoběžníky, kružnice opsané, vepsané
- "dynamika" geometrie
- řešení matematických problémů na počítači
- program GRAPH
- funkce a její vlastnosti
- řešení rovnic, nerovnic a soustav
### 23. Algoritmy
- algoritmus
- algoritmizace
- vlastnosti
- tvorba
- diagram
### 24. Programování pro web
- jednoduchej HTML dokument by měl následující strukturu
```HTML
<!DOCTYPE html>  
<html>  
	<head>  
		<title>Název stránky</title> 
		<meta charset="UTF-8">
		<link rel="stylesheet" href="style.css">
		<meta name="author" content="Jonas Konarik">
		<meta name="topic" content="tema stranky">  
	</head> 

	<style>
		h1 {color:red;}
		p {color:blue;}
		kokos {color:gray;}
	</style>
	 
	<body>  
		<h1>Nadpis nadpis</h1>  
		<p>Tohle je odstavec.</p>  
		
		<ol>
			<li>Řazenej seznam</li> 
			<li>Ordered List</li> 
			<li>Položka seznamu List Item</li>
		</ol>
		<ul>
			<li>Neřazenej seznam</li>
			<li>Unordered List</li>
		</ul>

		<a href="https://google.com">Tohle je odkaz!</a>
		<p>Po tomhle odstavci budou dva line braky</p> <br>

		<code>a=5; print(5*a);</code> sem dat nejakej kod
		<img src="/path/to/picture.jpg" alt="popis obrázku">
		<svg width="100", height="100">
			<circle cx="50" cy="50" r="40" stroke="black" fill="yellow">
		</svg> tady bude zobrazenej SVG kruh

		<div class="kokos">
			<p>Tenhle odstavec je zanořenej v divu, 
			   dědí jeho CSS formátování, sedy pismo.</p>
		</div>
		
	</body>  
</html>
```
- jednoduchej CSS dokument by měl mít následující strukturu
```CSS
body{
	background-color: lightblue;
	background-image: url("images/picture.jpg")
	font-family: serif/sans-serif/monospace/cursive/emoji/math;
	font-family: "JetBrains Mono", monospace;
}

p{
	text-align: center;
	font-weight: 400;
}

kokos{
	padding-top: 50px;
	padding-left: 5%; 
	margin-right: 40px;
	border-style: solid;
	border-width: 5px;
}

extra{
	position: static/relative/fixed/absolute;
	float: left;
	margin: auto; /*posune do stredu*/
} 

/*snazil jsem se tu vypichnout to nejdulezitejsi*/
```
- html dokument i css soubor by měli být v jedné složce, obrázky v podsložce /img třeba
```
- projekt
	- index.html
	- style.css
	- img
		- picture1.jpg
		- picture2.png
```
- Nastudovat positioning v CSS protože je pěkně debilní!!!!!
### 25. Programování pro web - BootStrap
- webové **frameworky
	- je jich hrozná mrda a furt vznikaj nový
	- slouží k tomu aby šlověk nemusel psát všechno ručně, tak častý věci jsou předepsaný "frameworky"
	- [https://en.wikipedia.org/wiki/Comparison_of_JavaScript-based_web_frameworks](https://en.wikipedia.org/wiki/Comparison_of_JavaScript-based_web_frameworks)
- **bootstrap
	- prostě jeden hodně basic framework, máš předdefinovaný nějaký CSS třídy který použiješ v HTML dokumentu a ono to prostě nevypadá špatně a je to reizable
	- **instalace
		- ```<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">```  do  ```<head>```   pro BootStrap 4
		- ```<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">``` taky do ```<head>``` prej je to dulezity idk
		- vsechno ze stranky [https://getbootstrap.com/docs/4.0/getting-started/introduction/](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
	- **principy
		- jakejkoliv prvek co chci nějak stajlovat obalim do divu
		```HTML
		<div>
			<p>Odstavec o hovně</p>
		</div>
	   ```
		- a k tomu divu přidám nějakou třídu z bootstrapu
		```HTML
		<div class="container-fluid">
			<p>Odstavec o hovně</p>
		</div>
	   ```
		- tadá!
	- základní **třídy
		- container - box okolo prvků v něm se zafixovanou šířkou
		- container-fluid - box okolo prvků který obsahuje, šířka je celá obrazovka
		- row (řádek), col (sloupec) - vytvoří tabulku
			```HTML
			<div class="row">
				<div class="col">1.1.</div>
				<div class="row">1.2.</div>
			</div>
			<div class="row">
				<div class="col">2.1.</div>
				<div class="row">2.2.</div>
			</div>
			```
		
