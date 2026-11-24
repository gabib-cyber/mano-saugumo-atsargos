# Mano saugumo atsargos

Lietuviška, neprisijungus veikianti asmeninių atsargų PWA programėlė.

## Kas įtraukta
- 2 žmonėms ir 72 valandoms skirtas pradinis atsargų sąrašas (kiekiai redaguojami).
- Atsargų apskaita: tikslinis kiekis, turimas kiekis ir trūkumas.
- Atskiras išvykimo krepšio sąrašas.
- Šeimos pasiruošimo kontrolinis sąrašas: dokumentai, susitikimo vieta, kontaktai, augintiniai ir transportas.
- Duomenų saugojimas naršyklės vietinėje saugykloje.
- JSON atsarginės kopijos eksportas ir atkūrimas.
- Service worker talpykla darbui be interneto.

## Svarbu dėl iPhone
PWA diegimui iPhone reikia HTTPS svetainės. Vien ZIP ar HTML failo atsisiuntimas savaime neįdiegia programėlės ir negarantuoja patikimo darbo neprisijungus.

1. Įkelk šio aplanko failus į HTTPS statinį hostą (pvz., GitHub Pages).
2. iPhone atidaryk svetainės adresą per Safari ir palauk, kol puslapis pilnai užsikraus.
3. Pasirink Safari „Bendrinti“ → „Į pradžios ekraną“ → „Pridėti“.
4. Atidaryk programėlę iš pradžios ekrano ir patikrink, ar ji veikia įjungus lėktuvo režimą.
5. Reguliariai eksportuok atsarginę kopiją į programėlę „Failai“.

## Duomenų privatumas
Duomenys saugomi tame pačiame įrenginyje naršyklės localStorage. Jie nėra siunčiami į serverį. Išvalius svetainės duomenis arba pašalinus naršyklės duomenis, jie gali būti prarasti, todėl eksportuok atsarginę kopiją.

## Pastaba apie kiekius
Pradiniai kiekiai yra redaguojami planavimo orientyrai, o ne individuali medicininė ar civilinės saugos rekomendacija. Pritaikyk juos savo šeimos poreikiams, mitybai, sveikatai, sezonui ir oficialioms Lietuvos rekomendacijoms.
