# Welcome to your website, Ivy.

This is your personal site at **ivy.vivianx.com**. You can change it anytime.

The whole thing is just 2 files of code, sitting in this folder on GitHub:

- `index.html` — your homepage (the wall with all the cards)
- `story.html` — your longer story page

You don't need to know "how to code." You only need to learn how to **change text between two arrows**. That's 95% of what you'll ever do.

---

## How to edit your site (the fast way)

1. Go to **github.com/vyanhle/ivy** (this is the page you're on right now if you're reading the README)
2. Press the period key **`.`** on your keyboard — your screen will turn into a code editor
3. Open `index.html` or `story.html` from the left sidebar
4. Press **Cmd+F** (Mac) or **Ctrl+F** (Windows) to search for the text you want to change
5. Change the text → look for the **Source Control** icon on the left (it looks like a Y branch shape)
6. Click it → type a quick note like "updated bio" → press **Commit & Push**
7. Wait 30 seconds → refresh `ivy.vivianx.com` → your change is live

If you mess something up, you can always come back and undo it. Git keeps every version of every file you've ever saved.

---

## The one rule of editing HTML

**Only change the words. Don't touch the brackets `<` and `>`, or anything inside them.**

Example. This is in your file:

```html
<h3>still figuring it out</h3>
```

To change the sticky note text to "still figuring out lunch", just change the words:

```html
<h3>still figuring out lunch</h3>
```

Keep `<h3>` and `</h3>` exactly the same. Just change what's between them.

---

## Things on your site you can easily change

I went through your `index.html` and made a list. Each item shows what to search for and what to change.

### Homepage (`index.html`)

| Want to change... | Search for this text | Change the words after it |
|---|---|---|
| Your tagline at the top | `seventh grade, in pieces` | Whatever feels right |
| The "still figuring it out" sticky note | `still figuring it out` | Change this and the next line |
| "currently obsessed with" sticky | `[ Ivy fills this in ]` | Replace with what you're actually obsessed with this month |
| The school routine description | `Math before lunch` | Rewrite to match your actual day |
| The "Side quests" card | `[Ivy fills these in]` | List 2-3 things you spend time on |
| The big '31 stamp | `'31` | (Don't change — that's your class year) |

### Story page (`story.html`)

| Want to change... | Search for this text |
|---|---|
| The opening "Hi. I'm Ivy. I'm thirteen." | `Hi. I&rsquo;m Ivy.` |
| What you say about your sister | `much more organized than me` |
| The "currently obsessed with" placeholder | `[ Ivy fills this in ]` |
| The plan for next year (high school) | `Eighth grade next year` |

---

## Things that are harder (just ask if you want these)

These take a bit more code knowledge. Instead of struggling, send a message in the chat your dad uses with Claude (he'll know what to do):

- Adding a new card to the wall on the homepage
- Removing a card you don't want anymore
- Changing the layout (where cards are positioned)
- Changing colors of the site
- Adding a new page (like `/photos` or `/projects`)

The wall layout uses something called CSS Grid — it's how the cards are positioned to look scattered. Changing it without understanding it will mess up the layout. Not worth the time when you can just ask.

---

## How to add a real photo of you

Right now your polaroid has a placeholder that says "A photo of Ivy goes here."

To put a real photo:

1. Get a photo you like (any photo — selfie, photo with friends, photo of just your hands holding something, anything)
2. Save it on your computer as `ivy_hero.jpg`
3. Go to your repo at `github.com/vyanhle/ivy`
4. Click **Add file** → **Upload files**
5. Drag `ivy_hero.jpg` in
6. Commit
7. Refresh your site → photo shows up automatically

The placeholder text disappears as soon as the image loads.

---

## A note from Claude (the AI helping your dad build this)

I made this site with placeholders because I don't know you yet. The words in the cards right now are *my guesses* about what a seventh grader might want to say. They probably aren't *you*.

When you get a chance, change them. Not because you have to, but because **the whole point of this site is that it sounds like you**, not like anyone else.

You don't have to do it all at once. Change one sticky note this week. Change another next month. The site is yours. It grows with you.

If you don't know what to write, that's okay too. "still figuring it out" is honest. That can stay as long as you want.

— c.

---

## Quick reference

| Task | How long | Need help? |
|---|---|---|
| Change text in a card | 2 minutes | No |
| Add a new entry / sticky | 2 minutes | No (after first time) |
| Upload your photo | 2 minutes | No |
| Add a new card/section | 10 minutes | Yes, ask in chat |
| Change colors / fonts | 15 minutes | Yes, ask in chat |
| Add a new page | 20 minutes | Yes, ask in chat |

Good luck. Be a little weird. That's the point.
