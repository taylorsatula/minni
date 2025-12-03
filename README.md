# Minni

Old Norse for *memory*.

A writing system where English gets spelled phonetically and rendered in alien glyphs. Say "knight" out loud - it's "nait". That's what gets written. Someone who learns the 26 shapes can look at the glyphs and sound out English.

The font is a skin over regular ASCII. Underneath it's just letters.

---

## How it works

```bash
pip install g2p_en
python minni.py "Hello world"
# hulo werld
```

Put that in HTML with the Minni font applied and you get alien text that reads aloud as English.

```html
<style>
  @font-face {
    font-family: 'Minni';
    src: url('Minni.woff2') format('woff2');
  }
  .minni { font-family: 'Minni', monospace; }
</style>

<p class="minni">hulo werld</p>
```

---

## What's in here

`Minni.ttf` / `Minni.woff2` — the font

`minni.py` — translates English to phonetic spelling

`PHONETICS.md` — the spelling rules

`LINGUISTICS.md` — why the glyphs look the way they do

`Minni_reference.png` — cheat sheet

---

## The grid

9×9 pixels per glyph. Monospaced. 72 characters total - lowercase, uppercase (crowned), digits, punctuation.

---

Public domain. Part of MIRA.
