# drishtisen.github.io

Personal portfolio site — n8n automation + LinkedIn ghostwriting.

**Live at:** https://YOUR-USERNAME.github.io

## Files

| File | What it is |
|---|---|
| `index.html` | The whole website — all content, styling and motion in one file |
| `images/` | Case-study screenshots, system graphics, social sharing card |
| `404.html` | Shown if someone visits a wrong URL |
| `robots.txt` / `sitemap.xml` | Helps Google find and index the site |

## To edit

Open `index.html` on GitHub, click the pencil icon, change the text, click **Commit changes**.
The live site updates in about a minute.

---

## Three things still to switch on

### 1. Your LinkedIn URL
Search `index.html` for `YOUR-LINKEDIN-HANDLE` — **3 places** — and replace with your real profile URL.

### 2. Your site address (optional, helps Google)
Search for `REPLACE-WITH-YOUR-URL` in `index.html` (2 places), `robots.txt` (1) and `sitemap.xml` (1).

### 3. Your photo
- Save your headshot into the `images` folder as **`drishti.jpg`** (square-ish crop, phone camera is fine)
- Open `index.html`, search for `YOUR PHOTO`
- Delete the comment line above the `<img>` tag and the closing marker below it

---

## The testimonials section

It's already built, sitting commented out just above "Every build includes". When you have two real
client quotes, delete the two comment markers and paste them in. Instructions are inside the file.

**Never put an invented quote there.** The timestamped screenshots are what make this page credible;
one fake testimonial would undo all of it.

---

## Image inventory

| File | Used in |
|---|---|
| `telegram-rag-assistant.jpg`, `rag-how-it-works.jpg`, `rag-conversation.jpg`, `rag-real-phone.jpg` | Telegram doc-assistant case study |
| `content-engine-run.jpg`, `content-calendar.jpg`, `content-1-to-9.jpg`, `content-you-approve.jpg` | Content engine case study |
| `content-output-sample.jpg` | Finance spec-demo case study |
| `inquiry-assistant-run.jpg`, `inquiry-log.jpg` | AI inquiry assistant case study |
| `lead-capture-run.jpg`, `lead-built-tested.jpg`, `lead-never-lose.jpg`, `lead-80-percent.jpg` | Lead capture case study |
| `carousel-workflow.jpg`, `carousel-calendar.jpg` | Carousel Factory case study |
| `social-card.png` | Link preview when the site is shared |

Note: `content-output-sample.jpg` is your "Real Output. Not a Mockup." card with the bottom caption
redrawn at a smaller size so it fits inside the frame — the original ran off the right edge.

---

## Motion

Six effects: scroll fade-ups, hero stat counters, card hover-lift, nav shadow on scroll, screenshot
hover, button hovers. All pure CSS plus about 1KB of JavaScript at the bottom of `index.html`.

Every effect is wrapped in `prefers-reduced-motion: no-preference`, so visitors who have asked their
device to reduce motion get a completely static page. Don't remove that wrapper.
