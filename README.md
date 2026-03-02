# rroblak.github.io

GitHub Pages user site. Serves as the root domain for project sites hosted under `rroblak.github.io/*`.

## `.well-known/assetlinks.json`

Android [App Links](https://developer.android.com/training/app-links) verification file for the [Monkey Mind](https://github.com/rroblak/monkey-mind) meditation app. This allows Android to verify that `rroblak.github.io` deep links (e.g. `https://rroblak.github.io/monkey-mind/join?groupId=X`) should open directly in the app.

This file must live at the **domain root** (`/.well-known/assetlinks.json`), which is why it's in this repo rather than the monkey-mind repo.