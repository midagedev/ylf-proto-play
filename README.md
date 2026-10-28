# ylf-proto-play

Web builds of combat prototypes (Godot 4.7.2) for 「야간 유실물센터」.

- proto01 (v15, story demo): https://midagedev.github.io/ylf-proto-play/?v=15
  - v15: skill effects redone in a concise, flat graphic style (inspired by Studio Trigger / Guilty Gear): angular flat shapes in black / off-white / amber + one accent, stepped 12–15 fps motion, 1–3 frame impact frames, short cut-ins; press V to cycle v1 / v14 / v15
  - v14: 담's skill 「세 번 두드림」 (three knocks) with new effects (freeze-frame cut-in, keyhole door, shockwave, particles, hit-stop/camera punch, vibration on phones); finishers 담 「아퀴」 (끝매듭) and 하람 「옭매듭」 when the 사연 gauge is ~full; press V to compare with the old effects
  - title → prologue dialogue → 유실물센터 (case note) → 3 waves → boss 016 → return scene → result → 괴이 도감
  - v10: retry from the boss, saved progress ("이어서" on the title)
  - v9: after 016, a new note appears at the 접수대 → case 2 「활주로 빈 코트」 (canon ep01 boss, simplified): engine/silence phases over 4 planes, control-tower glass meter, 하람's bind holds the coat
  - two-person party (담 / 하람), switch (Q), Switch! skill after a parry, 하람's 묶기 bind skill
  - press P for auto-advance + auto-battle demo

All character art, enemy art, dialogue portraits, backgrounds and the closing illustration were made with an AI image tool (Grok Bot's built-in image generation). The battle backdrops and floors (market street, runway) and the coat boss are AI-generated too. Skill effect textures are AI-generated (Grok Bot's built-in image generation), and a few of 담's finisher frames were extracted from a short clip made with Grok Bot's built-in video generation. Sound effects are synthesized in code.

This repo holds exported builds only; it is built and published by Grok Bot on behalf of the owner. Source: midagedev/yagan-lost-and-found (games/proto01).
