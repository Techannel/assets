# Techannel assets

Public images used on Techannel's Civitai pages, served through jsDelivr.

| File | URL |
|---|---|
| Patreon banner (top of every model card) | `https://cdn.jsdelivr.net/gh/Techannel/assets@v1/banners/patreon-banner.png` |

`banners/patreon-banner.html` is the banner's source: a canvas drawing rendered to PNG with headless Chrome
(`google-chrome --headless=new --window-size=1600,400 --virtual-time-budget=8000 --screenshot=patreon-banner.png patreon-banner.html`).
A new design ships as a new tag (`@v2`, …), so pages pinned to an older tag never change underneath.
