# Casa Mona — smernica o kamerovom systéme

Smernica (index.html) a označenie monitorovaného priestoru (tabula.html, A4 na tlač) publikované cez GitHub Pages
z vetvy main repozitára github.com/yoyanec/casa-mona-kamery-smernica na https://kamery.casamona.sk/ (súbor CNAME;
Cloudflare: proxied CNAME kamery → yoyanec.github.io v zóne casamona.sk, Always Use HTTPS zapnuté).

- Obsah je formálna slovenčina, terminológia GDPR, zákona č. 18/2018 Z. z., usmernení EDPB 3/2019 a usmernenia
  ÚOOÚ 1/2023; pri zmene pravidla zvýšiť verziu, doplniť riadok v tabuľke verzií a dátum účinnosti; tabuľu držať
  v súlade s článkom 7 smernice.
- Štýl: balík dizajnového systému v casa-mona/ (casa-mona.css, písma, logo, licencie) skopírovaný z
  ~/Dev/casa-mona-design-system/dist/balik; po novom builde dizajnového systému ho skopírovať znova. Stránkové štýly sú
  v smernica.css a tabula.css; žiadne inline štýly ani skripty, žiadny build krok.
- QR kód v tabula.html je inline SVG pre https://kamery.casamona.sk/ (vygenerovaný npx qrcode, úroveň H); pri zmene
  adresy vygenerovať znova.
- Zmeny cez feature vetvu a PR; main je publikačná vetva Pages.
