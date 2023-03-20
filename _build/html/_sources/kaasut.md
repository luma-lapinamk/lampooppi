# Kaasujen perusprosessit

Kaasujen perusprosessit tarkoittavat muutoksia, joissa jokin kaasulain $pV=nRT$ suureista pysyy vakiona. Useat koneet (polttomoottori, kaasuturbiini, ilmastointi) perustuvat kaasuissa tapahtuviin prosesseihin. Prosessit voivat olla seuraavanlaisia:

1. Isokoorinen prosessi: tilavuus pysyy vakiona
2. Isobaarinen prosessi: paine pysyy vakiona
3. Isoterminen prosessi: lämpötila pysyy vakiona

Lisäksi voi tapahtua adiabaattinen prosessi: kaasun sisäenergia pysyy vakiona.

Kaikissa näissä prosesseissa perustana on kaasulaki $pV=nRT$. Kaasulain voi esittää myös muodossa: $\frac{pV}{T}=nR$ eli toisin sanoen suure $pV/T$ on vakio. Siis jos alkutilanteessa kaasun paine on $p_1$, tilavuus $V_1$ ja lämpötila $T_1$, ja lopputilanteessa vastaavat arvot ovat $p_2, V_2, T_2$, niin voimassa on kaasujen tilanyhtälö

$\frac{p_1 V_1}{T_1}=\frac{p_2 V_2}{T_2}$

## Isokoorinen prosessi

Isokoorisissa prosessissa kaasun tilavuus ei muutu. Kaasu on siis astiassa, joka ei mahdollista kaasun laajenemista. Toisaalta koska kaasu täyttää aina koko käytössään olevan tilan, niin kaasun tilavuus ei voi pienentyäkään. Kun tilavuus ei muutu, niin $V_1=V_2=V$, joten

$\frac{p_1 V}{T_1}=\frac{p_2 V}{T_2}$

Sieventämällä saadaan seuraava laskukaava eli Charlesin laki:

$\frac{p_1}{T_1}=\frac{p_2}{T_2}$

Isokoorisissa prosesseissa kaasu ei laajene, joten se ei tee mekaanista työtä. Kaasun lämmittämiseen tarvittava lämpöenergia
lisää sisäenergiaa: $\Delta U = Q$.

::::{admonition} Esimerkki

Auton renkaisiin laitetaan ylipaine 180 kPa (180 bar), kun pakkasta on -20 astetta. Kun autolla on ajettu puoli tuntia, renkaiden lämpötila on noussut +15 asteeseen. Mikä on rengaspaine tuolloin?

:::{admonition} Ratkaisu
:class: tip, dropdown

Auton renkaissa olevan ilman absoluuttinen paine on ylipaineen ja ilmanpaineen summa. Normaali ilmanpaine on 101300 Pa eli noin 101 kPa. Todellinen paine on siis $p_1=180~\text{kPa}+101~\text{kPa}=281~\text{kPa}$. Lämpötilat tulee sijoittaa kaavaan Kelvineinä. Alkulämpötila on $T_1=(-20+273)~\text{K}=253~\text{K}$ ja loppulämpötila on $T_2=(15+273)=288~\text{K}$. Charlesin laista saadaan loppupaine

$p_2=p_1 \frac{T_2}{T_1} = 281~\text{kPa}\cdot \frac{288~\text{K}}{253\text{K}}=320~\text{kPa}$

Lukema vastaa normaaliin ilmanpaineeseen verrattuna ylipainetta $(320-101)~\text{kPa}=219~\text{kPa}$ eli noin 2.2 bar.

:::

::::

## Isobaarinen prosessi

Isobaarisissa prosesseissa kaasun paine ei muutu, eli $p_1=p_2=p$. Kaasu voi kuitenkin laajentua, esimerkiksi ilmapallon koko voi muuttua. Kun kaasujen tilanyhtälöön sijoitetaan vakiopaine $p$, saadaan seuraava laskukaava, Gay-Lussacin laki:

$\frac{V_1}{T_1}=\frac{V_2}{T_2}$

Kaasu tekee laajetessaan työn $W = p \Delta V$. Jos kaasua lämmitetään, lämpöenergia menee osittain sisäenergian nousuun, mutta tästä pitää
vähentää kaasun tekemä työ. Siis $\Delta U = Q- p \Delta V$.

::::{admonition} Esimerkki

Saunan ilmatilavuus on 12 kuutiometriä.

a) Kuinka paljon ilmaa virtaa pois saunasta, kun sauna lämmitetään 20 asteen huoneenlämmöstä 90 asteen lämpötilaan?

b) Kuinka suuren työn ilma laajetessaan tekee?

:::{admonition} Ratkaisu
:class: tip, dropdown

$V_2=V_1 \frac{T_2}{T_1} = 12~\text{m}^3 \cdot \frac{(20+273)~\text{K}}{(90+273)~\text{K}} = 14.9~\text{m}^3$

Ilmaa poistui $(14.9-12)~\text{m}^3$ eli 2.9 kuutiometriä.

b) Oletetaan, että saunan ilma on normaalipaineessa 1013000 Pa. 

