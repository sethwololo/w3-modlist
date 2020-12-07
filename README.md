# Sethwololo modlist Witcher 3 2020

## Passos iniciais

### Ajustes no arquivo user.settings

#### Uso de VRAM
  `
  [Rendering]
  TextureMemoryBudget=metade da VRAM da sua gpu (ex: "2048" para GPUs de 4GB)
  `

#### Telas diferentes de 16:9
  + 16:10: `uiVerticalFrameScale=1.1253`
  + 21:9 (não necessário na versão GOTY): `uiHorizontalFrameScale=1.3125`

#### Correções visuais relacionadas às sombras
  Para correção desses bugs use os seguintes valores:
  `
  [Rendering]
  CascadeShadowDistanceScale0=3
  CascadeShadowDistanceScale1=3
  CascadeShadowDistanceScale2=2.5
  CascadeShadowDistanceScale3=2
  `

  Para aumentar o desempenho sem uma perda de qualidade perceptível use o seguinte valor:
  `
  [Rendering]
  CascadeShadowmapSize=2048
  `

  Para corrigir o pop-in de sombras de objetos carregados por NPCs use o seguinte valor:
  `
  [Rendering]
  CharacterShadowsFallbackDistance=40
  `

  Para aumentar a fidelidade visual ao custo de alguns frames use essas configurações:
  `
  [Rendering]
  CascadeShadowDistanceScale0=4
  CascadeShadowDistanceScale1=4
  CascadeShadowDistanceScale2=3
  CascadeShadowDistanceScale3=2
  CascadeShadowQuality=4
  `

### Instalar o The Witcher 3 Mod Manager
  Automatiza o processo de instalação e gerenciamento de mods
  https://www.nexusmods.com/witcher3/mods/2678

### Instalar o script merger
  https://www.nexusmods.com/witcher3/mods/484
  
### Mod Limit Fix 
  https://www.nexusmods.com/witcher3/mods/3643

## Mods


### Base
  - Community patch base - https://www.nexusmods.com/witcher3/mods/3652
  - Community patch shared imports - https://www.nexusmods.com/witcher3/mods/2110
  - Community patch besserwisser - https://www.nexusmods.com/witcher3/mods/3163
  - All NPCs Scabbards - https://www.nexusmods.com/witcher3/mods/1569/

### Gameplay
  - Ghost Mode - https://www.nexusmods.com/witcher3/mods/992

### Tweaks
  - Immersive real-time cutscenes - https://www.nexusmods.com/witcher3/mods/4574
  - No dirty lens effect - https://www.nexusmods.com/witcher3/mods/347
  - No water droplets on screen - https://www.nexusmods.com/witcher3/mods/408
  - HairWorks on everything but Geralt's hair

### UI
  - Friendly HUD - https://www.nexusmods.com/witcher3/mods/365
  - Tweaks - https://www.nexusmods.com/witcher3/mods/2658
  - All Quest Objectives On Map Full - https://www.nexusmods.com/witcher3/mods/943
  - (Opcional) (Pode dar conflito com outros mods) Vladimir UI - https://www.nexusmods.com/witcher3/mods/5256
  - (Opcional) (Pode dar conflito com outros mods) E3 UI and HUD - https://www.nexusmods.com/witcher3/mods/2996

### Camera
  - Absolute Camera - https://www.nexusmods.com/witcher3/mods/856

### Iluminação
  - Willy Wonka's Verona (Base beta 12mb - Toussaint 6mb) - Discord Gudmods 4.0
  - W3 Reworked Lighting Project Beta - Discord Gudmods 4.0 (Pode dar alguns problemas com outros mods)
  - Immersive Lighting - https://www.nexusmods.com/witcher3/mods/3953?tab=files
  - Immersive Lighting Nudel - https://www.nexusmods.com/witcher3/mods/3953?tab=files
  - Immersive Lighting Nudel (sem toussaint) - https://mega.nz/file/aiQQ3ASB#LzF_H0J2Owb8C-_69xMvxaYEDQ_jBH336OauHss8e4s

### Animações
  - E3 Inspired Gameplay Mod - https://www.nexusmods.com/witcher3/mods/4525
  - 2014 Animation System - https://www.nexusmods.com/witcher3/mods/5273 (Não testei)

### Texturas
  - The Witcher 3 HD Reworked Ultimate - https://www.nexusmods.com/witcher3/mods/1021
  - BLOOD - https://www.nexusmods.com/witcher3/mods/900
  - New Starfields - https://www.nexusmods.com/witcher3/mods/5283
  - Fixed E3Reworked Quen - Discord Gudmods 4.0 #downloads
  - Meadows - An Efflorescent Grass Mod - https://www.nexusmods.com/witcher3/mods/4757

### Cabelo/Barba/Rosto/NPCS
  - Witchers Eyes Lore Friendly - https://www.nexusmods.com/witcher3/mods/2259
  - Yennefer concept hair - https://www.nexusmods.com/witcher3/mods/2567
  - Lore friendly Ciri - https://www.nexusmods.com/witcher3/mods/685
  - Triss (g)lorified - https://www.nexusmods.com/witcher3/mods/3223
  - Triss (g)lorified wardrobe - https://www.nexusmods.com/witcher3/mods/3722

## Addons
  - More Robes - https://www.nexusmods.com/witcher3/mods/2144
  - Hoods - https://www.nexusmods.com/witcher3/mods/4242


## Referências e créditos
  - https://forums.cdprojektred.com/index.php?threads/the-compendium-of-tweaks-and-fixes-for-the-pc-version.64211/
  - https://www.reddit.com/r/witcher/comments/ij30kz/witcher_3_perfection_modding_guide_ghostmode/
