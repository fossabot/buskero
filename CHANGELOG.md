# Changelog

## 0.1.0 (2026-11-23)


### Features

* **app:** add chart rebuild, microphone lifecycle, and simulation tick ([3014fa7](https://github.com/efaj/buskero/commit/3014fa7b9015fd08ddb85b3956116c1b532cd7f4))
* **app:** add HUD, transport, MIDI device, and dialog UI sync helpers ([81c47d8](https://github.com/efaj/buskero/commit/81c47d83225544bbe299b8e30dd43afa64aad9ef))
* **app:** add playback transport, sax calibration, and boot preferences ([def9bf5](https://github.com/efaj/buskero/commit/def9bf535697274942148d47c3c95cedb0703e73))
* **app:** bootstrap state, DOM bindings, and formatting helpers in main.mjs ([a5f6b67](https://github.com/efaj/buskero/commit/a5f6b671412b86ac462e774c6a4389130d85f2de))
* **app:** wire song tree, renderer switching, event handlers, and init loop ([8fe17d4](https://github.com/efaj/buskero/commit/8fe17d4ca25286bc6f9615261f4f8ca548976a71))
* **audio:** add AudioWorklet processor and pitch detection Web Worker ([848abf0](https://github.com/efaj/buskero/commit/848abf0bdacb38262aff0b13dc72503227e5200c))
* **audio:** add MicrophoneInputController with raw-instrument defaults ([57f30f3](https://github.com/efaj/buskero/commit/57f30f3f806c8ea5d7f3bd53702335376d81ebf1))
* **audio:** add Web Audio synthesizer engine ([2e2a6fa](https://github.com/efaj/buskero/commit/2e2a6faa4695729dcb99496a77d9c17e4056ca08))
* **audio:** add Web MIDI input controller and virtual keyboard fallback ([990b519](https://github.com/efaj/buskero/commit/990b5191bc8c0d8ce1dddbbb13eee54bdc73da7e))
* **audio:** implement YIN pitch detector with weak-fundamental guard and tests ([9a0a28a](https://github.com/efaj/buskero/commit/9a0a28a3832988bafee7e8d34b0eb470090e3011))
* **game:** add rhythm game engine, scoring, loop state, and unit tests ([5fc2895](https://github.com/efaj/buskero/commit/5fc289595ee912156b2bfdcdc945fca3f7289cce))
* **instruments:** add piano keyboard highway mapper ([5910257](https://github.com/efaj/buskero/commit/5910257890a3a327d4d2308beed3539717d18391))
* **instruments:** add saxophone key-stack lanes, transpositions, and fingering table ([20168b2](https://github.com/efaj/buskero/commit/20168b21935e5507a12467665d6fb68ac909da36))
* **instruments:** add saxophone octave auto-fit, calibration, registry, and tests ([2db9520](https://github.com/efaj/buskero/commit/2db9520e53e1ee7941b78f5146fe50ba6db69def))
* **instruments:** add violin 8-lane 1st-position highway mapper ([e3b7130](https://github.com/efaj/buskero/commit/e3b71303acebf536f03696b2e507908e25b04ad7))
* **midi:** add built-in sample song framework and initial tracks ([204d85b](https://github.com/efaj/buskero/commit/204d85b8e55d137c4e2b35345fec5818ee7cb72d))
* **midi:** add GM program tables, binary I/O helpers, and tempo map ([e9357f8](https://github.com/efaj/buskero/commit/e9357f8c9d89bac441a424526b28ff0ccffd5ae6))
* **midi:** add intermediate practice sample songs ([2470776](https://github.com/efaj/buskero/commit/2470776cb68111b73914f2c323f6e93e2c334176))
* **midi:** add MIDI buffer builder and lead-track recommender ([668ebaf](https://github.com/efaj/buskero/commit/668ebaf0833f671781a0c21329d0176bf3204955))
* **midi:** add remaining sample songs and MIDI parser/song tests ([0726c29](https://github.com/efaj/buskero/commit/0726c29629775b886b7a64760ff8f951006e088a))
* **midi:** implement SMF binary parser (parseMidiBuffer) ([009ce03](https://github.com/efaj/buskero/commit/009ce032ba51fe5e82ea04f22ae9d3c9e6791a50))
* **server:** add zero-dependency static dev server with security headers ([816e136](https://github.com/efaj/buskero/commit/816e1368a4a6bcc8d3516388930978b3cc3c1d58))
* **storage:** add IndexedDB and in-memory song library adapters ([d4432b7](https://github.com/efaj/buskero/commit/d4432b7877f90fd827cdf12222a9aa95d6181191))
* **storage:** add preference sanitizers, score keys, and storage backend resolver ([50af604](https://github.com/efaj/buskero/commit/50af604c81664910876d61631659f5eb6eff374f))
* **storage:** implement createLocalStore persistence facade ([9f9343c](https://github.com/efaj/buskero/commit/9f9343c6d95e788625a4b9581d8a2adc81c81098))
* **storage:** implement createSongLibraryStore and storage unit tests ([0ed0007](https://github.com/efaj/buskero/commit/0ed00074e736467c7fb4fa2a845f4b343c02df54))
* **ui:** add 2D canvas Highway2DRenderer ([83ca480](https://github.com/efaj/buskero/commit/83ca4803c83b16fbd2ae81cd5e1bc2966d8dcfe0))
* **ui:** add BaseHighwayRenderer core canvas primitives and header bar ([0bd36ec](https://github.com/efaj/buskero/commit/0bd36ec0500fa820bc76f1c3c6b0df8c167703d6))
* **ui:** add GPU capability detection and 3D perspective projection math ([0786666](https://github.com/efaj/buskero/commit/078666604725e0fd1718d9e14fe427e58b60cb0c))
* **ui:** add layered CSS design system and responsive layout styles ([8806caa](https://github.com/efaj/buskero/commit/8806caa7ab2a76beac76afb583c66063ea8c12b2))
* **ui:** add saxophone intonation gauge to BaseHighwayRenderer ([a20c473](https://github.com/efaj/buskero/commit/a20c47302e73a93328a0ea488736e54e7966feba))
* **ui:** add semantic HTML app shell, dialogs, controls, and server integration test ([bb678c1](https://github.com/efaj/buskero/commit/bb678c18ae41773912035dfa0677357b875bdec3))
* **ui:** add song library tree model with unit tests ([34feb0c](https://github.com/efaj/buskero/commit/34feb0cc7b768dd26a2385bb8ad7192e76e96cc6))
* **ui:** add WebGL Highway3DRenderer and renderer test suite ([41689e8](https://github.com/efaj/buskero/commit/41689e83d51be1db119c50797da41120d4b2a868))
* **ui:** add WebGL shaders, color helpers, and MeshBatch for 3D highway ([0a0a750](https://github.com/efaj/buskero/commit/0a0a750913d851a4c4301f17bdffc0e7f1e0fe92))

## [0.1.0] (2026-11-23)

### Features

* **dsp:** move YIN pitch analysis to a dedicated `AudioWorklet` + `Web Worker` pipeline decoupled from visual FPS (`AnalyserNode` fallback preserved).
* **highway-3d:** add hardware-gated WebGL2/WebGL1 Guitar Hero-style 3D tilted highway (`Highway3DRenderer`) sharing the interchangeable `BaseHighwayRenderer` contract with `Highway2DRenderer` (`HighwayRenderer`), including automatic FPS watchdog fallback and `prefers-reduced-motion` support.
* **storage:** persist uploaded `.mid` / `.midi` files locally in `IndexedDB` (`buskero-library`) and preferences, mic/horn calibration, and personal-best track scores in `localStorage`.
* **mic:** automatically attempt microphone activation when switching to `Violin (Mic)` or `Saxophone (Mic)` (keeping mic active across mic instruments and stopping auto-managed mic on `Piano`).
* **privacy:** add local-only data processing disclosures in the footer and native `#legal-dialog` modal with live storage inspection and one-click local data erasure.
* **oss:** add `Makefile`, `tools/presubmit.mjs`, `tools/build_static.mjs`, `biome.json`, `.crenet-governance.json`, `docs/assets_ledger.json`, `LICENSE`, and GitHub Actions CI workflows.
