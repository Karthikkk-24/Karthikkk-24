# Banner backup

Previous profile banners, kept so you can revert anytime.

| File | Description |
| --- | --- |
| `banner-original.png` | Original LinkedIn-style banner (1584×396) |
| `banner-v2-glass-card.svg` | v2 source — glass code card + orbital glow design |
| `banner-v2-glass-card.png` | v2 rendered PNG |
| `banner-v3-brackets-focus.svg` | v3 source — brackets, FOCUS block, skill pills |
| `banner-v3-brackets-focus.png` | v3 rendered PNG |
| `../banner.svg` | **Active** banner source (editable) |
| `../banner.png` | **Active** banner rendered for GitHub README |

**Remote URL (original):** `https://user-images.githubusercontent.com/86278623/208313871-26849c79-9413-4a1e-b7cc-217f3a630528.png`

## Revert to the original banner

In `README.md`:

```markdown
![Karthik Shettigar banner](./assets/backup/banner-original.png)
```

## Revert to v2 (glass code card design)

Copy backup files to active paths, or point README directly:

```markdown
![Karthik Shettigar banner](./assets/backup/banner-v2-glass-card.png)
```

Or restore as active assets:

```bash
cp assets/backup/banner-v2-glass-card.svg assets/banner.svg
cp assets/backup/banner-v2-glass-card.png assets/banner.png
```

Then commit and push.
