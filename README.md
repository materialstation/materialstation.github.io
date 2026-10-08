# Materials Station · Malzeme İstasyonu

Bilingual (English / Türkçe) site built with Hugo and published free on GitHub Pages.

## Where things are

| What | Where |
|---|---|
| Email, links, brand names | `hugo.toml` (lines marked `<-- EDIT`) |
| English pages | `content/en/` |
| Turkish pages | `content/tr/` |
| English articles | `content/en/writings/` |
| Turkish articles | `content/tr/yazilar/` |
| English case studies | `content/en/case-studies/` |
| Turkish case studies | `content/tr/vaka-analizleri/` |
| Images | `static/images/` → use as `/images/name.jpg` |
| Blank templates to copy | `templates-for-new-posts/` |
| Colours | `static/css/style.css` (top of file) |

## Adding a new article (on github.com)

1. Open the right folder, e.g. `content/en/writings/`.
2. Click **Add file → Create new file**.
3. Name it with lowercase and hyphens, e.g. `how-glass-is-made.md`.
4. Paste a template from `templates-for-new-posts/` and fill it in.
5. Click **Commit changes**. The site updates in about a minute.

## Linking an English article to its Turkish version

Give both files the same `translationKey`. A "Türkçe / English" link then appears on each.
Articles without a translation are fine — they simply show in one language.

## Equations

Add `math: true` to the top of the file. Inline: `\( \sigma_y \)` · Display: `$$ K_I = Y\sigma\sqrt{\pi a} $$`

## Comments (Cusdis) and newsletter (Buttondown)

Both stay hidden until you add your IDs in `hugo.toml`:

- `cusdis_app_id`: sign up at cusdis.com → add a website → "Embed Code" → copy the `data-app-id` value.
  New comments wait for your approval in the Cusdis dashboard (turn on email notifications there).
- `buttondown_username`: sign up at buttondown.com → your username.
  When you publish an article, send a short email from Buttondown with the title and link.
