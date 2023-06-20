
udělat něco co funguje
velmi težké, unreal engine 5



Úvod:
Tato dokumentace popisuje vývoj a implementaci projektu v Unreal Engine 5, ve kterém hráč prochází mapou a hledá terče. Cílem je najít a střílet všechny terče a úspěšně dokončit hru. Projekt se zaměřuje na využití pokročilých vizuálních efektů a nových funkcí poskytovaných Unreal Engine 5.

I. Návrh hry:

Cíl hry:
Hráč má za úkol najít a zničit všechny terče na mapě.

Mechanika hry:
a) Pohyb hráče: Hráč může ovládat postavu pomocí klávesnice nebo gamepadu a pohybovat se po mapě.
b) Hledání terčů: Na mapě jsou umístěny terče, které hráč musí najít.
c) Střelba: Hráč může střílet na terče pomocí stisknutí určeného tlačítka na klávesnici nebo gamepadu.
d) Zničení terče: Když hráč zasáhne terč, terč se zničí a hráč obdrží bodové skóre.
e) Hra konečná: Hra končí, když hráč zničí všechny terče na mapě.

Vizuální styl:
a) Použití Unreal Engine 5: Projekt využívá nové funkce Unreal Engine 5, jako jsou pokročilé vizuální efekty, osvětlení a textury.
b) Mapa: Mapa je navržena s důrazem na detaily a vizuální atraktivitu. Může obsahovat různé prostředí, například město, les nebo jeskyně.

II. Implementace:

Vytvoření mapy:
a) Vytvoření terčů: Na mapě jsou umístěny různé terče ve strategických pozicích.
b) Nastavení prostředí: Vytvoření prostředí a atmosféry, která odpovídá zvolenému vizuálnímu stylu.

Implementace hráčské postavy:
a) Ovládání postavy: Implementace ovládání hráče pomocí klávesnice nebo gamepadu.
b) Pohyb hráče: Implementace plynulého pohybu hráče po mapě.
c) Střelba: Implementace střelby na terče po stisknutí určeného tlačítka.

Implementace terčů:
a) Vytvoření terčů: Implementace různých typů terčů s různými vlastnostmi.
b) Detekce zásahu: Implementace detekce zásahu na terče po střelbě hráče.
c) Zničení terče: Implementace efektu zničení terče a přičítání bodů hráči.

Implementace logiky hry:
a) Správa terčů: Sledování počtu zbývajících terčů na mapě.
b) Konec hry: Detekce, zda hráč zničil všechny terče a ukončení hry.

III. Testování a ladění:

Testování herní mechaniky:
a) Ověření, zda hráč může správně ovládat postavu a střílet na terče.
b) Testování zásahů na terče a jejich správného zničení.

Testování herního prostředí:
a) Ověření vizuálních efektů a celkové atmosféry hry.
b) Testování plynulého pohybu hráče po mapě.

IV. Závěr:
