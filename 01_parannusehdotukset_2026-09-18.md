# Claude-parannusehdotukset: Turvallinen sote-kuljetus MASTER 3.0

**Tarkastuspäivä:** 18.9.2026
**Tarkastuksen kohde:** `Juhaanttila156/sote-koulutus-master` (MASTER 3.0, 15.8.2026, AAC-täydennys 23.8.2026)
**Tekijä:** Claude (Anthropic)
**Periaate:** Alkuperäistä materiaalia ei muokattu. Tämä tiedosto sisältää vain lisäys- ja tarkennusehdotuksia erilliseen repositorioon.

## Yleisarvio

Materiaali on poikkeuksellisen hyvin auditoitu: lähdeauditointi (`08_lahteet/02_lahdeauditointi_2026-08-15.md`) osoittaa systemaattista lähdekritiikkiä, ajantasaisia lakiviittauksia (vammaispalvelulaki 675/2023, CER-laki 310/2025) ja tarkkaa rajanvetoa tutkimusnäytön ja käytännön ohjeen välillä. Alla olevat ehdotukset ovat täydennyksiä, eivät korjauksia virheisiin.

## 1. Kriittiset huomiot USA-markkinalle myöhempää käännöstä varten

Nämä eivät vaadi muutoksia suomenkieliseen versioon nyt, mutta kannattaa kirjata muistiin käännösvaihetta varten, koska ne eivät ole suoria käännöksiä vaan sisällöllisiä korvauksia:

| Suomalainen elementti | USA-vastine, joka tarvitaan käännösvaiheessa | Miksi tämä ei ole pelkkä käännös |
|---|---|---|
| Hätänumero 112 | 911 | Eri numero, ja USA:ssa myös alueellisia poikkeuksia (esim. jotkin osavaltiot/yliopistoalueet) |
| ERC 2025 -elvytysohje | American Heart Association (AHA) / ILCOR-pohjainen ohje | ERC ja AHA eroavat pienissä yksityiskohdissa (mm. kouluttajasertifiointikäytännöt); AHA on USA:n käytännön standardi |
| Rikoslaki 39/1889 (hätävarjelu, pakkotila) | Osavaltiokohtainen itsepuolustus- ja "duty to act" -lainsäädäntö | USA:ssa ei ole yhtä liittovaltion tason vastaavaa; jokaisen osavaltion laki on tarkistettava erikseen |
| Työturvallisuuslaki 738/2002 | OSHA-säännökset ja osavaltiokohtainen työturvallisuuslainsäädäntö | Liittovaltio + osavaltio -kaksitasoisuus, ei suoraa vastaavuutta |
| Vammaispalvelulaki 675/2023, Asiakaslaki 812/2000 | ADA (Americans with Disabilities Act), Olmstead-päätös, osavaltiokohtainen Medicaid-kuljetussääntely (esim. Minnesotan 8840-säädökset) | USA:n vammaispalvelujärjestelmä on hajautettu osavaltioittain, ei valtakunnallinen kuten Suomen sote |
| WHO ICD-11 -diagnostinen kehys | DSM-5-TR (American Psychiatric Association) | **Tämä on tärkein yksittäinen huomio.** USA:n kliininen ja koulutuksellinen käytäntö nojaa pääosin DSM-5-TR:ään autismikirjon ja älyllisen kehitysvammaisuuden diagnostiikassa, ei ICD-11:een. Diagnoosikriteerit ja kynnysarvot eivät ole identtiset. Käännösvaiheessa koko diagnostinen viitekehys (ei vain sanasto) on käytävä läpi rinnakkain DSM-5-TR:n kanssa. |
| Tietosuojalaki / GDPR-pohjaiset viittaukset | HIPAA ja osavaltiokohtainen tietosuojalainsäädäntö | GDPR:ää ei sovelleta USA:ssa; HIPAA kattaa terveystiedon eri tavalla kuin GDPR |

## 2. Sisällölliset lisäysehdotukset (hyödyllisiä myös suomenkieliseen versioon)

Näitä nousi esiin vertailtaessa yhdysvaltalaisia ja EU-tason kuljetuskoulutuskäytäntöjä:

- **Kohtauksen (epilepsia) tunnistamisen erillinen ensiapumoduuli.** Yhdysvaltalaisissa kuljetuskoulutuksissa (esim. Epilepsy Foundationin Seizure Recognition and First Aid -sertifiointi) tämä on usein oma erillinen sertifiointinsa. Materiaalissanne kohtaus käsitellään osana laajempaa hätätilanneosiota (`04_hatatilanteet/01`), mikä on sinänsä toimiva ratkaisu, mutta erillinen, helposti kerrattava pikaohje/kortti kohtauksen tunnistamiseen ja toimintaan voisi olla hyödyllinen lisä kouluttajan käsikirjaan.

