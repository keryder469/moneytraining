[README.md](https://github.com/user-attachments/files/29752937/README.md)
# Members / Consumer Money Training Ledger

A simple 2-page site: the training curriculum, and a placeholder ramp dashboard.

- `index.html` — the Members / Consumer Money curriculum (Weeks 1–4)
- `dashboard.html` — sample ramp metrics dashboard (not connected to real data yet)
- `style.css` — shared styling for both pages

---

## Adding links to each topic yourself

Right now, topic names are plain text (e.g. `Consumer Money - Overview`). To turn any of them into a clickable link, wrap the text in an `<a>` tag.

**Before:**
```html
<span class="ledger-line__topic">Consumer Money - Overview</span>
```

**After:**
```html
<span class="ledger-line__topic"><a href="https://docs.google.com/presentation/d/XXXXXXX/edit">Consumer Money - Overview</a></span>
```

Steps:
1. Open `index.html` in any text editor (Notepad, TextEdit, VS Code, or even GitHub's own web editor — see below).
2. Use Find (Ctrl+F / Cmd+F) to locate the topic name you want to link.
3. Copy the real link from the source Google Sheet for that resource.
4. Wrap the topic text in `<a href="PASTE_LINK_HERE">...</a>` as shown above.
5. Save the file.

You can do this one topic at a time, whenever you have the link handy — no need to do them all at once. Nothing breaks if some topics stay plain text and others become links.

If you want it to look like a link (underlined, colored), it already will — the site's link styling applies automatically to any `<a>` tag.

---

## Turning this into a real website — step by step (like you're 5)

Think of it like this: right now these files just sit on your computer, like a drawing in a drawer. GitHub Pages is a magic drawer that puts your drawing up on a wall (the internet) for anyone to see.

### Step 1: Get a GitHub account
Go to [github.com](https://github.com) and sign up if you don't already have an account. (Skip if you already have one.)

### Step 2: Make a new "repository" (a folder for your project)
1. Click the **+** icon top-right → **New repository**.
2. Give it a name, like `members-money-training`.
3. Leave everything else as default.
4. Click **Create repository**.

### Step 3: Upload your files
1. On the new repository page, click **uploading an existing file** (a blue link near the middle of the page).
2. Drag `index.html`, `dashboard.html`, and `style.css` into the upload box.
3. Scroll down, click **Commit changes** (the green button). This just means "save."

### Step 4: Turn on GitHub Pages
1. Click the **Settings** tab (top of the repository page).
2. In the left sidebar, click **Pages**.
3. Under "Branch," choose **main** and leave the folder as **/ (root)**.
4. Click **Save**.

### Step 5: Wait a minute, then visit your site
GitHub will show a message like "Your site is live at `https://your-username.github.io/members-money-training/`." Give it about a minute, then click that link — your site is now a real, public website.

### Making changes later
Every time you want to update something (like adding a link):
1. Go to your repository on GitHub.
2. Click on the file you want to edit (e.g. `index.html`).
3. Click the pencil icon (✏️) to edit it right in the browser.
4. Make your change, scroll down, click **Commit changes**.
5. Your live site updates automatically within a minute or two — no re-uploading needed.

That's it — no coding tools, no installs, just a browser.
