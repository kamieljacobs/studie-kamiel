# Studie Kamiel

Persoonlijke studiesite van Kamiel Jacobs: studiepodcasts en literatuur. Live via GitHub Pages: https://kamieljacobs.github.io/studie-kamiel/

## Inhoud
- `index.html` startpagina, `bronnen.html` bronnen per aflevering
- `podcasts/index.html` speler (gewone `<audio>`, Media Session, speelt door met scherm op slot, hoofdstukken als losse mp3's), data in `podcasts/afleveringen.json`
- `podcasts/sdt/<aflevering>/` per aflevering: `script.md` (tekst + bronnen), `segmenten.json` (opnamestukken, stem-invoer, ElevenLabs generation-ids), `audio/` (gebouwde hoofdstukken)
- `podcasts/sdt/uitspraak.md` wachtlijst uitspraak (nog te beluisteren)
- `scripts/maak_segmenten.py` en `scripts/bouw.py`, overgenomen uit de biologiesite (`kamieljacobs/biologie-`, `podcasts/`), met eigen uitspraakregels in `scripts/uitspraak.json` + EXTRA

## Werkwijze nieuwe aflevering
1. Script in `podcasts/<reeks>/<aflevering>/script.md` (kop, `---`, hoofdstukken `## <nr> · <titel> (± duur)`, denkstiltes `[STILTE 3]`/`[STILTE 4]`, afsluitend geen tweede `---` nodig).
2. `python3 scripts/maak_segmenten.py <map>`
3. Inspreken in ElevenLabs: stem Remko (`vjeU1L5RIGPyrwuboFwz`), eleven_v4, één take per segment; ruwe takes als `<segment-id>.mp3` buiten de repo.
4. `python3 scripts/bouw.py <map> <ruwe takes>` (intro/overgang uit `podcasts/geluid/`, −16 LUFS, mono 64 kbit/s)
5. Aflevering toevoegen aan `podcasts/afleveringen.json` en een kaart op `index.html`.

## Reeks Zelfdeterminatietheorie (25 nov 2026)
Gebaseerd op het literatuuronderzoek *Motivatie in leerlingentaal (SDT × taal × AI)* (Claude Doc). ElevenLabs-flow: https://elevenlabs.io/app/flows/tcgPz0uwllyw3QKnUXdF, ±18.600 credits.
1. Drie voedingsstoffen (7:31) · 2. Motivatie in de klas (6:11) · 3. Hoe klinkt motivatie? (6:15)
