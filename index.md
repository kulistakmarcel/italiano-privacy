---
layout: default
---

# Zásady ochrany osobních údajů — Italiano

**Účinné od:** 24. 10. 2026 (předchozí verze 25. 8. 2026)
**Provozovatel (správce údajů):** Marcel Kulišťák
**Kontakt:** italiano.vibe.app@gmail.com

---

## 1. Úvod

Tyto zásady popisují, jaké údaje aplikace **Italiano** (dále „aplikace") zpracovává,
proč, jak dlouho a jaká máš práva. Zpracování probíhá v souladu s Nařízením (EU)
2016/679 (GDPR).

Aplikace slouží k výuce italštiny. **Nezobrazuje reklamu, nesleduje tvoje chování
napříč aplikacemi a nepoužívá reklamní identifikátor.** Anonymní statistiku
používání posílá jen tehdy, když ji sám povolíš (sekce 2).

## 2. Jaké údaje zpracováváme

- **Jméno profilu** — text, který sám zadáš při vytvoření profilu. Může, ale nemusí
  být tvým skutečným jménem; volba je na tobě.
- **Studijní data** — postup v lekcích, skóre, body za odpovědi, kategorie naučených
  slovíček, stav dokončení lekcí a zkoušek.
- **Nastavení aplikace** — automatické čtení, tempo čtení, režim rozpoznávání řeči
  (online / jen z telefonu), jazyk rozhraní a rod, ve kterém tě aplikace oslovuje
  (mužský, ženský, nebo neutrální — volba je na tobě).
- **Anonymní identifikátor** — aplikace se k cloudu přihlašuje anonymně (Firebase
  Anonymous Auth). Tento identifikátor je náhodný a **není** navázán na e-mail,
  telefonní číslo ani jméno.
- **Technické údaje nezbytné pro zabezpečení** — při komunikaci se serverem se
  zpracovává **IP adresa** tvého zařízení a **ověřovací tokeny** (Firebase App
  Check, na Androidu přes Play Integrity, na iPhonu přes App Attest). Slouží
  výhradně k tomu, aby se k datům nedostal někdo, kdo nepoužívá naši aplikaci.
- **Anonymní statistika používání (jen se souhlasem)** — když ji povolíš (okno při
  spuštění nebo Nastavení → Soukromí a data), aplikace posílá do **Google Analytics
  for Firebase** počty událostí: dokončená lekce Slovní zásoby, Gramatiky a školy,
  dokončený den denního plánu, dokončené místo v Montelingua (úroveň a počet hvězd),
  výsledek opakování slovíček (kolik slov, kolik bez chyby) a stav zásobníku.
  Neposílá se jméno profilu, odpovědi ani text, nepoužívá se reklamní identifikátor
  a údaje se nespojují s tvým profilem. Firebase k událostem přidává technické údaje
  zařízení (model, verze systému a aplikace, země odvozená z IP) a náhodný
  identifikátor instalace. Souhlas můžeš kdykoli odvolat v Nastavení.

**Nezpracováváme** e-mail, telefonní číslo, polohu, kontakty ani platební údaje.

*(Až aplikace zavede placené předplatné, zásady se rozšíří o údaje související
s platbou, které zpracovává obchod Google Play / App Store.)*

## 3. Mikrofon a rozpoznávání řeči

Aplikace obsahuje trenažér výslovnosti a možnost odpovědět v testu hlasem.

- **Mikrofon se zapíná jen tehdy, když sám podržíš tlačítko** („Vyslov" u slovíčka,
  „Řekni to" v testu). Nikdy neposlouchá na pozadí.
- Nahrávka se předá **systémové službě rozpoznávání řeči** tvého telefonu — na
  Androidu Google, na iPhonu Apple. Ta ji převede na text a aplikace pracuje už jen
  s tím textem.
- **Aplikace nahrávku neukládá, neodesílá na naše servery ani ji nikam nekopíruje.**
  Žádné servery pro zvuk neprovozujeme.
- V nastavení **Nastavení → Mluvení → Rozpoznávání → „Jen z telefonu"** zpracování
  probíhá výhradně v zařízení a zvuk ho neopouští. Vyžaduje to stažený jazykový
  balík italštiny, který se stahuje v nastavení telefonu.

**Odvolání souhlasu.** Použití mikrofonu stojí na tvém souhlasu a ten můžeš
**kdykoli odvolat** — odebráním oprávnění k mikrofonu v nastavení telefonu
(Android: Nastavení → Aplikace → Italiano → Oprávnění; iPhone: Nastavení →
Italiano → Mikrofon). Odvolání nemá vliv na zákonnost zpracování před odvoláním
a zbytek aplikace funguje dál beze změny.

Zpracování nahrávky se řídí podmínkami provozovatele systémové služby:
Google — <https://policies.google.com/privacy>, Apple — <https://www.apple.com/legal/privacy/>.

## 4. Účel a právní základ

| Co | Proč | Právní základ (GDPR) |
|---|---|---|
| Ukládání postupu na zařízení a jeho záloha do cloudu | aby aplikace fungovala, pamatovala si, kde jsi skončil, a abys o postup nepřišel při výměně nebo obnově telefonu | **čl. 6 odst. 1 písm. b)** — plnění smlouvy (poskytnutí služby, o kterou jsi požádal instalací a používáním aplikace) |
| Zpracování hlasu | abychom mohli vyhodnotit tvou výslovnost | **čl. 6 odst. 1 písm. a)** — souhlas, který dáváš podržením tlačítka a systémovým povolením mikrofonu |
| Ověřovací tokeny a IP adresa | aby se k datům nedostal někdo, kdo nepoužívá naši aplikaci | **čl. 6 odst. 1 písm. f)** — oprávněný zájem na zabezpečení služby proti zneužití a neoprávněnému přístupu |
| Anonymní statistika používání | abychom věděli, které části aplikace lidi používají a dokončují, a mohli ji zlepšovat | **čl. 6 odst. 1 písm. a)** — souhlas (okno při spuštění, odvolání v Nastavení) |

