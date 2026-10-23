# 港鐵小達人 MTR Mini 3D

Play: https://pakho2433.github.io/mtr-mini-3d/

A short first-person Three.js game about riding the Hong Kong MTR, made for a primary-school Humanities lesson (「輪與翼」 unit). It has five tasks: Octopus fare top-up, waiting behind the yellow line, giving up a seat and holding the handrail, spotting bad behaviour, and changing lines at Admiralty.

## Credits & licences
- **3D people**: Quaternius — *Ultimate Animated Character Pack* (CC0 1.0). https://quaternius.com/packs/ultimatedanimatedcharacter.html  
  Models used: OldClassy_Female, Suit_Male, Suit_Female, Casual_Male, Casual_Female, Casual2_Female, Casual3_Male, Worker_Female. Unused animations were pruned and the files compressed with gltf-transform (meshopt).
- **Textures**: ambientCG (CC0 1.0) — Terrazzo013, Tiles053, Metal009. https://ambientcg.com
- **MTR data**: MTR Corporation open data via DATA.GOV.HK — `mtr_lines_and_stations.csv`, `mtr_lines_fares.csv` (Octopus child fare, retrieved 2026-10-23).
- **Voice announcements**: generated with Microsoft Edge neural TTS voices (zh-HK-HiuMaanNeural, zh-HK-WanLungNeural, en-GB-RyanNeural) through the edge-tts tool.
- **Engine**: three.js r160 (MIT), loaded from jsDelivr.

URL options: `?q=0|1|2` locks the quality level (2 = floor reflection and shadows). If `q` isn't set, quality drops automatically when the frame rate stays below 40 fps.
