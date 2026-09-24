<a href="https://rokovnik.svilenkovic.com/"><img src="media/cover.jpg" alt="Registracioni rokovnik, naslovna strana na laptopu i telefonu" width="100%"></a>

# Registracioni rokovnik

Web aplikacija za agencije za registraciju i tehničke preglede: istek registracije, klijenti, termini i predmeti, i kada nema interneta.

**[rokovnik.svilenkovic.com](https://rokovnik.svilenkovic.com/)** · [English](README.md)

> [!NOTE]
> Moj sopstveni proizvod. Izvorni kod je privatan. Ova stranica opisuje šta radi i kako je napravljen.

<table>
  <tr><td><b>Klijent</b></td><td>Sopstveni proizvod</td></tr>
  <tr><td><b>Delatnost</b></td><td>Softver za agencije za registraciju vozila i stanice tehničkog pregleda</td></tr>
  <tr><td><b>Lokacija</b></td><td>Srbija</td></tr>
  <tr><td><b>Vrsta</b></td><td>Web aplikacija (PWA) za više firmi</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>React 19, Vite, PWA, Astro</td></tr>
</table>

## O projektu

Registracioni rokovnik je moj proizvod za agencije za registraciju vozila i stanice tehničkog pregleda u Srbiji. Klijente, vozila, rokove, saglasnosti, termine i predmete drži u jednoj istoriji, pa zaposleni vidi kome uskoro ističe registracija, koji predmet stoji i gde ima slobodnog termina.

Aplikacija nikoga ne zove i nikome ne piše sama. Listu za rad slaže iz roka, ranijih pokušaja, kanala na koji je klijent pristao i slobodnog kapaciteta, i uz svaki predlog piše zašto je dat. Poziv ili poruku pokreće zaposleni i posle beleži kako se završilo. Podrazumevani podsetnici su 30, 15 i 7 dana pre isteka i 3 dana posle, a uvezeni kontakti bez dokaza o saglasnosti ne ulaze u liste za kontakt.

## Šta sam uradio

- PWA u React 19 i Vite-u koja čuva nacrte i bez interneta: radni podaci ostaju dostupni do 72 sata bez provere naloga i sinhronizuju se kad se veza vrati
- Nova verzija se preuzima u pozadini i uključuje tek kada nema upisa u toku; ako instalacija ne uspe, ostaje prethodna
- Podaci odvojeni po firmi i lokaciji, i u bazi i u aplikaciji, uz lične naloge, audit log i opoziv uređaja
- Uvoz CSV i XLSX tabela kroz red poslova u pozadini, sa pregledom mapiranja, grešaka i duplikata, a svaka serija može da se poništi
- Raspored za stanice tehničkog pregleda po liniji, kategoriji vozila, trajanju i pauzama, sa dolascima bez zakazivanja, listom čekanja i opterećenjem za osam nedelja
- Astro sajt za predstavljanje proizvoda i javna strana sa statusom usluge

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 98 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

Lighthouse, laboratorijsko merenje živog sajta, septembar 2026.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Registracioni rokovnik, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Registracioni rokovnik, naslovna strana na telefonu"></td>
  </tr>
</table>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
