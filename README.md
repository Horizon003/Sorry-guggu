# Guggu Site — GitHub + Netlify (Tracks + Separate Sorry Audio)

## 1) Folder structure (exact)

```
repo-root/
  index.html
  README.md
  assets/
    audio/
      track1.mp3
      track2.mp3
      track3.mp3
      sorry.mp3
```

> IMPORTANT: Netlify (Linux) par **names & paths case-sensitive** hotay hain. `assets/audio/track1.mp3` bilkul exact hona chahiye.

## 2) Mapping (kis player par konsa audio chalega)

### Playlist / Songs section
- Track 1 card: **Dill cheese 🧀 guggu ko dedi**  → `assets/audio/track1.mp3`
- Track 2 card: **Dill jo guggu ka hay**         → `assets/audio/track2.mp3`
- Track 3 card: **Aya delhi wali girlfriend...** → `assets/audio/track3.mp3`

### Sorry / Slap section
- “Thapar” (slap) / “Ik baar aur suno” button → `assets/audio/sorry.mp3`

## 3) Agar aap ke paas separate sorry audio ho
Aap bas apni file ka naam **exact** `sorry.mp3` rakh kar is path me replace kar dein:

`assets/audio/sorry.mp3`

(baqi `track1/2/3` as-is rahay.)

## 4) Deploy
### A) Netlify Drag & Drop
1. Is folder ko zip karein
2. Netlify me drag & drop

### B) GitHub + Netlify
1. GitHub me repo banayein
2. Isi structure ke mutabiq files upload
3. Netlify → Add new site → Import from Git → repo select
4. Build command blank, Publish dir blank (root)
