# telixirx

Personal site with Hugo + PaperMod (lius.me style Profile homepage).

## Preview

```bash
hugo server
```

Open http://localhost:1313/

- Chinese: `/`
- English: `/en/`

## Edit later

| What | Where |
|------|--------|
| Name / subtitle / buttons | `hugo.yaml` → `languages.*.params.profileMode` |
| Nav menu | `hugo.yaml` → `languages.*.menu` |
| About page | `content/about.md` / `about.en.md` |
| Blog posts | `content/posts/*.md` (+ `.en.md` for English) |
| Avatar | `static/images/avatar.svg` |

Calendar and other extras can be added later as new buttons/pages.
