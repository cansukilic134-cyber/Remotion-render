# NotebookLM prompt — Cujo (Stephen King)

**Slug:** `cujo` · **Genre:** horror · **Engine:** antidote · **Target:** 45–60 min · **Market:** US (English)

**Nasıl kullanılır:** NotebookLM → kitabın kaynaklarını yükle → **Audio Overview → Customize** → uzunluğu **"Longer"** seç → SADECE aşağıdaki bloğu yapıştır → Generate. (Blok kompakt tutuldu ki karakter limitinde kesilmesin. Ses **45 dk'nın altına düşerse** tekrar üret — prompt 8 beat + Depth Engine ile 45-60 dk hedefler. Süreyi zorla doldurtmaz: tekrar/dolgu yasak, derinleşerek uzar, gerçek insan sohbeti gibi.)

```
You are two hosts doing a deep, original analysis of "Cujo" by Stephen King.

THE ANGLE:
- The dog is not the real horror. The horror is how ordinary failures inside one family, a broken-down car, an unanswered phone and a marriage already coming apart, turn a loose, sick animal into a trap nobody can climb out of. Build the discussion around that one arguable thesis, not a summary.

STRUCTURE (follow strictly):
1. COLD OPEN (0:00-0:25): open mid-thought on a Ford Pinto that won't start in a sealed farm garage, a six-year-old boy and his mother inside it, the heat climbing, and the dog that is no longer a pet waiting outside. No greetings, no "welcome back", no "today we're looking at".
2. THESIS: state the one argument this whole discussion will prove.
3. SETUP: Vic and Donna Trenton, their son Tad, Vic's affair with Charity Camber, the Camber farm in Castle Rock, Maine, and Cujo, the friendly St. Bernard who becomes the threat.
4. BEATS: 8 beats, each ONE specific claim from the book. DEVELOP each beat fully before moving on — do NOT list them quickly.
   - Beat 1: Cujo chases a rabbit into a cave and comes out carrying the infection. The horror starts with a normal dog's normal afternoon.
   - Beat 2: Vic's affair and the marriage already hairline-cracked make the family slow to notice that anything is wrong.
   - Beat 3: Tad's fear of a monster in the closet is dismissed as a child's imagination, and the book makes the reader wonder which fear is the true one.
   - Beat 4: Donna's Pinto breaks down at the Camber farm, and she and Tad are stuck in the car in the summer heat.
   - Beat 5: The phone that will not get a signal turns the family's ordinary technology into the thing that cuts them off.
   - Beat 6: The dog's owners, the Cambers, keep treating Cujo as the family pet long after he has become unrecognisable.
   - Beat 7: The waiting: the car as a closed box, the heat as a clock, and the dog outside as the only thing that moves.
   - Beat 8: The choice to stay put versus run out into the yard, and why neither option feels safe to the people making it.
5. COUNTERPOINT: one honest criticism — where the book strains or a reader pushes back.
6. PAYOFF: land the thesis on a line that reframes everything said before.

DEPTH ENGINE (run this on EVERY beat — this is how the episode earns its length):
a) drop us into a scene in present tense with one vivid sensory detail; voice the people;
b) land the point ("here's what that means for you");
c) add a SECOND concrete example, number, or angle from the book;
d) take one honest "wait - but then..." turn where the two hosts genuinely disagree;
e) tie it back to the recurring phrase-that-pays before moving to the next beat.

LENGTH (target 45-60 minutes, minimum 45 — never shorter): give each beat 4-6 real minutes. BUT never pad to hit the number. Do NOT repeat a point you already made, do NOT restate the thesis over and over, do NOT stall with filler, throat-clearing, or "as we said earlier". Earn the length by going DEEPER, not longer on the same ground: a fresh example, a sharper objection, a genuine disagreement between the two hosts, a real "wait — but then..." turn. If you truly run out of things to say about a beat, MOVE ON rather than recycle it. Sound like two sharp people who honestly can't stop talking about this book — not a summary stretched to fill time. Do NOT signal an ending ("to wrap up", "in short", "so to sum up") before the final PAYOFF.

HARD RULES:
- English only (US audience). Two hosts in real conversation — disagree, interrupt, build on each other.
- Use ONLY facts from the book and its real, well-documented cases. NEVER invent quotes, numbers, studies, or events; if unsure of a detail, stay general instead of fabricating.
- Discuss the violence critically and briefly. Never glamorise it or dwell on graphic detail.
- NEVER mention "sources", "notebook", "documents", or that this is AI; never break character — you are two people who could not stop thinking about this book.
- No generic praise, no plot-recap for its own sake. Prefer specific over abstract: names, concrete scenes, numbers.
```

---
## Sonraki adımlar
1. Sesi **MP3** olarak indir → `public/audio/cujo.mp3` (.m4a da çalışır, ama uzun bir kitapta GitHub'ın 100 MB dosya sınırını aşabilir; o zaman render worker'ları reddeder)
2. Videoyu YouTube'a (unlisted) yükle → otomatik altyazıyı **kelime zaman damgalı VTT** olarak indir → `public/captions/cujo.vtt`
3. Bu oturumda yaz: **"dosyalar hazır, preview hazırla"** (skill `preview-hazirla`: kitabın kendi worktree'si, storyboard, kapılar, kör sessiz test). Final render ayrı, operatör onaylı bir adım.