## 5. Kde jsou údaje uložené

- **Na tvém zařízení** — primární úložiště.
- **V cloudu** přes službu **Google Firebase (Cloud Firestore)**, v regionu
  **`eur3` (Evropská unie)** — záloha postupu pod anonymním identifikátorem.
- **Firebase Authentication** (anonymní přihlášení) běží na infrastruktuře Google
  ve **Spojených státech** — viz sekce 7.

## 6. Příjemci / zpracovatelé (třetí strany)

- **Google (Firebase)** — Cloud Firestore (databáze), Firebase Authentication
  (anonymní přihlášení), Firebase App Check (ochrana proti zneužití aplikace),
  Google Analytics for Firebase (anonymní statistika, jen se souhlasem).
  <https://policies.google.com/privacy>
- **Google, resp. Apple (rozpoznávání řeči)** — podle platformy a tvého nastavení;
  viz sekce 3.

Tyto subjekty vystupují jako **zpracovatelé** a údaje zpracovávají na základě svých
smluvních podmínek.

Písma použitá v aplikaci jsou její součástí a **nestahují se odnikud** — aplikace
kvůli vzhledu nikam nevolá.

## 7. Předávání údajů mimo EU

**Studijní data** (jméno profilu, postup, nastavení) jsou uložena v databázi
Cloud Firestore v **Evropské unii** a při běžném provozu EU neopouštějí.

K předání do **Spojených států** ale dochází u těchto částí služby:

- **Firebase Authentication** — služba, která vydává tvůj anonymní identifikátor,
  **neumožňuje volbu regionu** (na rozdíl od databáze). Nemůžeme proto zaručit,
  že se údaje spojené s přihlášením (identifikátor, IP adresa) zpracovávají
  v EU, a je nutné počítat s jejich předáním do USA. Týká se to každého
  spuštění aplikace, ne jen výjimečných situací.
- **Firebase App Check** — ověřovací tokeny.
- **Google Analytics for Firebase** — anonymní statistika používání, jen pokud jsi
  ji povolil.
- **Rozpoznávání řeči v online režimu** — nahrávku zpracovává Google nebo Apple
  podle jejich vlastní infrastruktury. Přepnutím na „Jen z telefonu"
  (Nastavení → Mluvení) tomuto předání zcela zabráníš.

