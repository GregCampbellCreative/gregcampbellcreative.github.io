# gregcampbellcreative.com

Personal site for Greg Campbell — author, journalist, documentary filmmaker.

## Structure

```
/
├── index.html        ← Main site (homepage + all sections)
├── photo.jpg         ← Headshot (used in About panel)
├── README.md         ← This file
└── workshop/
    └── index.html    ← Workshop minisite (to be built)
```

## How to edit content

All content lives in `index.html`. Open it in VS Code and search for:

- **Your bio** → search for `about-text` 
- **Book descriptions** → search for `book-caption`
- **Journalism outlets** → search for `outlet-row`
- **Film section** → search for `film`
- **Workshop copy** → search for `workshop-desc`

## How to publish changes

1. Make your edit in VS Code and save the file
2. Open GitHub Desktop
3. You'll see the changed file listed — write a short note in the "Summary" box (e.g. "updated bio")
4. Click **Commit to main**
5. Click **Push origin**

Live site updates within ~60 seconds.

## To connect your custom domain (gregcampbellcreative.com)

1. In your GitHub repo, go to Settings → Pages
2. Under "Custom domain", enter `gregcampbellcreative.com`
3. Log into your domain registrar (wherever you bought the domain) and update the DNS records — Claude can walk you through this step when ready.
