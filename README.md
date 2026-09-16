# Homestead: 3D Farm Tycoon — Legal & Support Pages

Public, login-free hosting for the player-facing legal pages of **Homestead: 3D Farm
Tycoon** (`com.homestead.farm`) by **Casayoung Development**.

This repository contains **no game source code** — only the published legal pages:

| Page | Purpose |
|---|---|
| [`privacy.html`](privacy.html) | Privacy Policy (the URL declared to Google Play) |
| [`PRIVACY_POLICY.md`](PRIVACY_POLICY.md) | Same policy as Markdown (source of truth) |
| [`terms.html`](terms.html) | Terms of Service |
| [`support.html`](support.html) | Player support & contact |
| [`index.html`](index.html) | Landing page for the portal |

## Privacy policy URL for Google Play

```
https://freeborn99.github.io/homestead-legal/privacy.html
```

Fallback (GitHub renders the Markdown page directly):

```
https://github.com/freeborn99/homestead-legal/blob/main/PRIVACY_POLICY.md
```

## Keeping these pages up to date

The pages are generated from the game repository, which owns the policy text as
`docs/PRIVACY_POLICY.md`. To republish after a policy change:

```powershell
# in the game repository
node tools/smoke-test.js                  # regenerates docs/privacy.html from the markdown
Copy-Item docs\index.html, docs\privacy.html, docs\terms.html, docs\support.html, docs\PRIVACY_POLICY.md <this repo>
git add -A; git commit -m "Update legal pages"; git push
```

## Contact

Casayoung Development — casayoung.dev@gmail.com
