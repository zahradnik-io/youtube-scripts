# Notebook z vášho mobilu? Spoznajte NexDock

## Hook
Mám... sen. Dlhotrvajúci sen, že chcem používať môj mobil ako linuxový notebook. Takže kamkoľvek pôjdem, len vložím svoj telefón do docku, a všetku svoju prácu mám po celý čas so sebou. Nechcem používať viac zariadení. S projektami ako UBPorts sa môj sen pomaly stáva realitou, ale pred nami je ešte dlhá cesta. Dnes vám ukážem NexDock, čo je notebook poháňaný vašim smartfónom alebo Raspberry Pi.

## Content
- Ako môžem používať môj telefón ako notebook?
  - Firmy ako Microsoft a Canonical pracovali na konvergencii dlhú dobu. Funguje to tak, že keď pripojíte k telefónu veľkú obrazovku, používateľské prostredie sa zmení na desktopové.
  - V roku 2015 som si kúpil Lumiu 950. Bol to telefón od Microsoftu, ktorý mal tiež dock, do ktorého ste mohli pripojiť externý displej, klávesnicu a myš, a ktorý ponúkal s určitými obmedzeniami prostredie, ktoré pripomínalo to z plnohodnotného Windowsu. Bol to krok správnym smerom, ale ten zážitok z používania nebol veľmi dobrý.
  - Canonical, tvorca linuxovej distribúcie Ubuntu, mal podobnú víziu. Chceli prispôsobiť Ubuntu na mobily a premeniť ich po pripojení k docku na plnohodnotné počítače. Nakoniec túto myšlienku upustili, ale projekt stále žije vďaka komunite a ľuďom z UBPorts. A tiež existujú iné skupiny, ktoré sa snažia o niečo podobné, napríklad taká Plasma Mobile.
  - V roku 2018, 3 roky po vydaní Lumie 950, prišiel Samsung s ich riešením, ktoré nazval DeX. Pre tú pôvodnú verziu ste si museli zakúpiť špeciálne príslušenstvo. Neskôr vám stačila obyčajná redukcia z USB-C na HDMI. Nejaký čas dokonca Samsung dával k dispozícii možnosť spúšťať na vašich telefónoch Linux. Žiaľ, toto riešenie prestali podporovať v októbri 2019.
  - Samsung DeX môže predstavovať schopné riešenie, ale funguje iba so Samsung zariadeniami. Avšak v súčasnosti dokážu všetky moderné Android smartfóny zabezpečiť HDMI výstup cez USB-C. Android 10 prišiel so skrytým desktopovým režimom, ktorý priniesol túto možnosť na zopár telefónov mimo Samsungu. V tom čase bol tento režim vysoko experimentálny. Dokázali ste ho zapnúť iba cez Možnosti pre vývojárov. Tento režim však dostáva pozornosť a časom budú nadchádzajúce mobily prinášať slušnú podporu priamo od výroby.

- Ako do toho zapadá NexDock?
  - A tu sa dostávame k NexDocku. Ide o displej s klávesnicou, touchpadom a vlastnou batériou. Všetko toto je zabalené do hliníkového šasi, ktoré pripomína ultrabooky.
  - Žiaľ, môj telefón, OnePlus 6T, HDMI výstup nepodporuje, takže skúsenosti s týmto desktopovým režimom nemám. Možno si niektorí myslíte, že mi slúži NexDock ako ťažítko, ale mýlite sa. NexDock podporuje aj minipočítače Raspberry Pi, a tých mám dostatok. Poďme sa pozrieť, ako to celé funguje.

- Prehliadka NexDocku

- Živé demo: NexDock poháňaný Raspberry Pi 4
  - Ukáž bootovanie, Raspberry OS, ovládanie hlasitosti a jasu, dotykovú obrazovku

- NexDock nie je dokonalý
  - Chcel som použiť svoj NexDock ako druhý monitor, ktorý viem zapojiť k môjmu digitálnemu fotoaparátu
  - HDMI port je dosť vyberavý a podarilo sa mi NexDock rozbehať s mojím fotoaparátom iba raz. Takisto vtedy, keď je pripojené len HDMI, nemôžete používať ovládanie hlasitosti, pretože nefunguje.
  - Redukcia z microHDMI na HDMI je v dosť zlej kvalite. Rozlomila sa mi už po pár použitiach. Našťastie sú tieto adaptéry lacné a ľahko ich viete nájsť.

## CTA
Tak to by bolo asi všetko. V tejto chvíli používam NexDock hlavne s mojimi počítačmi Raspberry Pi, keď robím nejaký embedded vývoj. Je to rýchlejšie ako pripojiť Raspberry k mojej hlavnej obrazovke, klávesnici a myši, ktoré sú pripojené k môjmu hlavnému počítaču. Páči sa mi, že spracovanie je v slušnej kvalite, vrátane fullHD dotykového displeja. Teoreticky bude môcť NexDock používať roky, akurát sa budú meniť zariadenia, ktoré k nemu pripojím.

Čo si myslíte o konvergencii? Dáva pre vás zmysel používať váš telefón namiesto notebooku? Dajte mi vedieť v komentároch nižšie. Vďaka a vidíme sa u ďalšieho videa.
