---
name: skills/czech-docs
description: Píše nebo upravuje českou technickou dokumentaci a komentáře ke kódu tak, aby byly přirozené, střídmé a terminologicky jednotné. Použij při tvorbě nebo revizi českých textů, které mají působit věcně bez marketingových obratů a typických znaků strojového textu.
---

# Účel

Vytvářej českou dokumentaci a komentáře, které přesně popisují skutečné chování kódu nebo systému. Zachovej význam zdroje, místní kontext a zavedený styl projektu. Doplňuj jen to, co lze opřít o zdrojový kód, konfiguraci, testy nebo zadaný kontext.

# Postup

1. Urči, komu je text určen, co má čtenář pochopit a kde bude text použit. Rozliš dokumentaci pro uživatele, vývojáře, správce a krátký komentář přímo u kódu.

2. Získej potřebná fakta. Projdi relevantní kód, názvy rozhraní, testy a existující dokumentaci. Když údaj nelze ověřit, vyjádři nejistotu nebo jej vynech.

3. Při vkládání nového textu do existujícího textu zachovej původní význam, strukturu, terminologii, tón a členění co nejvěrněji, pokud to není v rozporu s pravidly tohoto skillu. Uprav jen místa nutná pro návaznost, pravdivost, srozumitelnost nebo odstranění porušení těchto pravidel.

4. Sepiš si hlavní termíny. Pro každý pojem zvol jedno české označení a drž se ho v celém výstupu. Technické názvy, identifikátory, příkazy a citované názvy ponech v přesném znění.

5. Napiš první verzi věcně. Používej běžná česká slova a konkrétní slovesa. Každý odstavec nebo komentář by měl mít jasný účel. Délku přizpůsob významu, ne předem danému vzoru.

6. Uprav styl. Nahraď obecné fráze přesným popisem. Marketingový výraz použij jen tehdy, když jej uživatel výslovně požaduje. Odborný termín ponech, pokud označuje přesný pojem a není použit jako propagační obrat. Vynech klišé, samoúčelné zesilování a opakované slovní výplně.

# Dokumentace

Uveď účel, chování, vstupy, výstupy, omezení a důležité chybové stavy podle potřeby. Odděl ověřená fakta od předpokladů a doporučení. Příklad přidej pouze tehdy, když zpřesní použití nebo odhalí důležitou hranici chování.

Tvrzení přizpůsob dostupným důkazům. Slova jako „vždy“, „nikdy“, „zaručuje“ nebo „bez výjimky“ použij jen při skutečně ověřeném rozsahu. Neodvozuj vlastnosti, které ze zdroje neplynou.

# Komentáře ke kódu

Komentář vysvětluje důvod, invariant, vedlejší účinek, smlouvu rozhraní nebo omezení, které není zřejmé ze samotného kódu. Nepřepisuj v něm řádek kódu vlastními slovy. Udržuj komentář blízko vysvětlovaného místa a při změně chování ověř, zda je stále pravdivý.

Jeden komentář má jednu hlavní myšlenku. Krátký komentář může být úsporný, delší komentář rozděl podle logiky vysvětlení. Pokud z komentáře vznikne návod, přesuň jej do vhodné dokumentace.

# Jazyk a interpunkce

V próze dávej přednost tečkám a čárkám. Spojovník, pomlčku a středník použij jen tehdy, když bez nich vznikne ztráta významu nebo syntaktická nejasnost. Nejdříve zkus větu rozdělit, přeformulovat nebo použít běžnou českou interpunkci. Technickou syntaxi v kódu, názvech, příkazech, odkazech a citovaných textech neměň jen kvůli tomuto pravidlu.

Střídej přirozeně délku vět, ale nevytvářej pravidelný rytmus. Vyhýbej se zrcadlovým konstrukcím, mechanickým trojicím a opakování stejného začátku vět. Vol jedno přesné slovo místo několika podobných slov. Zachovej stejný termín pro stejný pojem, i když by synonymum znělo pestřeji.

Odstraň nadužívaná spojovací a hodnotící slova. Odborný termín ponech, i když se v textu opakuje, protože přesnost je důležitější než slovní pestrost.

# Závěrečná kontrola

Před odevzdáním proveď samostatný kontrolní průchod v tomto pořadí:

1. Porovnej text se zdrojem a ověř význam každého tvrzení.

2. Projdi termíny a zkontroluj, že stejný pojem nemá bezdůvodně více označení.

3. Vyhledej obecné fráze, marketingová slova, klišé, nadužívaná nápadná slova, mechanické opakování, zrcadlové konstrukce, mechanické trojice a zbytečné zesilování. Odborný termín ponech jen tehdy, když stále označuje stejný pojem.

4. Zkontroluj spojovníky, pomlčky a středníky v próze. Každá výjimka musí mít jasný významový nebo syntaktický důvod.

5. Ověř, že komentáře vysvětlují něco, co není patrné z kódu, a že dokumentace nepřisuzuje systému neověřené vlastnosti.

Pokud je dostupná delegace, předej hotový text a nutný zdrojový kontext nezávislému subagentovi. Požádej jej, aby vrátil pouze konkrétní nálezy s místem, důvodem a návrhem opravy. Nepředávej mu očekávaný výsledek ani vlastní závěry. Zapracuj jen opodstatněné nálezy a potom kontrolu zopakuj. Když delegace není dostupná, proveď druhý průchod se stejnými body s odstupem od psaní.
