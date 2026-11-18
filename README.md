# ⭐ Sylvia's CoR Quest ⭐

A pixel-art platformer in the style of Mario Bros, in European flag colors, as a tribute to **Sylvia**, assistant at the European Committee of the Regions (CoR).

The team is locked up in office-cages by administrative paperwork. Across the **3 main political priorities of the CoR**, Sylvia must free her colleagues and reach her boss **Fabrizio**.

## 🎮 Play

Just open `index.html` in your browser, or deploy to GitHub Pages (see below).

### Controls

**PC / Mac**
- `←` / `→` or `A` / `D`: move
- `Space` / `↑` / `W`: jump

**Mobile / Tablet**
- On-screen touch buttons

### 🏛️ The 3 levels (CoR priorities)

Each colleague is guarded by **🧙‍♂️ ACHIM the Terrible**, an evil bureaucrat-wizard who demands a trial before releasing them:

1. **🌱 Green Transition** — free the **WEB team** (Annika, Marios, Carmen, Jake, Mara, Amelia, Arnaud)
   → **Trial**: answer Achim's **European Green Deal quiz** (Fit for 55, climate neutrality, ETS, CBAM, Just Transition Fund…)
2. **🤝 Territorial Cohesion** — free the **Social Media team** (Klaudia, Katrin, Benedetta, Sarah, Yannis, Betty)
   → **Trial**: solve Achim's **Simon-says memory puzzle** (watch the color sequence, repeat it)
3. **⭐ The Future of Europe** — free the **Visual Communication team** (Carole, Carlos, George, Blandine, Viktor, Valerie, Timothy, Gaia)
   → **Trial**: pass Achim's **EPSO-style abstract reasoning test** (number sequences, letter sequences, odd-one-out, logical deduction)

A wrong answer costs 1 life — Achim cackles, pushes Sylvia back, and locks the cage for a couple of seconds before she can try again.

### Objective

- 📋 **Collect** signed leave forms (+100 pts)
- ⭐ **Grab** the 12 European stars of each level (+200 pts)
- ☕ **Drink** coffee to restore a life (rarer in higher levels!)
- 👥 **Beat Achim's trial** at each cage to free the colleague (+300 pts) — they'll follow you around!
- 📄📞📧 **Avoid** paperwork, ringing phones, flying emails (more of them each level!)
- 👔 **Reach Fabrizio** at the end of each level

### 🔥 Difficulty

The levels get progressively harder:
- **Level 2 & 3** add **flying email enemies** on floating platforms
- Enemies get **faster and more numerous** each level
- **Fewer coffees** are available in higher levels
- Simon-says sequences and reasoning puzzles get longer as more colleagues are freed

### 🎵 Music

A rotating playlist of 4 public-domain European classical pieces, played in 8-bit style and cycling automatically so it never gets repetitive:

1. **Ode to Joy** — Beethoven (official EU anthem)
2. **Can-Can** — Offenbach (French, energetic)
3. **Für Elise** — Beethoven (German, gentle)
4. **In the Hall of the Mountain King** — Grieg (Norwegian, driving)

Top-right controls: `♪ ON/OFF` button to mute, and a **volume slider** to adjust in real time. The current track name briefly appears each time a new piece starts.

### ⭐ European touches

- European blue background and golden accents
- 12 stars arranged in a circle (like on the EU flag) in the background of every level
- European flag waving next to Fabrizio
- Mini EU flags on the background buildings

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `sylvia-cor-quest`)
2. Push both files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit — Sylvia's CoR Quest"
   git branch -M main
   git remote add origin https://github.com/YOUR_USER/sylvia-cor-quest.git
   git push -u origin main
   ```
3. In **Settings → Pages**, source = `main` / root
4. Available at `https://YOUR_USER.github.io/sylvia-cor-quest/` in about 1 minute

## 🛠️ Tech stack

- 100% vanilla HTML / CSS / JavaScript
- Zero dependencies, zero build, zero backend
- Pixel art drawn on Canvas 2D (sprites defined as ASCII)
- Works on desktop + mobile (touch controls automatically shown)
- Audio: Web Audio API (8-bit SFX + Ode to Joy looping with bass line)

## 💙⭐ For Sylvia and the entire CoR team
