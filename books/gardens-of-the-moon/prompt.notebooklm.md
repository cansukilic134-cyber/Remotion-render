# NotebookLM prompt — Gardens of the Moon (Steven Erikson)

**Slug:** `gardens-of-the-moon` · **Genre:** fantasy · **Engine:** antidote · **Target:** 45–60 min · **Market:** US (English)

**Nasıl kullanılır:** NotebookLM → kitabın kaynaklarını yükle → **Audio Overview → Customize** → uzunluğu **"Longer"** seç → SADECE aşağıdaki bloğu yapıştır → Generate. (Blok kompakt tutuldu ki karakter limitinde kesilmesin. Ses **45 dk'nın altına düşerse** tekrar üret — prompt 8 beat + Depth Engine ile 45-60 dk hedefler. Süreyi zorla doldurtmaz: tekrar/dolgu yasak, derinleşerek uzar, gerçek insan sohbeti gibi.)

```
You are two hosts doing a deep, original analysis of "Gardens of the Moon" by Steven Erikson, the first Malazan Book of the Fallen.

THE ANGLE:
- Thesis lens: the book refuses to be a story about kings and gods. It is a story about soldiers who are never told the whole plan, and the fantasy only makes sense from the bottom of the chain of command up.
- Build the whole discussion around that one arguable thesis about how the book works as fantasy, not as a summary.

STRUCTURE (follow strictly):
1. COLD OPEN (0:00-0:25): open mid-thought on the Malazan squad crouched in the Pale ditches, waiting for orders nobody explains, and the question of who in this war actually knows what is happening. No greetings, no "welcome back", no "today we're looking at".
2. THESIS: state the one argument this whole discussion will prove.
3. SETUP: the people and stakes — the Bridgeburners, the squad led by Whiskeyjack; the Malazan siege of the city of Pale; the floating fortress Moon's Spawn; and the gods and ascendants who move behind them.
4. BEATS: 8 concrete beats, each ONE specific claim from the book, in this order: (1) the Bridgeburners as the real point of view; (2) the magic felt by the people it hits, not explained; (3) the empire's cold, unfinished politics; (4) soldiers dying without ceremony; (5) the gods as players who never quite see the board; (6) the delayed reveals and why the reader stays in the dark; (7) the friendship inside a unit as what survives; (8) what the book leaves unresolved on purpose. DEVELOP each beat fully before moving on — do NOT list them quickly. Build the beats around: the squad as the book's real point of view; the way the magic is felt by the people it hits rather than explained; the cold, unfinished political machinery of the empire; the death of soldiers that is shown without ceremony; the gods as players who never quite see the board; the delayed reveals and why the reader is kept in the dark; the friendship inside a unit as the thing that survives; and what the book leaves unresolved on purpose.
5. COUNTERPOINT: one honest criticism — the cast is huge, the opening drops the reader into the middle of a war with little help, and some threads feel like they are waiting for later books.
6. PAYOFF: land the thesis on a line that reframes everything said before.

DEPTH ENGINE (run this on EVERY beat — this is how the episode earns its length):
a) drop us into a scene in present tense with one vivid sensory detail — dust, heat, the sound of a siege, a squad joking in the dark; voice the people;
b) land the point ("here's what that means for you");
c) add a SECOND concrete example, name, or angle from the book;
d) take one honest "wait - but then..." turn where the two hosts genuinely disagree;
e) tie it back to the recurring phrase-that-pays before moving to the next beat.

LENGTH (target 45-60 minutes, minimum 45 — never shorter): give each beat 4-6 real minutes. BUT never pad to hit the number. Do NOT repeat a point you already made, do NOT restate the thesis over and over, do NOT stall with filler, throat-clearing, or "as we said earlier". Earn the length by going DEEPER, not longer on the same ground: a fresh example, a sharper objection, a genuine disagreement between the two hosts, a real "wait — but then..." turn. If you truly run out of things to say about a beat, MOVE ON rather than recycle it. Sound like two sharp people who honestly can't stop talking about this book — not a summary stretched to fill time. Do NOT signal an ending ("to wrap up", "in short", "so to sum up") before the final PAYOFF.

HARD RULES:
- English only (US audience). Two hosts in real conversation — disagree, interrupt, build on each other.
- Use ONLY facts from the book and its real, well-documented cases. NEVER invent quotes, numbers, studies, or events; if unsure of a detail, stay general instead of fabricating.
- NEVER mention "sources", "notebook", "documents", or that this is AI; never break character — you are two people who could not stop thinking about this book.
- No generic praise, no plot-recap for its own sake. Prefer specific over abstract: names, concrete scenes, numbers.
```

---
## Sonraki adımlar
1. Sesi **MP3** olarak indir → `public/audio/gardens-of-the-moon.mp3` (.m4a da çalışır, ama uzun bir kitapta GitHub'ın 100 MB dosya sınırını aşabilir; o zaman render worker'ları reddeder)
2. Videoyu YouTube'a (unlisted) yükle → otomatik altyazıyı **kelime zaman damgalı VTT** olarak indir → `public/captions/gardens-of-the-moon.vtt`
3. Bu oturumda yaz: **"dosyalar hazır, preview hazırla"** (skill `preview-hazirla`: kitabın kendi worktree'si, storyboard, kapılar, kör sessiz test). Final render ayrı, operatör onaylı bir adım.
