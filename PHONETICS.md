# Phonetics

English spelling is chaos. "Knight" has a silent k, silent gh. "Through" and "though" look similar but sound nothing alike.

Minni just spells things how they sound.

---

## The mapping

The script uses CMU's pronouncing dictionary to get phonemes, then converts each to one or two letters.

Vowels:

- cat, cup → **a**, **u**
- bed → **e**  
- day → **ei**
- bit, bee → **i**, **ee**
- go, law → **o**
- book, boot → **u**, **oo**
- my, cow, boy → **ai**, **au**, **oi**
- bird → **er**

Consonants are mostly obvious. The weird ones:

- "th" in *think* → **th**
- "th" in *this* → **dh** (voiced, different sound)
- "sh" → **sh**
- "ch" → **ch**
- "j" sound → **j**
- "ng" → **ng**
- "zh" (measure) → **zh**

---

## Examples

| English | Minni |
|---------|-------|
| knight | nait |
| through | throo |
| enough | inuf |
| translate | tranzleit |
| psychology | saikolujee |
| English | ingglish |

---

## Try it

```bash
pip install g2p_en

python minni.py "Hello world"
# hulo werld

python minni.py --debug "knight"
# Input:    knight
# Phonemes: N AY1 T
# Minni:    nait
```

The `--debug` flag shows the intermediate phonemes if you're curious.

---

## Audio samples

The `audio/` folder has some spoken examples using Italian TTS, which gets close to the right vowel sounds. Not perfect but gives you the idea.
