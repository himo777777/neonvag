# CrazyGames-inlämning — allt färdigt att klistra in

**Så här går det till:** CrazyGames har två steg. Steg 1 (*Basic Launch*) kräver
**ingen teknisk integration alls** — de testar spelet med en begränsad publik i två
veckor. Går det bra bjuds du in till steg 2 (*Full Launch*), och det är då pengarna
börjar komma in. Du behöver alltså inte göra något mer tekniskt nu.

**Skapa konto:** https://developer.crazygames.com → "Submit a game"

---

## Filer att ladda upp

| Vad | Fil |
|---|---|
| Spelet (ZIP) | `neonvag-crazygames.zip` |
| Omslag liggande 1920×1080 | `cover-landscape-1920x1080.png` |
| Omslag stående 800×1200 | `cover-portrait-800x1200.png` |
| Omslag kvadrat 800×800 | `cover-square-800x800.png` |
| Video liggande | `neonvag-preview-landscape.mp4` |
| Video stående | `neonvag-preview-portrait.mp4` |

---

## Speltitel

```
Neonvåg
```

## Kort beskrivning (till listningar)

```
One touch. Zero mercy. Hold to rise, release to dive, and surf a neon wave
through a tunnel that never stops narrowing.
```

## Lång beskrivning

```
Neonvåg is a one-touch arcade game about riding a wave of light.

Hold to rise. Release to dive. That is the entire control scheme — and it takes
about two seconds to understand and a lot longer to master.

The first half minute is gentle on purpose: a wide, calm tunnel that lets you
find the rhythm. After that the walls close in, the speed builds, and the
soundtrack climbs with it. Graze the walls without touching them to earn bonus
points, chain orbs to build a multiplier, and hit the x8 rush where everything
turns into colour.

MODES
- Daily Track — the same course for every player, every day. Come back tomorrow
  for a new one and build a streak.
- Levels — 12 handcrafted stages that alternate between reaching a goal and
  surviving the clock, each rated with up to three stars.
- Endless — one wave, no finish line, how far can you get?

FEATURES
- Power-ups: a shield that absorbs one crash, a magnet that pulls orbs to you,
  and slow-motion for the tightest gaps
- 11 achievements and 8 unlockable ship colours
- An adaptive synthwave soundtrack generated in real time — there are no audio
  files in the game at all
- Plays with touch, mouse or keyboard
```

## Instruktioner (fältet "How to play")

```
Hold anywhere on the screen (or press Space) to rise.
Release to dive.
Collect gold orbs to build your multiplier, and fly close to the walls without
touching them for bonus points.
```

## Kategori och taggar

```
Kategori:  Arcade  (alternativt Casual)
Taggar:    one button, arcade, skill, endless, neon, reaction, minimalist, music
```

## Orientering och enheter

```
Orientering:  Både stående och liggande (spelet anpassar sig till skärmen)
Enheter:      Desktop, mobil och surfplatta
Kontroller:   Touch, mus och tangentbord (mellanslag / uppåtpil)
```

## Om de frågar om integritet eller datainsamling

```
The submitted build collects no data at all. It contains no analytics, no
tracking, no external requests and no external links. All progress is stored
locally in the browser.
```

---

## Vad jag ändrade i portalversionen (och varför)

Versionen i ZIP-filen är avskalad enligt CrazyGames regler — den skiljer sig från
din vanliga sajt:

- **Ingen statistikinsamling.** Portalen ger dig egen statistik, och deras QA
  ogillar rutor som blockerar spelaren. Därför är samtyckesrutan borttagen — det
  finns ingenting att samtycka till längre.
- **Ingen supportknapp.** Portaler tillåter normalt inte egna betallänkar ut från
  spelet. Din Stripe-knapp finns kvar på din egen sajt.
- **Inga externa metataggar** (delningsbilder m.m.) — de behövs bara på din sajt.
- **Tillagt enligt deras tekniska krav:** alla varianter av `user-select: none`
  (hindrar att texten markeras vid dubbeltryck på surfplattor) och en ljudfix som
  återstartar musiken när iOS avbrutit den, t.ex. efter ett telefonsamtal.

Din egen sajt på himo777777.github.io är **oförändrad** — den har fortfarande
statistik, supportknapp och delning.

---

## Vad som händer sedan

1. De granskar spelet (räkna med några dagar).
2. Godkänns det får du en *Basic Launch* på två veckor med begränsad publik.
3. De mäter tre saker: hur länge folk spelar, hur många som börjar spela, och hur
   många som kommer tillbaka.
4. Klarar spelet deras riktmärken bjuds du in till *Full Launch* — global lansering
   med annonsintäkter.

Det är först i steg 4 du behöver bygga in deras SDK, och då hjälper jag dig med det.
