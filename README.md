# victorthelin.github.io

Bara två små filer som låter QR-koden på TV:n öppna Homeplay-appen direkt i mobilen
(i stället för att gå via webbläsaren):

- `.well-known/apple-app-site-association` – iPhone (universella länkar)
- `.well-known/assetlinks.json` – Android (App Links)

Båda gäller bara adressen `victorthelin.github.io/homeplay/tv.html?k=…` (sidan finns i
[VictorThelin/homeplay](https://github.com/VictorThelin/homeplay)). Saknas appen öppnas sidan som vanligt.
Inga hemligheter här: bara appens id (se.tittarn.tv) och signeringsnyckelns offentliga fingeravtryck.

`.nojekyll` behövs för att GitHub Pages ska lämna ut mappen `.well-known`.
