<p align="center">
  <img src="https://raw.githubusercontent.com/Bahia-Software/polypus/main/assets/logo.png" alt="Polypus logo" width="220">
</p>

<h1 align="center">Polypus — Tutorials</h1>

<p align="center">
  <strong>Interactive, beginner-friendly tutorials for Polypus: learn distributed quantum computing from scratch.</strong>
</p>

## What is this repository?

This is a **read-only mirror** of the [`tutorials/`](https://github.com/Bahia-Software/polypus/tree/main/tutorials) folder from the main [Polypus](https://github.com/Bahia-Software/polypus) repository. It exists so you can get just the tutorial notebooks — without cloning the full Rust workspace.

It is synced automatically, once per Polypus release, so the notebooks here always match exactly what `pip install polypus-quantum` gives you at that version. **Don't open pull requests or edit files here directly** — they'll be overwritten on the next sync. Report issues, suggest fixes, or contribute new tutorials on the [main repository](https://github.com/Bahia-Software/polypus/issues) instead.

## Getting started

```bash
git clone https://github.com/Bahia-Software/polypus-tutorials.git
cd polypus-tutorials
pip install -r requirements.txt
jupyter lab
```

Then open [`00_bienvenida.ipynb`](00_bienvenida.ipynb) — it explains how the series works and routes you to the right starting point depending on your programming/quantum-computing background.

## License

Same as Polypus itself: [European Union Public Licence, version 1.2 (EUPL-1.2)](https://github.com/Bahia-Software/polypus/blob/main/LICENSE).
