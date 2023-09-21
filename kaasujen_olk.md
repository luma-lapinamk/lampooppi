# Kaasujen energian muutoksia

Tarkastellaan energian muutoksia tapahtumissa, jossa kaasun lämpötila, paine tai tilavuus muuttuu. Energian määrä prosesseissa riippuu siitä, millainen kaasu on kyseessä. Lisäksi lämpötilan muutoksiin liittyvä ominaislämpökapasiteetti on erilainen riippuen siitä, muuttuuko kaasun lämpötila vakiopaineessa vai vakiotilavuudessa.

## Erilaisten kaasujen sisäenergia

Aiemmin tarkasteltu, kineettisen kaasuteorian mukainen keskimääräinen kaasumolekyylin liike-energia on voimassa vain sellaisille kaasuille, joiden rakennehiukkaset ovat yksittäisiä atomeja. Tällaisia kaasuja ovat jalokaasut kuten helium, neon ja hitsauskaasu argon. Liike-energiasta johdettiin kaasun sisäenergiaksi $U=\frac{3}{2}nRT$.

Kahdesta atomista koostuva molekyyli liikkuu kokonaisuudessaan siten, että molekyylin etenemiseen liittyvä osuus sisäenergiasta on edellä mainittu $\frac{3}{2}nRT$. Lisäksi molekyylin kahden atomin välisessä sidoksessa tapahtuu värähtelyä. Mielikuvana voi ajatella, että atomit ovat kiinni toisissaan kuminauhalla, joka voi venyä mutta palautuu aina ennalleen. Värähtely lisää molekyylien liike-energiaa siten, että sisäenergiaksi tulee $U=\frac{5}{2}nRT$. Ilma koostuu enimmäkseen kaksiatomisista kaasuista (happi, typpi).

Jos molekyylissä on atomeja kolme tai enemmän, niin molekyylin etenemiseen ja liikkumiseen sisältyy vielä enemmän energiaa. Sisäenergia tällaisille kaasuille on $U=\frac{6}{2}nRT$. Moniatomisia kaasuja ovat esimerkiksi hiilidioksidi $\text{CO}_2$ ja ammoniakki $\text{NH}_3$.


## Energia kaasujen lämpötilamuutoksessa

Tarkastellaan tilannetta, jossa kaasun lämpötila muuttuu. Lämpöopin ensimmäisen pääsäännön mukaan $Q=\Delta U+p\Delta V$. Koska oleellisin kaasu sovelluksissa on ilma, niin sijoitetaan yhtälöön kaksiatomisen kaasun sisäenergia $U=\frac{5}{2}nRT$. Oletetaan, että ainemäärä $n$ ei muutu. Tällöin sisäenergian muutos on $\Delta U = \frac{5}{2}nR\Delta T$.

**Muutos vakiotilavuudessa**

Jos lämpötilan muutos tapahtuu vakiotilavuudessa, niin $\Delta V=0$ ja tällöin $Q=\Delta U$ eli $Q=\frac{5}{2}nR\Delta T$. Toisaalta energian $Q$ ja lämpötilanmuutoksen $\Delta T$ yhteys voidaan määritellä ominaislämpökapasiteetin $C$ (yksikössä $\frac{\text{J}}{\text{mol K}}$) avulla siten, että $Q=nC \Delta T$. Saadaan siis yhtälö:

$\frac{5}{2}nR\Delta T=nC \Delta T$

josta saadaan helposti

$C=\frac{5}{2}R$.

Kyseistä suuretta kutsutaan kaasun _ominaislämpökapasiteetiksi moolia kohden vakiotilavuudessa_ ja merkitään $C_V$. Tämän avulla voidaan määritellä myös _kaasun ominaislämpökapasiteetti vakiotilavuudessa_, $c_v=\frac{C_V}{M}$, missä $M$ on kaasun moolimassa.

Ilmalle voidaan laskea $C_V=\frac{5}{2}\cdot 8.31~\frac{\text{J}}{\text{mol K}}=20.8~~\frac{\text{J}}{\text{mol K}}$ ja

$c_v=\frac{20.8~~\frac{\text{J}}{\text{mol K}}}{0.029~\frac{\text{kg}}{\text{mol}}}=717~\frac{\text{J}}{\text{kg K}}$

**Muutos vakiopaineessa**

Jos lämpötilan muutos tapahtuu vakiopaineessa, niin tilavuus voi kuitenkin muuttua. Kaasujen tilanyhtälöstä saadaan $p\Delta = nR\Delta T$. Tällöin siis $Q=\Delta U + nR\Delta T$. Kun sijoitetaan kaasun sisäenergian lauseke, saadaan $Q=\frac{5}{2}nR\Delta T+nR\Delta T$, siis sievennettynä $Q=\frac{7}{2}nR\Delta T$.

