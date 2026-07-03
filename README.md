# LearnMon Assets

Centralized asset library for LearnMon game (videos, images, UI, audio, and cinematics).

## Repository Structure

```
assets/
├── video/
│   ├── intro_v1.mp4
│   ├── guardian_terranor.mp4
│   └── starter_ceremony.mp4
│
├── images/
│   ├── lumii.png
│   ├── brighthaven_day.webp
│   └── environment/
│
├── ui/
│   ├── buttons/
│   ├── menus/
│   └── icons/
│
├── audio/
│   ├── music/
│   ├── sfx/
│   └── voices/
│
└── cinematics/
    └── guardian_cinematics/
```

## GitHub Pages Setup

1. Go to **Settings** → **Pages** (or use: https://github.com/hobohustlers/LearnMon-Assets/settings/pages)
2. Select:
   - **Deploy from a branch**
   - **Branch:** `main`
   - **Folder:** `/ (root)`
3. Save and wait ~1 minute for deployment

## Asset URL Base

Once GitHub Pages is enabled, your asset base URL will be:

```
https://hobohustlers.github.io/LearnMon-Assets/assets/
```

## Usage

In your game code, set:

```javascript
ASSET_CONFIG.remoteBase = "https://hobohustlers.github.io/LearnMon-Assets/assets/";
```

Then request assets like:

```
video/intro_v1.mp4
→ https://hobohustlers.github.io/LearnMon-Assets/assets/video/intro_v1.mp4

images/brighthaven_day.webp
→ https://hobohustlers.github.io/LearnMon-Assets/assets/images/brighthaven_day.webp

audio/music/theme.mp3
→ https://hobohustlers.github.io/LearnMon-Assets/assets/audio/music/theme.mp3
```

## Phase A Checklist

- [x] Repository created
- [x] Folder structure set up
- [ ] GitHub Pages enabled
- [x] Video uploaded to `assets/video/intro_v1.mp4`
- [ ] Video plays from GitHub Pages URL

## Phase B

Update `ASSET_CONFIG.remoteBase` and test video streaming.

## Phase C

Upload Guardian cinematics, Brighthaven artwork, UI packages, LearnMon art packages, and audio.

## Phase D

Convert LearnMon into a proper Android app using the hosted assets.

## Testing Your First Asset

Once GitHub Pages is enabled, test this URL in your browser:
```
https://hobohustlers.github.io/LearnMon-Assets/assets/video/intro_v1.mp4
```

If it plays, you're ready for Phase B! 🎬
