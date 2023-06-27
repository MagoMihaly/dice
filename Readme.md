# GIT verziókezelés 

- Helyi REPO inicialízálás :
  > git init 

- A helyi REPO ellenőrzés :
  > git status 

- Előkészítjük a commit -olásra , stage (indexelés , beazonosítás)
  > git add .

- Ellenőrzés (OPCIONÁLIS)
  > git status (itt zöld lesz a cmdben az indexelt)

- Commit fázis ,verzió létrehozás : 
  > git commit -m "megjegyzés mi változott"

- Távoli REPO létrehozása (GitHub-on)

- Összekapcsolni a helyi REPO-t a távoli REPOval (GitHub)
  > git remote add origin https://token@github.com/MagoMihaly/test.git

- Meghatározni az ágat "Branch" a távoli REPO-ban :
  > git push -u origin master  (csak legelső alkalommal kell -u oringin master)

  > git push (minden további alkalommal)

- Token beillesztés (előszőr vágólapra kimásolni)
  > csak jobb klikk és ENTER (azonosítás)

## Publikálás 

- A publikálandó fájl neve: index.html

- Setting > Pages > Branch (None -> Master) > Save!

- Action menűpontban látható a publikálási folyamat!

