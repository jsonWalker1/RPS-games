# RPS-games

Tento projekt je jednoduchá implementace hry Rock Paper Scissors, vytvořená s využitím HTML, CSS a JavaScriptu. Hra umožňuje uživatelům hrát proti počítači, sledovat skóre a resetovat výsledky.

Funkce
Hra proti počítači
Uživatel si vybere tah (rock, paper, nebo scissors) a počítač náhodně zvolí svůj tah. Výsledek hry se ihned zobrazí.

Skóre
Skóre (výhry, prohry, remízy) se ukládá do localStorage, takže se neztratí ani po obnovení stránky.

Resetování skóre
Uživatel může resetovat skóre kliknutím na tlačítko "Reset".

Jak hra funguje
Výběr tahu
Kliknutím na jeden z emoji (rock, paper, scissors) zvolíte svůj tah.

Počítačův tah
Počítač generuje náhodný tah pomocí Math.random().

Výsledek hry

Pokud oba zvolí stejný tah, hra skončí remízou.
Pokud váš tah porazí tah počítače (např. rock porazí scissors), vyhrajete.
V opačném případě prohrajete.
Zobrazení výsledků

Výsledek hry (win/loss/tie) se zobrazí na stránce.
Skóre se aktualizuje a uloží do localStorage.

Možné vylepšení
Přidání více vizuálních efektů (např. animace pro vítězství nebo porážku).
Přidání úrovní obtížnosti pro počítač (např. větší pravděpodobnost výhry na vyšší obtížnosti).
Možnost hrát více kol s výsledkovou tabulkou.
