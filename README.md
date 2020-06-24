# ArchivCZSK Premium

[Video Navody](https://www.youtube.com/channel/UCmBS0gFkw11vBeHjjK_AGqA/videos)


Prvotná instalácia je zdarma. Pokiaľ sa bude robiť vývoj resp. oprava už existujúcich doplnkov, prípadne pridávanie nových, tak aktualizácia bude klientovi dostupná po uhradení symbolického poplatku. Klient sa rozumie set-top box. V prípade multiboot stačí archív aktualizovať na jednom a do zvyšných image nainštalovať [verziu 1.0.0](https://github.com/mtester270/archivczskpremium/releases/tag/v1.0.0) a následne manuálne prepísať obsah adresára /usr/lib/enigma2/python/Plugins/Extensions/archivCZSKpremium.

Prosím uvedomte si že plugin ako taký len transformuje verejne dostupné údaje do pohodlnej formy pre užívateľa (je len zobrazovač) a nemá nic spoločné s poskytovateľom údajov. Pokiaľ poskytovateľ zmení údaje môže to spôsobiť nefunkčnosť niektorého z doplnkov čo môžete následne nahlásiť a ak to bude v mojich silách tak to môžem opraviť.

V prípade otázok a požiadaviek na vylepšenie môžete napísať [email](mailto:archivczsk@gmail.com).

# Problém pri spustení
Pokiaľ pri vstupe do "Doplnkov/Modulov" hlási enigma2 chybu ".../_counter.so: cannot open shared object file..." tak si treba prečítať [TOTO](https://github.com/mtester270/archivczskpremium/releases/tag/v1.0.0).

# Aktualizácie
Aktualizácia je viazaná na konkrétny čas (čas vytvorenia požiadavky) a je poskytovaná ako celkový balíček (nie jednotlivo). To znamená, že pokiaľ používate prvotnú verziu ktorá je zdarma a v priebehu času sa povedzme vylepšili resp. opravili 4 doplnky tak po uhradení poplatku a spracovaní platby dostanete poslednú aktualizáciu. To isté platí, pokiaľ klient uz pred tým aktualizoval kde boli opravené 2 doplnky a teraz chce aktualizovať znova, tak dostane už len zvyšné 2 doplnky, ktoré sa opravili.

Po požiadaní o aktulizáciu máte 14 dní na uhradenie poplatku. Pokiaľ tak neurobíte, tak sa Vaša požiadavka zneplatní v systéme a taktiež v set-top boxe. To znamená že pri spustení archívu sa Vám znova zobrazí možnosť požiadať o aktualizáciu. Po úhrade sa platba musí spracovať (štandardne do 1 hodiny). O spracovaní budete informovaný na registrovaný email platobnej brány.

Aktuálny zoznam vylepšení nájdete [TU](https://github.com/mtester270/archivczskpremium/releases).

Automatická kontrola aktulizácií pri spustení archívu sa dá v nastaveniach vypnúť. Tým pádom klient nebude nikdy notifikovaný o nových aktualizáciach, pokiaľ si toto nastavenie znovu nezapne.

# Platba
Platbu je nutné identifikovať podľa inštrukcií zobrazených na obrazovke po odkliknutí súhlasu s aktualizáciou. Pri chybne zadanom identifikátore je možné, že aktualizácia nebude spracovaná, preto si davajte pozor pri odpisovaní.

# Zálohovanie
Po úspešnej aktualizácii doporučujem archiv odzálohovať. Už stiahnuté aktualizácie sa zo servra mažú, tak prosím nežiadajte opätovné obnovenie odomňa. Kazdý je zodpovedný za svoj box a to čo s ním robí.

1) Pripojíte sa na box pomocou FTP protokolu napr. cez TotalCommander
2) Skopírujete adresár do PC
```
/usr/lib/enigma2/python/Plugins/Extensions/archivCZSKpremium
```

1) Pri obnove najskôr nainštalujete ipk balíček a teda prvotnú [verziu 1.0.0](https://github.com/mtester270/archivczskpremium/releases/tag/v1.0.0)
2) Následne prepíšete odzálohovaný adresár v boxe z PC
3) Až teraz vykonajte reštart príjmača!!!

[Video Navody](https://www.youtube.com/channel/UCmBS0gFkw11vBeHjjK_AGqA/videos)
