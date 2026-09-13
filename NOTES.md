# The Selah Taiwanese Rendering — NOTES

*nan.v1 · chair 71 · seated 2026-09-13. The first Taiwanese chair —
Hanji spoken register (台語漢字白話), the register the chair was built
to guard: 伊/𪜶/毋/袂/佮/佇/欲/咧, never the Mandarin 他/不/沒/們.*

## The seal

| Count | Value |
|---|---|
| Verses | 23,213 / 23,213 |
| Token spine ≡ en floor | 23,213 / 23,213, zero mismatches |
| 雅威 at the Name seat | 6,828 / 6,828 tokens carrying יהוה, 100% (6,923 in the flow) |
| 以羅欣 (flow) | 2,502 |
| ⟨את⟩ | 11,866 in the token row ≡ 11,866 in the flow ≡ the en floor, per-file 0 off |
| Erasure vocabulary (耶和華 / 上帝 / 天主 / 祢 / 祂) | **0** in every flow and gloss |
| Latin / POJ residue | **0** (the POJ sweep table + hand gleanings) |
| Empty flows | **0** |
| Simplified-only glyphs | **0** after the validated 172-char map (个 enumerated LAWFUL — the standard Taiwanese classifier, 11,704 uses) |
| Malformed ⟨את⟩ brackets | **0** after normalization (254 variant closers 》〉〕>, doubled markers unmasked and cured) |

## Cruxes of the chair

- **The bleed ledger was a false alarm — and that is the chair's
  central lesson.** Three press rounds kept "re-flagging" 320 verses
  for 他/不/沒; the Tekoa thermometer lane proved 317 of 320 lawful:
  他 is a Hebrew name syllable (拿弗他利 50 · 他連得 37 · 他施 30 ·
  耶弗他 27…), 不 lives in literary compounds (不義 23 · 不時 · 不法),
  沒 is myrrh (沒藥) — the ledger regex simply had no whitelist. The
  REAL Mandarin bleed was where the regex never looked: 它/她/們 in
  50 verses (0.215%), discharged at seating (mechanical swaps + six
  whole-verse re-presses).
- **The fabricated-marker burn.** The flow carried 59 markers with no
  Hebrew source — 8 of them one nameable failure: the press mistook
  the 2nd-person pronoun אַתְּ/אַתָּה ("you") for the object particle
  (Ezek 16:45,48 · Isa 51:9 · Jer 2:27 · Judg 13:3 · Neh 9:6 ·
  Ps 65:4 · Zech 9:11 · Gen 39:9). Meanwhile the gloss row reproduced
  the en floor's marker set byte-exactly in all 23,213 verses, and the
  nan flow was CORRECT on all 92 of the floor's own flow/gloss marker
  inconsistencies. All 59 stripped; the lawful markers re-anchored by
  the object rule; 16 terminal double-marked flows read against the
  Hebrew one by one (`dev/scripts/nan_tekoa_hand16.py` in the Selah
  repo holds every decision).
- **The rule-6 burn.** The press printed its own second thoughts into
  scripture 41+ times — the densest cluster a PRONOUN-POLICY tic in
  the Psalms (祢——毋著,是你 "not 祢, by the rule write 你"; Ps 38:10
  printed the rule and rendered the verse twice). Factual
  self-corrections in the counting books (Omri→Baasha, Egypt→Moab,
  14,000→41,500 照原文), and 1 Chr 1:38 carried 研究袂著 ("can't
  figure it out") where Shobal's brother stands. Discharged at
  seating: 52-verse re-press; the tic re-printed in four
  (Ps 30:9 · Ps 86:17 · 1 Sam 14:2 · Ex 23:14) and was hand-excised.
- **Lev 8:35, the center verse, clears the bho trap outright**:
  תמותו → 袂死 — death named, no idiom drift. Hab 3:3 carries 以羅亞
  for אלוה and 細拉 for סלה. Isa 7:14 reads 少女 — the Hebrew let be
  the Hebrew.
- **Dan 3:12, the eighteenth chair.** יתהון is the Aramaic pronoun
  object, not a marker: bare 𪜶, no ⟨את⟩/⟨ית⟩; the Hebrew marker
  never crosses the language seam (⟨את⟩ ≡ 0 inside the Aramaic
  sections).
- **Sheol is 示阿勒** (65/66) and 地獄 appears zero times in the whole
  corpus, as do 陰府/黃泉/火湖.
- **The mixed-script corruption** (the bho analogue): ⟨阿ת⟩ and
  ⟨阿特⟩ — את partially transliterated into Hanji inside its own
  marker — plus Hebrew letters embedded in Hanji words; six sites,
  all cured. Cross-lingual decoder bleed at four sites (Russian
  человек, Greek χ, Korean 의 and Japanese の standing in 的's slot)
  — cured.
- **POJ swept to Hanji**: the ~40-word romanization table (in/teh/ê →
  𪜶/咧/的) plus hand gleanings (o-ló→呵咾, lim→啉, Hit→彼个,
  kaat/rahama/shalak parentheticals removed).

## Open questions (Class B — filed for the stranger, never auto-fixed)

The full framing lives in `data/experiments/nan-seating/nan-tekoa-report.md`
in the Selah repo. The heads:

1. Retire the bleed ledger with the six whitelists (the yue-particle
   precedent)?
2. The classifier glyph: 個 3,802 vs 个 5,783 — a 40/60 split,
   inconsistent in every book.
3. Literary 們 on nouns (9 verses) — lawful written register or bleed?
4. The ארץ posture: Genesis 1 renders identical הארץ seven ways
   (土腳 "the floor" at 1:17/1:20); the Gen 1:10 naming loop doesn't
   close; orthographic split 土腳/塗跤/塗腳/土跤.
5. The Aramaic Elah seat scatters six transliterations (以羅欣/以羅亞/
   以羅阿/以勒/以拉/神); Ezra 7's rescript wholly off-seat; 以拉
   collides with King Elah. And Dan 5:25–28 leaves MENE MENE TEKEL
   PARSIN in raw Aramaic script inside the Taiwanese flow.
6. 28 individual erasure seats (six in Daniel where kings name the
   Hebrews' God 神/神明; Neh 8:9 carries the corpus's single 上主).
7. The Spirit seat: 10 of 18 capital-S Spirit rows read 神/神魂/風 —
   神魂 means "wits" in Taiwanese, and it stands at Isa 61:1.
8. 1cs rendered 阮 (plural-exclusive "we") at Job 19:25 and elsewhere
   — deliberate spoken-register humility or drift?
9. 618 empty glosses clustered on particles (אשר 289 · כי 96 · די 33)
   — the floor itself carries 10.
10. The name separator (Katakana ・ 194 · ‧ 128 · · 66) and the
    ~35-term Hebrew-citation parenthetical (撒督 with pointed צדוק in
    parens) — convention or residue.

## The burn signature

Pressed 2026-09-12 → 2026-09-13 on the z.ai lane: tier glm-5.2 for
23,130 verses, glm-5.3 for 83 (the force re-press cohorts: spine
repairs, residue ladder rungs, the Tekoa 52). Recorded model field:
glm-5.3 across the corpus (the lane's serving model); the tier field
carries the true split. Rails:
`docs/methodology/translation-discipline/nan.md`. Every repair pass is
a script in the Selah repo (`dev/scripts/nan_*.py`) — the decisions
are the files.
