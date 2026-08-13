# Tactical Christmas 2026 PWA

## Käyttöönotto
PWA tarvitsee HTTPS-osoitteen. Helpoin tapa:
1. Pura ZIP.
2. Lataa kaikki tiedostot GitHub Pagesiin, Netlifyyn tai muulle HTTPS-palvelimelle.
3. Avaa sivu Safarissa/Chromessa.
4. iPhone: Jaa → Lisää Koti-valikkoon.
5. Android/Chrome: Asenna sovellus -painike tai selaimen Asenna sovellus.

## Tietojen tallennus
Harjoitus- ja ruokakirjaukset tallentuvat selaimen localStorageen tämän verkkotunnuksen alle.
Ne eivät siirry automaattisesti pilveen.
Käytä sovelluksen JSON-varmuuskopiota ennen selaustietojen tyhjennystä tai puhelimen vaihtoa.

## Offline
Ensimmäisen onnistuneen HTTPS-latauksen jälkeen service worker välimuistittaa sovelluksen,
joten se toimii myös ilman verkkoyhteyttä.