- **Strukturoitu matkustajan taitoarviointityökalu.** Yhdysvalloissa käytetään mm. Paratransit Skills Assessment (PaSA) -tyyppisiä työkaluja arvioimaan, minkä tyyppistä kuljetuspalvelua (reunalta reunalle, ovelta ovelle, ovelta läpi oven, käsi kädestä) henkilö tarvitsee. Materiaalissanne on vahva yksilöllisen kuljetusprofiilin ajattelu, mutta konkreettinen, lomakemuotoinen taitoarviointityökalu (`06_kouluttajan_kasikirja/02_skenaariot_ja_lomakkeet.md` olisi luonteva paikka) voisi tehdä arvioinnista systemaattisemman ja vertailukelpoisemman organisaatioiden välillä.

- **Onnettomuustilanteen evakuointi erityisryhmille.** USA:n koulutusstandardeissa (esim. Minnesotan osavaltion 8840.5910) mainitaan erikseen "crash and breakdown procedures" ja matkustajien evakuointi onnettomuustilanteessa, mukaan lukien pyörätuolin käyttäjän evakuointi ajoneuvosta hätätilanteessa. Tämä konkreettinen aihe ei näyttänyt saavan omaa alaotsikkoaan `03_ennakointi_ja_kuljetusturvallisuus`-osiossa — voisi olla arvokas lisäys.

- **"Näkymättömän vamman" käsitteen eksplisiittinen nimeäminen.** Materiaali käsittelee asiaa sisällöllisesti (esim. autismikirjon ja kommunikaation osiot), mutta yhdysvaltalaisissa ja brittiläisissä koulutuksissa käytetään usein tietoisesti termiä "invisible disability" omana opetettavana käsitteenään, jotta kuljettaja ymmärtää, ettei tuen tarve aina näy päällepäin. Tämä voisi olla hyödyllinen oma lyhyt kappale `01_ydin/02_kohtaaminen_luottamus_ja_toimijuus.md`-tiedostoon.

- **EU-tason vertailukehys.** EU-asetus 181/2011 teki vammaisuustietoisuuskoulutuksesta pakollisen linja-autoliikenteen kuljettajille EU:ssa vuoteen 2018 mennessä, ja UITP/IRU/EDF ovat julkaisseet yhteisen käytännön oppaan. Tämä voisi olla hyödyllinen kansainvälinen vertailukohta lähdeauditointiin tai hankekuvaukseen (`07_varautuminen_ja_hanke/02_hankekuvaus.md`), erityisesti jos materiaalia myöhemmin markkinoidaan myös muualle Eurooppaan kuin Suomeen.

## 3. Terminologinen huomio identiteettikielestä

Yhdysvaltalaisessa vammaisyhteisössä (erityisesti autismikirjon sisällä) käydään aktiivista keskustelua "person-first language" (esim. "person with autism") vs. "identity-first language" (esim. "autistic person") -välillä, ja monet autismikirjon aikuiset itse suosivat jälkimmäistä. Tämä poikkeaa siitä, mikä on ollut virallinen suositus monissa ammatillisissa yhteyksissä. Materiaalinne käsittelee itsemääräämisoikeutta ja asiakkaan omaa toimijuutta hyvin, joten käännösvaiheessa kannattaa harkita, kysytäänkö/mainitaanko tämä terminologinen valinta eksplisiittisesti, koska "oikea" käytäntö vaihtelee yhteisön sisällä eikä ole yksiselitteinen edes USA:ssa.

## 4. Avoimeksi jäävät kysymykset (ei ehdotuksia, vaan kysymyksiä tekijälle)

- Onko käännösvaiheessa tarkoitus tuottaa yksi yhtenäinen USA-versio, vai eriytetäänkö sisältöä osavaltiokohtaisesti (esim. Medicaid-kuljetussääntely vaihtelee merkittävästi osavaltioittain)?
- Käytetäänkö käännöksessä amerikanenglannin lisäksi amerikkalaista oikeudellista terminologiaa (esim. "duty of care", "reasonable accommodation") vai pidetäänkö rakenne suomalaisen lakiviittausmallin mukaisena ja lisätään vain rinnakkaisviittaus?
