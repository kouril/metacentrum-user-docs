# Welcome!    

Uvodni stranka Metacentrove dokumentace.

## About

Sem dat strucny popis featur pocitani na gridu. Slouzi k tomu aby si uzivatel vybral, pripadne se ujistil ze vybral spravne. Vlastnosti

- vhodne pro ulohy od-do 
- data jsou zalohovana, ale nikoliv archivovana, a i zalohovani neni bulletproof
- distribuovana infrastruktura
- ruzne stroje s ruznymi vlastnostmi
- ... (co vas jeste napada?)

a dale take

- kym je to zrizovane
- v jakem rezimu bezi support atd., co od nas muzete ocekavat

a dale

- uzivatel potrebuje basic knowledge of Linux CLI


Otazka zda na nejakem vyssim levelu dokumentace vznikne nejaka srovnavaci tabulka, ktera bude charakterizovat jednotlive typy sluzeb (grid vs cloud vs supercomputing vs ...) potom by tento vycet byl zbytecny a uvodni stranka by se omezila na nejakou jedoduchou welcome stranku


Co potrebuju zjistit: 

- kam se budou dava "novinky a vypadky"? Pokud maji byt zde v doku, je potreba jim vymyslet nejaky space. Dala bych je rovnou na titulni stranku, jinde imho nemaji cenu. Vypadky kazdopadne. U novinek (instalace sw apod) by se dalo uvazovat o nejake sekci "What's new" nekde


## Pro devel

- na GitHub v repu CESNET/metacentrum-user-docs
naklonujete si repo, spustite
`(sudo) ./start.sh` a v prohlizeci na `http://localhost:8080` by se mela zobrazit dokumentace

## Na techto strankach se pouziva markdown

**Tucne** se dava do dvou hvezdicek.

> Tohle je blocquote odstavec

Tohle je normalni radek.

    Ctyri spaci znaci blockcode
        ...anebo jde pouzit i Tab

Tohle je zase normalni radek.


Emailova adresa: <anezka.melounova@cesnet.cz>


Ruzne markdownove defaultni warningy, noticy a zvyrazneni... pouzivat budeme <https://www.markdownguide.org/basic-syntax/> a **[jedine ty!](https://www.markdownguide.org/basic-syntax/)**.

Viz napriklad:


> **Note**
> Note please that...

anebo

> **Warning**
> Warning! The page is under construction!

!!! note "note title"

    bla bla bla

!!! warning

    warningy a noty musi byt odsazene ctyrma mezerama!





