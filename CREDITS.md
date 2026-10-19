# 素材來源與授權 · Credits

Research Studio · 語言研究室 v13（由 v12「木漏れ日 · 語言研究室」改版）。
署名內容沿用 v12 封裝內的 `README_繁體中文.txt` 與 `credits.txt`，並補上 v13 的修改說明。

## 原創內容

- 房間的 Blender 幾何與互動實作：本專案原創。
- 新的布面工作椅、書本、筆記本、筆：本專案原創。
- 都市夜景（高樓、街道、發光窗戶貼圖）：本專案原創，不代表任何真實地址。
- 天空球：生成的雲天影像，含白天、夕陽、藍調時段變化。

## 第三方 3D／PBR 素材

| 素材 | 作者／來源 | 授權 |
|---|---|---|
| modern_arm_chair_01 | [Poly Haven](https://polyhaven.com/a/modern_arm_chair_01) | CC0 |
| wood_floor | [Poly Haven](https://polyhaven.com/a/wood_floor) | CC0 |
| Cliffs Of Moher（山海景色） | PGSimulation (@lama99)，[Sketchfab](https://sketchfab.com/3d-models/cliffs-of-moher-01b5531d899e4a0fb01d96c21292e1c1) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

### Cliffs Of Moher：署名與修改說明

- 原作：**Cliffs Of Moher** by **PGSimulation (@lama99)**，CC BY 4.0。場景描繪愛爾蘭莫赫斷崖。
- 原始重建使用的影片素材來自 Jake Ladrigan：<https://youtu.be/5w124gCQV_I>
- v12 的改編：保留 13 個掃描網格與原始 UV，排除獨立的 Google 衛星平面網格；等比例放大 180 倍，並把原始 +Y 轉到世界方位 235°，配合虛構的工作室位置。另外加上海面、天空與光照。不宣稱測量精度，也不代表原作者背書。
- **v13 的修改**（為了放上 GitHub Pages）：
  - 7 張 4096² 底色貼圖縮成 2048²，從 JPEG 改成 WebP（品質 80）。
  - 幾何改用 Meshopt 壓縮（含頂點量化），沒有減面、沒有鏡像，也沒有換成照片平面。
  - 山海景色另外存成一個模型檔（`assets/model/mountain.glb`）。

## 程式與字型

| 項目 | 授權 |
|---|---|
| [three.js](https://threejs.org/) r170（含 GLTFLoader、OrbitControls、meshopt decoder；由 jsDelivr CDN 載入） | MIT License, Copyright © 2010–2024 three.js authors |
| [Noto Serif TC](https://fonts.google.com/noto/specimen/Noto+Serif+TC)（Google Fonts 載入） | SIL Open Font License 1.1 |

## 說明

兩種窗外景色都只是視覺布景；可以走動的範圍只有共用的房間和有欄杆的露台。
本專案不接任何後端或帳號，頁面裡的白板、番茄鐘資料只存在你自己瀏覽器的 `localStorage`。
