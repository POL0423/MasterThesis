# Diplomová práce

Tento projekt je diplomovou prací na téma
**Aplikace pro vyhledávání a porovnávání čerpacích stanic**.

## Cíle diplomové práce

- Vytvořit uživatelskou aplikaci (frontend), která bude komunikovat
  přes REST API se serverovou aplikací, součástí bude také aplikace
  pro Android a webová aplikace podporující PWA technologii.
- Integrovat využití polohovacích služeb (GPS a další geolokační služby
  prohlížeče a systému).
- Implementovat různé možnosti řazení konfigurovatelné zákazníkem
  (podle vzdálenosti, podle ceny, optimální jako kompromis mezi dvěma).
- Integrovat mapové podklady se zobrazením čerpacích stanic přímo v mapě.

## Úlohy k zajištění vývoje

- [x] Vymyslet jméno aplikace (PetrolScan je sice dobrý název, ale velmi generický a evokuje vysloveně crawling)
      => LITRIVO (25. 9. 2026). Záložní varianta: Trasiva. Dále v kolekci: Tankava, Fulevo, Pumiva, Usporia.
         Litr = jednotka, kterou aplikace porovnává; koncovka -ivo po vzoru palivo/mazivo/topivo;
         mimo přeplněné pole Tank*/Fuel* (TankUp, Tankomat, Tank Navigator, FuelNook Tankora, Tanklio).
         Claim: "Litrivo - ceny paliv ve tvém dojezdu." / "Fuel prices within your range."
- [ ] Zajistit datacentrum (školní datacentrum na tento účel stačit nebude)
- [x] Zajistit doménu aplikace (něco ve smyslu petrolscan.net)
      => k 25. 9. 2026 volné litrivo.cz, litrivo.sk, litrivo.eu, litrivo.com, litrivo.app
         (ověřeno v registrech přes RDAP, .eu přes whois.eu:43)
         Registrace provedena: litrivo.cz, litrivo.sk, litrivo.eu, litrivo.com
- [x] Rozhodnout package ID pro Android: com.litrivo.app (na Google Play je natrvalo, nelze přejmenovat)
- [x] Ověřit ochranné známky Litrivo a Trasiva v TMview, třídy 9 / 35 / 42 (rešerše je bezplatná)
- [ ] Zajistit vývojové prostředí (aplikace bude open-source)
- [ ] Rozšířit povědomí o této aplikaci mezi ostatní studenty, a jakmile bude aplikace připravená a v provozu,
      rozšířit ji i mezi další účastníky internetu = zajistit klientelu
- [ ] Vytvořit počáteční databázi a naplnit ji částečně automaticky získanými údaji (Globus, ONO, manuálně Makro)
- [ ] Zajistit GitHub Secrets

## AI assistance

V diplomové práci a vývoji přidružené aplikace je použita asistence AI.
Jedná se o obousměrnou vzájemnou komunikaci, kde je AI agent řízen člověkem
k důkladné rešerši a vývoji aplikace.

Osobně se mi nelíbí AI slop, který se zcela vážně prezentuje jako seriózní
projekt, takže si počínám tak, aby výsledkem této diplomové práce nebyl
další AI slop. AI je použito s jasným cílem a jasně definovanou strukturou
projektu, která není celá vygenerovaná pomocí AI, a v práci není použita
žádná tvůrčí grafika vygenerovaná pomocí AI. AI je použit pouze jako
prostředník k převedení vize do reálného funkčního projektu; samotné konečné
rozhodování a uživatelský vstup jsou výsledkem svobodné vůle autora práce.

Toto je mé transparentní prohlášení o použití AI ve své závěrečné práci.
Veškeré citované zdroje rešerše a referencí k jednotlivým manuálům
a technickým dokumentacím jsou manuálně prověřené, veškerý tvůrčí grafický
obsah pochází buď z importovaných knihoven, nebo je vlastnoručně vytvořen,
a samotný obsah diplomové práce není vygenerovaný umělou inteligencí.
