# Lämpölaajeneminen

Lämpölaajeneminen on ilmiö, jossa kappaleen tilavuus kasvaa, kun lämpötila nousee. Kappale voi olla kiinteässä, nestemäisessä tai kaasumaisessa olomuodossa. Tarkastellaan näitä tapauksia erikseen.


## Kiinteät aineet

Kiinteiden aineiden lämpölaajeneminen täytyy huomioida erityisesti metallirakenteiden suunnittelussa. Kiinteän aineen mittojen muutosta kuvaa lämpölaajenemiskerroin $\alpha$. Kertoimet ovat varsin pieniä, esimerkiksi betonille $\alpha=12\cdot 10^{-6}~\frac{1}{K}$. Lämpötilakertoimia löytyy esimerkiksi [taulukot.com](https://www.taulukot.com/fysiikka/mekaniikka_termodynamiikka/#muiden_kiinteiden_aineiden_ominaisuuksia)-sivustolta.

Jos kappaleen pituus alkuperäisessä lämpötilassa on $l_0$, niin pituus lämpötilan muutoksen $\Delta T$ jälkeen on 

$l=l_0(1+\alpha \Delta T)$

Tarvittaessa voidaan laskea myös pituuden muutos $\Delta l=l-l_0$:

$\Delta l = \alpha l_0 \Delta T$

::::{admonition} Esimerkki

Kuinka pitkäksi muuttuu 100 m teräksinen mittanauha, kun lämpötila nousee $20^{\circ}$ Celsius-asteesta $50^{\circ}$ Celsius-asteeseen? Teräksen lämpölaajenemiskerroin on $\alpha=12\cdot 10^{-6} \frac{1}{K}$ (sama kuin betonin).

:::{admonition} Ratkaisu
:class: tip, dropdown

Sijoitetaan suureiden arvot laskukaavaan $l=l_0(1+\alpha \Delta T)$.

Lämpötilan muutos $50^{\circ}~\text{C}-20^{\circ}~\text{C}=30^{\circ}~\text{C}$ on yhtä suuri Kelvineinä, siis $\Delta T = 30$ K.

$l=100~\text{m} \cdot (1+12\cdot 10^{-6}~\frac{1}{K} \cdot 30~\text{K}) = 100.036~\text{m}$

Muutos on siis 3.6 cm. Mittanauha näyttää väärin, koska nyt sen merkkiviivat ovat jakaantuneet liian pitkälle matkalle. Matkat ovat siis oikeasti pitempiä kuin mittanauhalla mitatut lukemat.

:::

::::

::::{admonition} Esimerkki

Teräksisen mittanauhan kalibrointilämpötila on $20^{\circ}~\text{C}$. Mittanauhalla mitattiin $35^{\circ}~\text{C}$ helteellä moukarinheittotulos $60.54~\text{m}$. Mikä oli oikea tulos?

:::{admonition} Ratkaisu
:class: tip, dropdown

Lasketaan pituuden muutos kaavalla $\Delta l = \alpha l_0 \Delta T$. Lämpötilojen erotus on $\Delta T = 15~\text{K}$. Sijoitetaan tämä ja muut arvot kaavaan:

$\Delta l = 12\cdot 10^{-6}~\frac{1}{K}\cdot 100~\text{m}~\cdot 15~\text{K} = 0.01~\text{m}$

Pituus poikkeaa siis 1 cm verran oikeasta. Koska mittanauha on venynyt, niin sen lukemat ovat liian harvassa. Oikea tulos olisi $60.54~\text{m} + 0.01~\text{m} = 60.55~\text{m}$.

:::

::::

::::{admonition} Esimerkki

Pajassa sorvataan teräksinen tappi (halkaisija 30.00 mm) pyöreään reikään (halkaisija 29.97 mm). Kuinka paljon teräksistä levyä on lämmitettävä, jotta tappi mahtuisi reikään?

:::{admonition} Ratkaisu
:class: tip, dropdown

Reiän halkaisija pitäisi saada kasvatettua yhtä suureksi kuin tapin. Ratkaistaan lämpötilan muutos $\Delta T$ yhtälöstä $l=l_0(1+\alpha \Delta T)$:

$\Delta T=\frac{l-l_0}{l_0 \alpha} = \frac{30.00~\text{mm}-29.97~\text{mm}}{29.97~\text{mm}\cdot 12\cdot 10^{-6}~\frac{1}{K}} \approx 83.4~\text{K}$

Lämpötilan muutos on yhtä suuri Celsius- ja Kelvin-asteikoilla. Niinpä levyä pitäisi lämmittää noin 84 astetta.

:::

::::

Pinta-alan muutosta $\Delta A$ vastaava laajenemiskerroin on $\beta=2\alpha$, ja tilavuuden muutosta $\Delta V$ vastaava kerroin on $\gamma=3\alpha$. Kun kappaleen alkuperäinen pinta-ala on $A$ ja tilavuus $V$, niin saadaan seuraavat laskukaavat:

$\Delta A = A \beta \Delta T = 2A \alpha \Delta T$, $\Delta V = V \gamma \Delta T = 3V \alpha \Delta T$


## Nesteet

Nesteillä ainoa oleellinen lämpölaajenemisen muoto on tilavuuden muutos. Ilmiötä voidaan hyödyntää lämpötilan mittauksessa. Nestelämpömittareissa asteikko on suoraan verrannollinen mittarin sisällä olevan nestepatsaan korkeuteen. Mitä lämpimämpää on, sitä nopeammin nesteen molekyylit liikkuvat ja sitä suuremman tilan ne vaativat. 

Nesteille on taulukoitu tilavuuden lämpölaajenemiskertoimet suoraan. Tällöin tilavuuden muutos saadaan kaavalla $\Delta V = V \gamma \Delta T$.

Yleensä nesteen tilavuus on sitä suurempi, mitä korkeampi on nesteen lämpötila. Vesi poikkeaa tästä säännöstä. Veden lämpötilakerroin on negatiivinen, kun veden lämpötila on välillä $0^{\circ}~\text{C} \dots 4^{\circ}~\text{C}$, ja positiivinen, kun lämpötila on enemmän kuin $4^{\circ}~\text{C}$. Vesi kutistuu, kun se lämpenee nollasta asteesta, ja saavuttaa pienimmän tilavuutensa neljässä asteessa. Kun lämpötila nousee siitä, veden tilavuus alkaa jälleen kasvaa.

::::{admonition} Esimerkki

Keskuslämmitysjärjestelmässä kiertää 300 litraa vettä. Veden lämpötila nousee 15 asteesta 80 asteeseen. Miten paljon vettä virtaa paisuntasäiliöön? Oletetaan, että veden laajenemisen lämpötilakerroin on $0.000207~\frac{1}{\text{K}}$. Verkoston lämpölaajenemista ei tarvitse ottaa huomioon.

:::{admonition} Ratkaisu
:class: tip, dropdown

$\Delta V = 300~\text{l} \cdot 0.000207~\frac{1}{\text{K}} ~\cdot (80-15)~\text{K} \approx 4.0~\text{l}$.

:::

::::

::::{admonition} Esimerkki

Teräksinen 1500 litran öljysäiliö täytetään aivan täyteen. Öljyn ja säiliön lämpötila on täyttöhetkellä -20 astetta. Myöhemmin lämpötila nousee +20 asteeseen. Öljyn tilavuuden lämpötilakerroin on $0.0009~\frac{1}{\text{K}}$.

a) Kuinka paljon säiliön tilavuus kasvaa?

