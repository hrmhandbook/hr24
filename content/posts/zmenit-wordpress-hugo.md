---
title: "Proč jsem přešel z Wordpressu k Hugovi."
date: 2020-12-02T20:39:00+01:00
aliases: ["/zmenit-wordpress-hugo"]
tags: ["hugo","wordpress","cms"]
author: "Lukáš"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
disableShare: false
cover:
    image: "/images/wordpress-hugo.jpg"
    alt: "Přechod od Wordpressu k HUGO"
    caption: "Přechod od Wordpressu k Hugo"
    relative: false
comments: false
---

Když chci jednoduchý web, tak obvykle je to Wordpress.  Je to super jednoduchý publikační systém. Funguje to hned, různých rozšíření jsou tisíce, ale nakonec člověk zjistí, že to má i hromadu omezení. Skoro každý webhosting nabízí možnost automatické instalace a obvykle to funguje úplně bez problémů. Má to ale i svá velká omezující ALE.

[Wordpress](https://wordpress.org) je sice zadarmo, ale pokud to s webem myslíte vážně, je nakonec dost drahý. Ekosystém kolem něj si nechá za svoje služby zaplatit a je to tak naprosto v pořádku. Jen je s tím potřeba počítat, že s tou jednoduchostí přijdou i náklady. Bez těch financí v pozadí by nebyl Wordpress tam, kde je dnes.

Nejenom, že rychlý wordpress vyžaduje specificky nastavený hosting, za který se připlácí. I za dobře naprogramovaný plugin nebo šablonu se platí. Bohužel, většinou se platí formou předplatného na rok, což je asi nejoblíbenější forma, jak z klienta vytřískat nějaký výnos navíc.

[Hugo](https://gohugo.io) na to jde trochu jinak. Není to systém, co běží na webu, ale pěkně lokálně vyprodukuje čisté HTML stránky, které se nahrají na web. Je to prostě web, jako ho vymysleli v CERNu a je to dodnes nejrychlejší technologie. Server jenom vezme soubor a pošle ho klientovi. Žádné databáze, žádné PHP skriptování. Jen čisté HTML stránky.
​
Ďábelsky rychlé a funguje to všude. I na vašem iPhonu.
​
**Důležité upozornění**
​
Hugo určitě není pro každého a Wordpress je výborný systém pro publikování. Je to stejné jako všude jinde, žádné štěstí nechodí osamoceno, vždy ho doprovází i nějaká bolest.

Hugo poskytuje hodně svobody, samozřejmě za cenu velkých porodních bolestí. Naopak, Wordpress jede hned, ale měnit směr později dost bolí. To se pak umí postavit do cesty a mít svou hlavu.
​
**Konec důležitého upozornění**
​
## Proč jsem opustil Wordpress
​
Každý projekt si s sebou táhne svou historii. Wordpress byl původně jednoduchý content management systém, který měl všem umožnit, aby si založili vlastní blog. A dodnes je to oblast, ve které Wordpress vyniká. Jen na něm běží odhadem téměř čtvrtina celého světového Internetu. Zbytek bude asi to porno.

Původně toho moc neuměl. Uměl vypsat jednotlivé příspěvky, zařadit je do kategorií a zobrazit archív. Pak se k tomu nabalily tagy (alias štítky) a stránky. A někoho napadlo, že by se v tom daly jednoduše dělat weby. Vyrojily se pluginy a různá témata. Ale ten základní stroj zůstával stejný.

To vedlo k několika zásadním problémům:
​
1. Rychlost
2. Bezpečnost
3. Vlastní vzhled a přátelský přístup
4. Náklady

### Rychlost
Google miluje rychlé weby. Cokoliv je rychlé, tak má výhodu, že se ve výsledcích vyhledávání umístí na předních místech. A Wordpress umí být pekelně pomalý, pokud se neinvestuje do hostingu a různých rozšíření, co se mají chovat jako hodně chytrá cache.

Holý Wordpress je poměrně svižný, s tím, jak se přidávají rozšíření, tak je pomalejší a pomalejší. Za rychlý systém se ovšem platí. Specificky nastavený hosting je vždycky dražší než jiné holé varianty. A často má i svá relativně drastická omezení.

Vyladit Wordpress, aby byl rychlý a svižný je velká věda, kterou ne každý ovládá. Ekosystém samozřejmě nabízí pomoc, ale opět, není to levné a ne každému se to vyplatí. Výsledek samozřejmě není garantovaný.

### Bezpečnost
Wordpress je ekosystém a jako takový je náchylný k bezpečnostním chybám. Nejen v samotném základu, ale každý plugin představuje jisté bezpečnostní riziko. Navíc, je pro útočníky atraktivní, protože je všudypřítomný.

Používal jsem Wordpress v minulosti třikrát a pokaždé se stalo, že byl nakonec napadený a ani jednou se mi nepodařilo udělat trvale udržitelnou léčbu. A zase, speciální hosting téhle bolesti zbaví, ale opět - platí se za to. Třebas [WPEngine](https://wpengine.com), kde jsem byl spokojený, se o to staral, ale není to vůbec laciný hosting. Jako vždy, za kvalitu se platí.

Taky platí jednoduchá zásada - čím méně pluginů, tím bezpečnější a rychlejší systém je. A to jde trochu proti myšlence, že rozšíření dělají web zajímavějším pro návštěvníky.

### Vlastní vzhled a přátelský přístup
Existují tisíce šablon a témat pro Wordpress. Od těch výborných po ty šílené. Udělat si svou vlastní, to chce hodiny a hodiny studia. Navíc, každý plugin si může přidat svůj vlastní styl a nakonec je to guláš, ve kterém se každý nevyzná.

Najít designera, který udělá šablonu nebo téma, není složité, ale opět platí se za to. A udělat si úpravy na koleně, to fakt hodně bolí. Jak systém rostl, tak složitost stylů narostla a není snadné pochopit, jak věci dohromady fungují.

Teoreticky to pokaždé vypadá snadno, v YouTube videích to je práce na pár minut, ve skutečnosti jsou to dny a dny pořádné dřiny.

A když to toho ještě vstoupí různé page builders, tak to začne být hodně zajímavé. Ono, udělat web jako stránku na blogu, to chce hodně kreativní myšlení. Hodně z nás to zvládlo, ale já to teda vzdal.

### Náklady
Wordpress je dnes platforma, nad kterou stojí celý byznys. Co bylo dřív zdarma, už dávno nejsou čistě nadšenecké projekty. Stalo se z toho seriózní podnikání a je to jenom dobře. Proč si lepit věci na koleně, když profík dokáže dodat hotové řešení. Jen je to drahé pro domácí nadšence.

Dnes se platí za vše:
​
- kvalitní hosting,
- prémiovou šablonu,
- bezpečnost,
- SEO,
- emailing.

Hosting obvykle nabízí nějaký základní startovací balíček, kde je relativně slušný počet návštěvníků za měsíc. Stačí ovšem poskočit a další tarif je klidně i 4x dražší. A to už peněženku slušně provětrá.

A co je zdarma, to je omezené a nebo se s tím táhne nějaká omezující podmínka. Například, že plugin dostane přístup k vašim datům, což je dnes velmi cenná komodita. Například za YoastSEO se platí, RankMath je zdarma, ale řekne si o to, že chce vidět na data z Google Search Console. Takže může vydolovat cenná data o tom, které stránky a která klíčová slova na webu letí.

Taky se všichni učili u Bati, takže většina rozšíření má cenu nastavenou na pěkných 99 dolarů ročně a to po slevě, která je v platnosti prakticky neustále. Prémiové šablony začínají na 49 dolarech, ale i 89 dolarů za rok je vcelku běžných.

A to jsou asi zásadní důvody, proč jsem si řekl, že je čas zkusit něco jiného.

## Co se mi zatím na Hugovi líbí
Chtěl jsem zkusit něco rychlejšího a levnějšího. A kupodivu, Github Pages jsou zdarma a Netlify taky. Měl jsem na výběr mezi Hugem a [Jekyllem](https://jekyllrb.com). Jekyll se mi nedařilo nainstalovat na mém Macovi a Hugo běžel na první dobrou, tak jsem zůstal u něj. Já mám prostě na to Ruby nějakou smůlu.

Stačilo je vytvořit repozitář na GitHubu, propojit s [Netlify](https://www.netlify.com), koupit doménu a bylo téměř hotovo. Zatím jsem spokojený, skoro nadšený. Šablony jsou tak snadné, že dokážu sám přijít na to, jak si ji přiohnout k obrazu svému. Psaní v Markdown je v Nextcloudu tak jednoduché.

Stačí něco napsat, uložit a Hugo hned provede překlad a změna je okamžitě vidět v prohlížeči. A když je člověk spokojený, tak jen pošle vše na Github a za momentík se to ukáže i na webu. Jednodušší to být asi nemůže.

Teda, cestou tam samozřejmě bylo pár ... zakopnutí, ale o těch více příště.