**Záruky pro předání (čl. 46 GDPR).** Příjemcem je společnost Google LLC, která je
certifikována v rámci **EU-U.S. Data Privacy Framework** (rámec, pro který Evropská
komise vydala v roce 2023 rozhodnutí o odpovídající ochraně). Google zároveň
uplatňuje **standardní smluvní doložky** schválené Evropskou komisí. Podrobnosti:
<https://business.safety.google/privacy/> a <https://www.dataprivacyframework.gov/>.

## 8. Doba uchování a mazání

Údaje uchováváme, **dokud je sám nesmažeš**. Nemáme nastavené automatické mazání
neaktivních účtů — aplikace tedy tvůj postup nedrží po nějakou pevnou lhůtu, ale
ani ho sama od sebe nezahodí.

**Výjimka — anonymní statistika:** události v Google Analytics se mažou
automaticky, nejpozději po **14 měsících**. Protože nejsou spojené s tvým profilem,
nedokážeme je dohledat ani smazat jednotlivě. Odvoláním souhlasu nebo smazáním
účtu se v telefonu smaže identifikátor statistiky a další události se už
neposílají.

**Smazání v aplikaci:** záložka **Profil → „Smazat účet a data"**. Nevratně se
odstraní lokální data, dokument s tvým postupem v cloudové databázi i anonymní
účet. Data se mažou jako první — kdyby se to nepodařilo, aplikace to oznámí a nic
nesmaže ani lokálně, aby nevznikl stav „lokálně smazáno, v cloudu zůstalo".

**Pozor:** samotné odinstalování aplikace cloudová data nesmaže. Pokud chceš mít
jistotu, použij nejdřív „Smazat účet a data".

**Smazání na žádost:** pokud už aplikaci nemáš nainstalovanou nebo se ti mazání
nepodařilo, napiš na **italiano.vibe.app@gmail.com** a data smažeme. Vyřídíme to
nejpozději do 30 dnů. Bez identifikátoru zařízení nedokážeme tvá data v databázi
dohledat, proto do žádosti prosím uveď, kdy a na jakém zařízení jsi aplikaci
používal.

## 9. Tvoje práva (GDPR)

Máš právo na:

- **přístup** ke svým údajům,
- **opravu** nepřesných údajů,
- **výmaz** („právo být zapomenut") — přímo v aplikaci přes „Smazat účet a data",
- **omezení** zpracování a **námitku** proti němu,
- **přenositelnost** údajů,
- **odvolání souhlasu** u zpracování hlasu (viz sekce 3) a u anonymní statistiky
  (Nastavení → Soukromí a data).

Pro uplatnění práv nebo dotazy nás kontaktuj na e-mailu uvedeném v sekci 14. Máš
také právo podat stížnost u **Úřadu pro ochranu osobních údajů** (<https://uoou.gov.cz>).

## 10. Automatizované rozhodování

Aplikace **neprovádí automatizované rozhodování ani profilování** ve smyslu
čl. 22 GDPR. Vyhodnocení odpovědí a doporučení, co procvičovat, slouží výhradně
k výuce a nemá pro tebe žádné právní ani obdobně významné účinky.

## 11. Děti

Aplikace je určena **obecnému publiku od 15 let**. Tato hranice vychází z českého
adaptačního zákona ke GDPR (zákon č. 110/2019 Sb.), podle kterého může dítě udělit
souhlas se zpracováním svých údajů u služeb informační společnosti **od 15 let**.

Pokud aplikaci používá mladší dítě, souhlas — zejména s použitím mikrofonu —
uděluje jeho zákonný zástupce.

## 12. Zabezpečení

- **Firebase App Check** — ověřuje, že požadavky posílá pravá aplikace.
- **Pravidla Firestore vázaná na vlastníka dat** — nikdo se nedostane k datům
  někoho jiného.
- **Šifrování přenosu (HTTPS) i úložiště** — zajišťuje Google.

## 13. Změny zásad

Zásady můžeme aktualizovat. O podstatných změnách budeme informovat v aplikaci nebo
v popisu v obchodě. Aktuální verze je vždy dostupná na adrese:

<https://kulistakmarcel.github.io/italiano-privacy/>

## 14. Kontakt

Marcel Kulišťák, e-mail: **italiano.vibe.app@gmail.com**
