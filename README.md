# Renatinho Birthday — V8 Y2K

Estrutura:
- `index.html` — experiência pública do Renatinho.
- `create.html` — área secreta dos amigos.
- `admin.html` — área privada da organizadora.
- `cards/cards.json` — cartões publicados.

No GitHub Pages, publique todos os arquivos descompactados mantendo a pasta `cards`.
Códigos atuais:
- Friends: `RENATINHO2000`
- Admin: `RENATO-ADMIN-2026`

A música de arquivo pode tocar no clique de abertura. YouTube/Spotify dependem das políticas de reprodução do provedor/navegador.


## V11
- Card Factory includes a SURPRISE ME button that randomizes Y2K themes, typography and message styling.


## V16
- Friend Card Factory is password-protected.
- Password: RENATINHO2000
- Supports up to 3 photos, photo styles, custom text color and two GIF positions.

## V18 — surgical fixes
- Card Factory is preserved from V16; only plain HTML navigation links were added.
- Love File is available immediately; it no longer requires opening every friend card.
- Fixed the JavaScript error in openFinal caused by an undefined `c`.
- Fixed the Old Internet Zone header spacing.
- Navigation uses normal HTML links rather than JavaScript.

## V19
- Adjusted only the OLD INTERNET ZONE layout.
- MSN Messenger, Friends Photo Booth, and Save to Floppy now occupy evenly spaced grid columns.
- Added responsive 2-column and 1-column breakpoints.
- Internal functionality of the three apps was not changed.

## V20
- Fixed the actual OLD INTERNET ZONE layout bug: `.legacy-zone` is no longer a grid container.
- MSN Messenger, Friends Photo Booth and Save to Floppy now share the intended three-column app row.
- Moved HOME into the site's top header instead of positioning it against the page/browser edge.
- No Card Factory, Love File, or app functionality changes.

## V21 — Friend Area fix
- Fixed the blurred Card Factory state shown when a previous session had already unlocked access.
- If `renatinhoFriendAccess=1` exists, the gate is hidden AND `factory-locked` is removed.
- No Card Factory fields, preview, themes, photos, GIFs, music, or export logic were changed.


## V22
- Adjusted only the HOME button position: vertically centered inside the site header.
- No changes to Card Factory, Love File, or Old Internet Zone.


## V23
- HOME is now structurally inside the header's existing right status panel.
- Removed the floating/absolute HOME navigation entirely.
- No other page functionality or layout was changed.


## Final language pass
- Site naming uses RENATO and RENATINHO.


## V24
- Removed HOME from the header completely.
- Added a standalone ★ HOME ★ desktop-style shortcut directly below the header.
- No other site functionality or layout was intentionally changed.

- Final naming rule: RENATO is used in main/personal copy; RENATINHO remains in selected Y2K/branded elements.
- The nickname Rê is not used.


## TEST BUILD — FAKE FRIEND CARDS
This build installs the fake cards generated from the Card Factory:
- GIGI / gigi-29aua
- BRUNO / bruno-29tkj

Their photos, GIF fields, themes, text colors, animation types, and YouTube music metadata are preserved exactly as generated.

This is a test build only; the original V26 remains unchanged.


## V27 — real GIF test
- Replaced the Tenor page URL in the two fake cards with a direct `.gif` image URL from GIPHY's documented image URL format.
- The same direct GIF is used in the top and bottom GIF slots for testing.
- Original V26 remains unchanged.


## V32 — Card Factory visual integration
- Based directly on the uploaded `renato2000-main.zip`.
- Preserves the successful card-loading approach used in the working test.
- Renders the Card Factory `cardConfig.theme`, `font`, `textColor`, `photoStyle`, and `emojis`.
- Renders `gifs.top` / `gifs.bottom` as actual image elements when the supplied URL is a usable image URL.
- Uses the real fake Card Factory cards as embedded test data when present.


## V34 — final micro-polish
- Added friend-specific message label.
- Added subtle theme stickers.
- Added organic photo rotations.
- Expanded GIF field fallbacks without changing card architecture.


## MEGA BLASTER FINAL
- Music choices: Spotify link, built-in Renato's Music Box, local audio file, or no music.
- GIF creation/upload removed from the friend flow.
- Legacy YouTube option removed.
- Spotify uses a visible official embed with user-initiated playback.
- Built-in Music Box contains original short instrumental loops bundled locally.
- Local audio upload capped at 10 MB in the Card Factory.


## V35 — music fixes
- Spotify parser accepts standard Spotify URLs including `/intl-pt/track/...` and Spotify URIs.
- Local Music Box files resolve against the deployed page URL.
- Added audio error feedback and a live music status in Card Factory.
- No GIF functionality added.
