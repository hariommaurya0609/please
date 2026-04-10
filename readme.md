# 💘 Valentine Proposal Page

A fun, interactive Valentine's Day page you can personalise with anyone's name and share as a link.

> ⭐ If this made you or someone smile, please **[Star this repo](https://github.com/hariommaurya0609/please)** or **[Fork it](https://github.com/hariommaurya0609/please/fork)** so others can use it too! It only takes one click and means a lot 🙏

---

## 🎯 What does this page do?

When someone opens the link, they see a cute kitten GIF and a question:
**"[Name], kya aap meri Valentine banoge? 💘"**

- They click **"Haan ji! 💖"** (Yes) → 🎉 Celebration screen with confetti hearts!
- They click **"Nahi 😒"** (No) → The button runs away from their cursor 😂 and the kitten gets sadder with every click!

---

## 🚀 How to use it (step by step)

### Step 1 — Open the page

Open `index.html` in any web browser (Chrome, Safari, Edge, Firefox).
You will see the Valentine page with a default name **"Jaanu"**.

---

### Step 2 — Add a name to the link

You just need to add `?name=YOURNAME` at the end of the URL in your browser's address bar.

**Example:**

| What you type in the address bar | What the person sees |
| -------------------------------- | -------------------- |
| `index.html`                     | Jaanu (default)      |
| `index.html?name=Kiran`          | Kiran                |
| `index.html?name=Priya`          | Priya                |
| `index.html?name=Rahul`          | Rahul                |

> 💡 Works with any name — girlfriend, boyfriend, husband, wife, crush, best friend, or your cat 🐱

---

### Step 3 — Share the link

However you are hosting or sharing the file, just add `?name=...` to the end of the URL and send it!

**Examples:**

```
https://hariommaurya0609.github.io/please/?name=Kiran
https://hariommaurya0609.github.io/please/?name=Priya
```

Send it over WhatsApp, Instagram DM, email — anywhere! 💌

---

## ✏️ One small setup step (for the "Steal this?" button)

After someone clicks **YES**, a small button appears in the top-right corner that says **"😏 Want to steal this?"** — it links to your GitHub repo so others can use it too.

To set your own link, open `index.html` in any text editor (Notepad on Windows, TextEdit on Mac), find this line near the top of the `<script>` section:

```js
const GITHUB_URL = "https://github.com/YOUR_USERNAME/YOUR_REPO";
```

Replace `YOUR_USERNAME` and `YOUR_REPO` with your actual GitHub username and repository name. Save the file. Done!

---

## 🎮 Easter eggs & fun behaviour

| Action                  | What happens                                              |
| ----------------------- | --------------------------------------------------------- |
| Click **NO** once       | Button text changes to _"Sach mein? 🥺"_                  |
| Click **NO** twice      | _"[Name]… please 😢"_                                     |
| Click **NO** a 3rd time | Button runs away from your cursor like a scared kitten 🐱 |
| Click **NO** more       | Text gets more dramatic. YES button keeps growing 😈      |
| Click **YES**           | Heart confetti explosion 💥 + celebration screen          |

---

## ❓ Frequently Asked Questions

**Q: Does it work on mobile?**
Yes! Works on phones and tablets. The NO button runs away from your finger touch too 😂

**Q: Do I need to install anything?**
No! Just open `index.html` in a browser. That's it.

**Q: Can I change the messages?**
Yes — open `index.html` in Notepad/TextEdit and search for `noLabels` or `final-msg` to edit the text.

**Q: The GIFs are not loading — why?**
You need an internet connection. The cute kitten GIFs are loaded from the internet (not stored locally).

---

---

## ⭐ Like this project?

If this made someone smile, please give it a star — it helps more people find it!

| Action                          | Link                                                                  |
| ------------------------------- | --------------------------------------------------------------------- |
| ⭐ Star the repo                | [Click here to Star](https://github.com/hariommaurya0609/please)      |
| 🍴 Fork & make your own version | [Click here to Fork](https://github.com/hariommaurya0609/please/fork) |

No pressure — just if it made you happy 😊

---

Made with ❤️ — because some people deserve a whole webpage, not just a text message.
