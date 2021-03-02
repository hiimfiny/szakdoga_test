# szakdoga_test

Jelenleg a futtatáshoz két terminál szükséges.
Az elsőben a peerjs segítségével létesítünk kapcsolatot 2 felhasználó között.
Első futtatáskor ezt telepíteni kell a
  npm i -g peer
paranccsal, majd ezután
  peerjs --port 3001
paranccsal létrejön a peer server.
A másik terminálban, első futtatáskor 
  npm install
paranccsal letöltjük a szükséges dependencyket, majd
  npm start
paranccsal indítjuk.
Két böngészőben a localhost:3000-t beírva a saját kameránk képt kellene látnunk.
Az oldalhoz generálódott egy hosszú kód a / után. Ez jelzi az adott felhasználó szobájának az ID-jét.
Az egyik böngészőből a másikba másolva az ID-t, becsatlakozunk a másik böngésző szobájába, és meg kell jelennie mégegyszer a kameránk képének.