Kirjoitetaan taas energian $Q$ ja lämpötilanmuutoksen $\Delta T$ yhteys ominaislämpökapasiteettiin $C$ muodossa $Q=nC \Delta T$. Saadaan siis yhtälö:

$\frac{7}{2}nR\Delta T=nC \Delta T$ 

ja edelleen $C=\frac{7}{2}R$ eli toisin ilmaistuna $C=C_v+R$.

Kyseistä suuretta kutsutaan kaasun _ominaislämpökapasiteetiksi moolia kohden vakiopaineessa_ ja merkitään $C_p$. Tämän avulla voidaan määritellä myös _kaasun ominaislämpökapasiteetti vakiopaineessa_, $c_p=\frac{C_p}{M}$, missä $M$ on kaasun moolimassa. 

Ilmalle voidaan laskea $C_p=\frac{7}{2}\cdot 8.31~\frac{\text{J}}{\text{mol K}}=29.1~~\frac{\text{J}}{\text{mol K}}$ ja

$c_p=\frac{29.1~~\frac{\text{J}}{\text{mol K}}}{0.029~\frac{\text{kg}}{\text{mol}}}=1003~\frac{\text{J}}{\text{kg K}}$.

::::{admonition} Esimerkki

Kuumailmapuhaltimella irroitetaan maalia. Laitteen teho on 2000 W ja se puhaltaa kuumaa ilmaa, jonka lämpötila maksimiteholla on $650^{\circ}\text{C}$. Huoneen lämpötila on 20 astetta. Laske kuuman ilman tilavuusvirta yksikössä litraa/minuutti.

:::{admonition} Ratkaisu
:class: tip, dropdown

Kun puhallinta käytetään teholla $P$ aika $t$, niin sen kautta kulkeva ilma sisältää energiaa $Q=Pt$. Toisaalta tiedetään, että ilman lämpöenergia on $Q=m c_p \Delta T$, kun puhalluksen oletetaan tapahtuvan vakiopaineessa. Niinpä saadaan yhtälö

$Pt=m c_p \Delta T$,

josta ratkeaa

$m=\frac{Pt}{c_p \Delta T}=\frac{2000~\text{W}\cdot 60~\text{s}}{1003~\frac{\text{J}}{\text{kg K}} \cdot (650-20)~\text{K}}=0.19~\text{kg}$

Massa voidaan muuttaa tilavuudeksi huomioimalla, että $n=\frac{m}{M}$ ja sijoittamalla tämä kaasujen tilanyhtälöön:

$pV=nRT$ eli $pV=RT\frac{m}{M}$, josta ratkeaa $V=\frac{mRT}{pM}$.

Sijoitetaan yhtälöön edellä laskettu massa $m$, vakio $R=8.31~\frac{\text{J}}{\text{mol K}}$, kuuman ilman lämpötila $T=(273+650)~\text{K}$, normaalipaine $p=101300~\text{Pa}$ ja ilman moolimassa $M=0.029~\text{kg/mol}$:

$V=\frac{0.19~\text{kg}\cdot 8.31~\frac{\text{J}}{\text{mol K}} \cdot 923~\text{K}}{101300~\text{Pa} \cdot 0.029~\frac{\text{kg}}{\text{mol}}} = 0.496~\text{m}^3$.

Ilmamäärä on siis hieman alle 500 litraa minuutissa.

:::

::::

::::{admonition} Esimerkki
Ilmalämpöpumpun sisäyksikön lämmitysteho on eräänä päivänä 1200 W. Se ottaa huoneesta 20-asteista ilmaa 8.0 kuutiometriä minuutissa. Mikä on sen ulos puhaltaman ilman lämpötila?

:::{admonition} Ratkaisu
:class: tip, dropdown
 
Muunnetaan tilavuus massaksi käyttämällä kaasujen tilanyhtälöä:

$pV = nRT$ eli $pV=\frac{m}{M}RT$, josta saadaan $m=\frac{pVM}{RT}$

$m=\frac{101300~\text{Pa}\cdot 8~\text{m}^3\cdot 0.029~\frac{\text{kg}}{\text{mol}}} {8.31~\frac{\text{J}}{\text{mol K}} \cdot 293~\text{K}}=9.66~\text{kg}$

Ilman lämpötilan muutos saadaan yhtälöstä $Pt=c_p m \Delta T$, eli

$\Delta T = \frac{Pt}{c_p m}=\frac{1200~\text{W}\cdot 60~\text{s}}{1003~\frac{\text{J}}{\text{kg K}}\cdot 9.66~\text{kg}}=7.4~\text{K}$

Lämpötilan muutos on siis 7.4 astetta, joten poistuvan ilman lämpötila on 27.4 astetta.

:::

::::
