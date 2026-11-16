# Portfolio Template 1 — Neon Tech ⚡

A dark, neon-glow portfolio website with premium animations. It's **one single file** (`index.html`), so you don't need to install anything, and you don't need to know React or any framework.

**Animations included**
- **Cinematic scroll:** the headline reveals line by line, the About text lights up word by word, the project gallery slides sideways, and a progress bar fills as you scroll
- **3D / particles:** glowing particles that move away from your mouse, and project cards that tilt in 3D
- **Kinetic typography:** big scrolling text bands, a job title that scrambles, and "LET'S TALK" letters that lift when you hover
- **Minimal & smooth:** a custom cursor, magnetic buttons and a 0 → 100 loading screen

---

## 🚀 How to use this template

### Step 1 — Get your own copy
Pick **one** of these:
- **Easiest:** click the green **Code** button → **Download ZIP**, then unzip it on your computer.
- **On GitHub:** click **Fork** (top right) to copy the repo into your own account.

### Step 2 — Open it
Double-click `index.html` and it opens in your browser. That's your website.

To edit it, open `index.html` in a code editor. [VS Code](https://code.visualstudio.com/) is free; Notepad works too.

> 💡 **Tip:** to find the text you want to change, press **Ctrl + F** (Windows) or **Cmd + F** (Mac) in your editor and search for it. Change it, save the file, then refresh the browser to see the result.

---

## ✏️ Step 3 — Put in your details

Search for each item in the left column and replace it with your own.

| Search for | What it is | Change it to |
|---|---|---|
| `Your Name` | Browser tab title, hero and footer (appears 3 times) | Your full name |
| `YOUR NAME` | Logo at the top left | Your name or brand |
| `Your City` | Location in the hero | Your city |
| `const roles=` | The job titles that scramble in the hero | Your own titles, e.g. `['Business Analyst','Web Developer']` |
| `I design &amp; build` | Big hero headline | Your own headline (`&amp;` means "&") |
| `Available for projects` | Small green "status" line | e.g. `Open to work` |
| `I turn complex ideas` | Big About sentence. Words with a `*` before them glow blue | Your own sentence |
| `Write two or three sentences` | Short paragraphs beside the About text | A bit about you |
| `data-count="8"` | Numbers that count up (years, projects, clients, awards) | Your own numbers. Change the label under each one too |
| `Project One` … `Project Four` | Project names, type and year | Your projects |
| `<span>UX</span>` | Small tags on each project | The tools you used |
| `Product Design` (in Services) | The 4 services you offer | Your services |
| `Placeholder testimonial` | Client quote | A real quote |
| `Client Name` | Who said the quote | Their name, role and company |
| `hello@yourname.com` | Your email address | Your email |
| `href="#" data-hover>LinkedIn` | Social links in the footer | Replace `#` with your profile links, e.g. `href="https://linkedin.com/in/yourname"` |

---

## 🖼️ Step 4 — Add your project pictures

1. Create a folder called **`images`** next to `index.html`.
2. Put your screenshots in it, e.g. `project-1.jpg`, `project-2.jpg`. Landscape images (16:10) look best.
3. In `index.html`, search for `class="art a1"`. You'll find a line like this:
   ```html
   <div class="art a1"><div class="mock"><i></i><i></i><i></i><div class="blk"></div></div></div>
   ```
   Replace that **whole line** with:
   ```html
   <img class="art" src="images/project-1.jpg" alt="Project One" style="width:120%;height:120%;object-fit:cover">
   ```
4. Do the same for `a2`, `a3` and `a4`, using `project-2.jpg` and so on.

---

## 📬 Step 5 — Make the contact form send you emails

Right now the form is a demo. To receive real messages (free):

1. Go to **[formspree.io](https://formspree.io)**, sign up and click **New Form**.
2. Copy your form link. It looks like `https://formspree.io/f/abcdwxyz`.
3. In `index.html`, search for `data-endpoint=""` and paste your link between the quotes:
   ```html
   <form id="form" class="reveal" data-endpoint="https://formspree.io/f/abcdwxyz">
   ```
4. Save. Messages sent from the form now arrive in your email inbox.

---

## 🎨 Change the colours (optional)

Near the top of `index.html`, look for `:root{`. These lines control all the colours:

```css
--bg:#05060d;      /* page background */
--blue:#3d8bff;    /* main glow colours */
--cyan:#22e4ff;
--violet:#9b5cff;
--pink:#ff4fd8;
```

Replace the colour codes with your own. You can pick colours at [coolors.co](https://coolors.co).

---

## 🌍 Step 6 — Put it online (free)

**Option A: GitHub Pages**
1. Upload your edited files to your own GitHub repo, or edit them directly in your fork.
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, pick **main** and **/ (root)**, then click **Save**.
4. Wait about 1 minute. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

**Option B: Netlify (drag and drop)**
Go to [app.netlify.com/drop](https://app.netlify.com/drop) and drag your project folder onto the page. It goes live instantly.

---

## ❓ Common questions

- **I broke something!** Undo your last change (Ctrl + Z) or download a fresh copy. Usually a `<` or `"` was deleted by mistake.
- **Does it work on phones?** Yes, it's responsive. The custom cursor is turned off on touch screens.
- **Can I remove a section?** Yes. Each section starts with a comment like `<!-- SERVICES -->`. Delete from that comment down to its closing `</section>`.
- **People who don't like motion?** The animations automatically calm down for visitors who have "Reduce motion" turned on in their device settings.

---

## 💬 Credit & custom websites

This template was designed and built by **Wintas (Nnanna Okechukwu)**. The small credit bar at the very bottom of the page links back to me. It's appreciated if you keep it.

Want a **custom website** built for you or your business? Get in touch:

- 💬 **WhatsApp:** [+234 708 306 6127](https://wa.me/2347083066127)
- ✉️ **Email:** nnannaokechukwu1@gmail.com
- 𝕏 **X:** [@wintasblog](https://x.com/wintasblog)
- 🌐 **Portfolio:** [wintas01.github.io/portfolio01](https://wintas01.github.io/portfolio01/)

---

Free to use for your personal portfolio. If it helps you, a ⭐ on the repo is appreciated!
