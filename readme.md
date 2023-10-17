# Verzókezelés

- helyi repo inicializálása
    > git init
- ellenőrzés (van-e különbség a repo és a munkakönyvtár közt)
    > git status
- előkészítjük a helyi repóba való eltárolásra a fájlokat commitol-ásra (a verzió beindexelése megtörténik)
    > git add .
- ellenőrzés
    > git status
- commitolás: eltároljuk az aktuális állapotot, mint egy verzió
    > git commit -m "first commit"
- ellenőrzés
    > git status
- az összes verzió megjelenítése
    > git log
- távoli repo létrehozása: **Github**
- helyi repo és távoli repo összekapcsolása
    > git remote add origin https:// **token@** github.com/pxedq/repoName.git