$W=p \Delta V = 101300~\text{Pa}\cdot 2.9~\text{m}^3 = 294~\text{kJ}$

:::

::::

## Isoterminen prosessi

Isotermisessä prosessissa kaasun lämpötila pysyy vakiona, siis $T_1=T_2=T$. Sijoittamalla tämä kaasujen tilanyhtälöön saadaan Boylen laki:

$p_1 V_1=p_2 V_2$

Laajetessaan kaasu tekee työtä, mutta koska painekin muuttuu, niin kaasun tekemän työn laskemiseen tarvittaisiin integraalilaskentaa.

::::{admonition} Esimerkki

Auton vararenkaassa on ylipaine 1.9 bar eli 190 kPa. Renkaan sisätilavuus on 95 litraa. Kuinka paljon ilmaa virtaa ulos normaalipaineeseen,
kun venttiili menee epäkuntoon ja koko ylipaine purkautuu? Oletetaan, että renkaan muoto säilyy muuttumattomana ja että kaasu virtaa ulos niin hitaasti, että sen lämpötila ei muutu.

:::{admonition} Ratkaisu
:class: tip, dropdown

Alkuperäinen paine on $p_1=(190+101)~\text{kPa}=291~\text{kPa}$, ja uusi paine on normaalipaine $p_2=101~\text{kPa}$. Ratkaistaan uusi tilavuus $V_2$:

$V_2=V_1 \frac{p_1}{p_2} = 95~\text{l}\cdot \frac{291~\text{kPa}}{101~\text{kPa}}=274~\text{l}$

Ulos virtaa siis määrä $\Delta V = (274-95)~\text{l}=179~\text{l}$.

:::

::::

## Adiabaattinen prosessi

Adiabaattinen prosessi on prosessi, jossa kaasun ja ympäristön välillä ei siirry lämpöenergiaa $Q$. Tyypillinen esimerkki adiabaattisesta
prosessista on nopea kaasun tilavuuden muutos, jossa lämpöenergiaa ei ehdi siirtyä esim. sylinterin seinämän läpi. Tällaisia prosesseja tapahtuu ainakin bensiinimoottoreissa.

Laskukaava on melkein sama kuin isotermisessä prosessissa:

$p_1 V_1 ^{\gamma} = p_2 V_2 ^{\gamma}$

missä $\gamma=\frac{C_p}{C_V}$, $C_p$ on kaasun ominaislämpökapasiteetti vakiopaineessa ja $C_V$ on kaasun ominaislämpökapasiteetti vakiotilavuudessa. Suureen $\gamma$ nimi on adiabaattivakio. Kaksiatomisten kaasujen (esim. happi, typpi) ja ilman adiabaattivakio on $\gamma=1.4$.

Kaava voidaan esittää myös seuraavassa muodossa:

$T_1 V_1 ^{\gamma-1} = T_2 V_2 ^{\gamma-1}$

Perustelu jälkimmäiselle muodolle on seuraava: $pV^{\gamma} = pVV^{\gamma-1} = nRT V^{\gamma-1}$. Koska $pV$ on vakio, niin myös $TV^{\gamma-1}$ on vakio.

Koska prosesseissa ei siirry lämpöenergiaa $Q$, niin kaasun sisäenergian muutos on sama kuin kaasun tilavuuden muutokseen liittyvä työ $W$. Siis $\Delta U = W$.

::::{admonition} Esimerkki

Bensiinimoottori ottaa sylinteriin ulkoilmaa, jonka lämpötila on 10 astetta. Moottorin puristussuhde on 16, siis sylinteritilavuuden maksimin $V_1$ ja minimin $V_2$ suhde on $V_1/V_2=16$. Laske ilman lämpötila, kun ilman tilavuus on pienimmillään. Oletetaan, että puristus on adiabaattinen.

:::{admonition} Ratkaisu
:class: tip, dropdown

Käytetään kaavaa $T_1 V_1 ^{\gamma-1} = T_2 V_2 ^{\gamma-1}$ ja ratkaistaan siitä lämpötila $T_1$:

$T_2=T_1\frac{V_2 ^{\gamma-1}}{V_1 ^{\gamma-1}}=T_1 \left(\frac{V_1}{V_2}\right)^{\gamma-1}$

Sijoitetaan lämpötila $T_1=(10+273)~\text{K}=283~\text{K}$, puristussuhde sekä ilman adiabaattinen vakio:

$T_1=283~\text{K}\cdot 16^{1.4-1} = 858~\text{K}$

Lämpötila on siis noin 585 Celsius-astetta.

:::

::::

::::{admonition} Esimerkki

Mihin murto-osaan ilman Kelvin-lämpötila pienenee, kun kaasu laajenee adiabaattisesti siten, että sen tilavuus 20-kertaistuu?

:::{admonition} Ratkaisu
:class: tip, dropdown

Nyt $V_2=20 V_1$. Uusi lämpötila on

$T_2 = T_1 \left(\frac{V_1}{20 V_1}\right)^{\gamma-1} = T_1 \left(\frac{1}{20}\right)^{0.4} = 0.3 T_1$

Lämpötila laskee siis 30 prosenttiin alkuperäisestä (Kelvin-asteikolla mitattuna).

:::

::::