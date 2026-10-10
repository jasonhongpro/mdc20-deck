# ArLin MDC-20 deck (web)

This is the password-protected web version of the ArLin MDC-20 investor presentation, served by GitHub Pages.

`deck.enc` is AES-256-GCM encrypted. The browser decrypts it locally once the password is entered, and nothing in this repository is readable without the password.

The deck's source and the build script live in a separate private repository. To update this site, rebuild with `tools/build_site.py --out <this repo>` and push.

Live at https://jasonhongpro.github.io/mdc20-deck/
