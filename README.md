# Glow Up Club ✧

App web en català, sense compte, servidor ni base de dades. Desa les dades amb `localStorage` del navegador.

## Provar-la ràpid
- Obre `index.html` al navegador. Les funcions principals funcionen directament.
- Les dades queden en aquell navegador/dispositiu; no es sincronitzen automàticament.
- Exporta periòdicament una còpia des d'Ajustos.

## Instal·lar com a app (PWA)
El manifest i el service worker estan inclosos. Per instal·lar-la i tenir millor suport offline, publica aquesta carpeta en un host HTTPS o serveix-la des de localhost. Després obre-la al mòbil i tria «Instal·lar» / «Afegir a pantalla d'inici».

## Notificacions
L'app pot mostrar notificacions amb permís concedit mentre la pàgina està oberta. Els navegadors poden suspendre pàgines en segon pla i els recordatoris locals no són fiables quan l'app està tancada. Les notificacions push fiables amb l'app tancada normalment necessiten infraestructura de servidor, que expressament no s'inclou aquí.

## Privacitat
No s'envien dades a cap servidor. Si esborres les dades del navegador o canvies de dispositiu, pots perdre-les; fes servir Exportar còpia per guardar-les.