b) Kuinka paljon öljyn tilavuus kasvaa säiliössä?

c) Kuinka paljon öljyä vuotaa yli säiliöstä?

:::{admonition} Ratkaisu
:class: tip, dropdown

a) Säiliön tilavuuden muutokseen tarvitaan laskukaavaa $\Delta V = 3V \alpha \Delta T$. Kaavassa tarvittava lämpötilaero on $\Delta T = (20-(-20))~\text{K}=40~\text{K}$.

$\Delta V = 3\cdot 1500~\text{l}\cdot 12\cdot 10^{-6} \frac{1}{K} \cdot 40~\text{K} = 2.2~\text{l}$

b) Öljyn tilavuuden muutos lasketaan kaavalla $\Delta V = V \gamma \Delta T $:

$\Delta V = 1500~\text{l}\cdot 0.0009 \frac{1}{K} \cdot 40~\text{K} = 54~\text{l}$

c) Öljyn tilavuus muuttuu huomattavasti enemmän kuin säiliön. Yli vuotava määrä on $54~\text{l}-2.2~\text{l}=51.8~\text{l}$ eli noin 52 litraa.

:::

::::

## Kaasut

Kaasumaisten aineiden lämpölaajeneminen on paljon voimakkaampaa kuin kiinteiden tai nestemäisten aineiden. Jälleen riittää tarkastella pelkästään tilavuuden muutosta. Laskukaava on kuitenkin toinen. Kaasuille ei ole olemassa erillisiä lämpölaajenemiskertoimia, vaan kaikkien kaasujen ajatellaan käyttäytyvän kuten niinsanottu ideaalikaasu. 

