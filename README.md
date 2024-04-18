# VR-room(LT)
KTU VR-room yra multimedijos technologijos studentų/praktikantų projektas. Jame buvo realizuota edukacinė erdvė dėstytojams, siekiant labiau įtraukti studentus į paskaitas. 

Šiame dokumente galima rasti projekto pasiruošimo ir naudojimo instrukciją, sukurtų elementų sąrašą ir pristatymą bei kitas rekomendacijas projektui.

## Naudojama įranga
- Unreal Engine versija: 5.3.2
- Operacinė sistema: Windows 10
- Virtualios realybės akiniai: HTC Vive

<br><br>

# Turinys

1. [Sveikato ir saugumo rekomendacijos](#Sveikatos-ir-saugos-rekomendacijos)
2. [Projekto pasiruošimo instrukcija](#Projekto-pasiruošimo-instrukcija)
3. [Programos VR-room pristatymas](#Programos-VR-room-pristatymas)
4. [Rekomendacijos](#Rekomendacijos)

<br><br>

# Sveikatos ir saugos rekomendacijos


<br><br>

# Projekto pasiruošimo instrukcija

Šioje dalyje bus pristatomos projekto aparatūrinės ir programinės įrangos sąranka.

## Aparatūrinės įrangos paruošimo instrukcija

Projekto paleidimui ir tinkamam veikimui yra reikalingi virtualios realybės akiniai. Priklausomai nuo naudojamų VR akinių, jų paruošimo instrukcija gali skirtis, dėl to šioje dalyje yra pateikiami keli virtualios realybės akinių dokumentacijos pavyzdžiai.

- HTC Vive: [HTC VIVE](https://www.vive.com/au/support/vive/category_howto/setting-up-for-the-first-time.html)
- Oculus Quest 2: [OCULUS QUEST 2](https://www.meta.com/quest/setup/)
- Valve Index: [VALVE INDEX]()

## Programinės įrangos instrukcija

Priklausomai nuo naudojamos įrangos, gali būti reikalinga [SteamVR](https://store.steampowered.com/app/250820/SteamVR/) programa, kuri būtų naudojama kompiuterio programų paleidimui. Jeigu yra naudojamas Oculus Quest linijos produktas, bus reikalingas [META QUEST DEVELOPER HUB](https://developer.oculus.com/documentation/unity/ts-odh/). Ši programa yra reikalinga Unreal Engine Editor lauko naudojimui ir greitam projekto programos keitimui.

Norint pasijunkti VR-room projektą, jums reikės įsidiegti "Unreal Engine" programinę įrangą į jūsų kompiuterį. Jį atsidarius galėsite importuoti projekto failus, kuriose bus visas jums reikalingas karkasas. Tam, jog galėtumėte importuoti parsisiųskite projekto failus iš [čia](https://blablablakurbusmusuprojektas.com), tada atsidarę programinę įrangą pagrindiniame lange spaudžiame "Browse..." ir einame i direktoriją, kurioje užsisaugojote failus. Paieškos langelyje susirandame ".uproject" failą ir jį atidarome. Visa tai padarę galite viską keisti redaguoti pagal savo norus.

Jeigu norite nenaudoti "Browse..." mygtuko kiekvieną kartą atidarius "Unreal Engine" programą, galite projekto failus užsisaugoti "C:\Users\[UserName]\Documents\Unreal Projects" aplanke.

# Programos VR-room pristatymas

Čia yra pats projektas.

Čia yra funkcijos, veikiančios šiame karkase:

- Vaikščiojimas
- (Pasirinktų)Objektų paėmimas
- Piešimas
- Ekrano trynimas
- Laikrodis
- Meniu atidarymas
- Pieštuko klonavimas

Tai yra projekto karkasas. Jis yra paruoštas veiklai su VR, taigi jame galima kurti naujas norimas funkcijas.

# Rekomendacijos

Didesniam interaktyvumui rekomenduojame implementuoti papildomų ekranų naudojimą aplinkoje žiūrovams. Taip pat sukurti daugiau funkcijų piešimui.
