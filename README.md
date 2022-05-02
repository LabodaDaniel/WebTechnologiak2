# WebTechnologiak2
Az első órák egyikén megbeszéltek alapján, az én beadandóm Vue JS-ben íródott. A backend Node JS, az autentikációt a Firebase végzi.

Le kell tölteni és feltelepíteni a node js-t.
A poker-app mappában meg kell nyitni a parancssort, majd kiadni a következő parancsokat:

  npm install vue
  npm install
  npm run serve
  
Ezután a poker-app-backend mappában is nyitni kell egy parancssort, majd kiadni ismételten a következő utasításokat:

  npm install
  npm run serve
  
Miután ez kész van, a poker-app mappa parancssorában megjelenő localhost url-en lehet futtatni az alkalmazást.

Regisztrációt követően lehet belépni a weboldalra.
Effektíven úgy érdemes futtatni az alkalmazást, hogy a "Simulate Game" fülön ki kell választani 2 saját lapot, majd 5 további lapot, ami az asztalra kerül.
Ezután a "Calc your chance" gombra kattintva, az alkalmazás kiszámítja a felhasználó nyerési esélyeit, majd a "Calc enemy's chance" kiszámítja az ellenfél esélyeit.
A "Draw diagram" gombra kattintva látható bal oldalt egy oszlopdiagramm, jobb oldalt egy százalékos esély.
