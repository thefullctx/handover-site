# handover-site

The landing page for [Handover](https://github.com/thefullctx/handover): see
something, press one hotkey, and hand it to the AI agent you already have
running.

Live at **https://thefullctx.github.io/handover-site/**

## What's here

A single static page, no build step:

- `index.html`: the page, with its CSS and JS inline. Each section is a small
  working copy of a Handover feature you can try with the keyboard or mouse.
- `assets/`: fonts, icons and the share image, taken from the brand kit in the
  main repo (`brand/`).

To work on it, open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploying

GitHub Pages serves the `main` branch as is (`.nojekyll` turns off Jekyll
processing). Pushing to `main` publishes.

## License

MIT, like Handover itself. The Geist and Geist Mono fonts in `assets/` are under
the SIL Open Font License (`assets/OFL.txt`).