Ideaalikaasun ominaisuudet ovat seuraavat:
- kaikki rakenneosat ovat keskenään samanlaisia ja kooltaan äärettömän pieniä
- rakenneosat liikkuvat tasaisella nopeudella ja suoraviivaisia reittejä
- rakenneosat vuorovaikuttavat toistensa kanssa vain törmätessään, ja törmäykset ovat täysin kimmoisia

Mikään kaasu ei oikeasti toimi kuten ideaalikaasu. Kemian perusasioihin kuuluu, että molekyylien välillä on pieniä sähköisiä vuorovaikutuksia (van der Waalsin voima), vaikka aine olisikin kaasumaista. Lisäksi ilmassa on monia erilaisia molekyylejä, esimerkiksi happi- ja typpimolekyylejä. Kuitenkin kaasujen tilavuuden muutosta lämpötilan muuttuessa voidaan riittävällä tarkkuudella mallintaa seuraavalla laskukaavalla:

$\frac{V_1}{T_1}=\frac{V_2}{T_2}$

Kyseisen laskukaavan nimi on Gay-Lussacin laki. Jos tiedetään, että kaasun tilavuus on $V_1$ silloin, kun lämpötila on $T_1$, niin voidaan laskea kaasun tilavuus $V_2$ jossakin muussa lämpötilasssa $T_2$. Tähän kaavaan lämpötilat pitää sijoittaa Kelvineinä.

::::{admonition} Esimerkki

Saunan tilavuus on 12 kuutiometriä. Saunan lämpötila on aluksi 18 astetta, ja saunan lämmettyä 80 astetta. Kuinka paljon saunasta poistuu ilmaa?

:::{admonition} Ratkaisu
:class: tip, dropdown

Lämpötilat pitää muuttaa Kelvineiksi. Alkulämpötila on $T_1=(18+273.15)~\text{K}=291.15~\text{K}$ ja loppulämpötila on $T_2=(80+273.15)~\text{K}=353.15~\text{K}$. Ratkaistaan Gay-Lussacin laista lopputilavuus $V_2$ ja sijoitetaan suureiden arvot:

$V_2=V_1 \frac{T_2}{T_1} = 12~\text{m}^3\cdot \frac{353.15}{291.15} = 14.6~\text{m}^3$

Ilmaa poistui $V_2-V_1=2.6~\text{m}^3$.

:::

::::

**Huom!** Jos lämpötila muuttuu, mutta kaasun tilavuus ei pysty kasvamaan, niin kaasun paine kasvaa arvosta $p_1$ arvoon $p_2$. Tämä tulee muistaa, jos kaasuja varastoidaan tiiviissä säiliöissä. Kaasun paineen ja lämpötilan yhteyttä kuvaa Charlesin laki, joka on seuraava:

$\frac{p_1}{T_1}=\frac{p_2}{T_2}$