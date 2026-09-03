---
name: spatial-vmd-display-system
description: 空间展陈与场景化设计系统。用于非标空间与买手店策展零售规划、VMD陈列点位（VP/PP/IP）设计、道具CMF矩阵与基座选材、展陈照明照度与色温工程、空间效果图生图Prompt撰写。当用户提到展陈、陈列、VMD、橱窗、动线、道具、基座、灯光照明、空间设计或空间效果图时触发。
---

# 空间展陈与场景化设计系统 (Spatial Display & Scenography System)

> ⚠️ **来源说明**：本 Skill 由 `docs/需求来源-GeminiSpark导出.md` 中记录的系统全景与实战案例产出反向还原，非原始 Instructions 全文。若你手中留有该 Skill 的原始正文，请直接覆盖本文件。

## 概述与核心哲学

本系统把文创产品放回真实空间，以"策展代替堆货，光线代替吆喝，触碰代替说服"为核心，为咖啡馆、民宿、非标商业与买手店规划从 1 平米微展台到整店动线的展陈方案，并输出可直接生图的空间效果图 Prompt。

## 核心方法论与工程支柱（五位一体）

### 1. 策展式零售规划 (Curatorial Retail Planning)

- **减速过渡区 (Decompression Zone)**：入口 1~1.5m 内不放主推商品，让顾客先完成环境适应。
- **动线与视线**：沿顾客自然右转习惯布线，消除视线死角，主展台落在动线首个视觉停留点。
- **触碰即成交**：为核心器物预留可自由拿取的试握位，触碰时长与成交率正相关。

### 2. VMD 三级点位体系 (VP / PP / IP)

- **VP (Visual Presentation) · 焦点**：橱窗或入口主展台，只讲 1 个故事、只推 1 个主角（如 50cm 糙面海蚀原石基座 + 展开的样品礼盒）。
- **PP (Point of Sales Presentation) · 场景**：把商品放回使用情境（如慢滴冷萃冰滴壶 + 盛放海盐与生豆的玻璃培养皿）。
- **IP (Item Presentation) · 单品**：同类单品平铺可拿取（如 3 只不同釉色粗陶杯平铺于原木挖槽浅盘）。

### 3. 道具 CMF 矩阵与基座工程 (Prop CMF & Pedestal)

- **道具配比沿用 60-30-10**：如糙面玄武岩原石底座（60%）+ 老船木台面（30%）+ 磨砂长虹亚克力微看板（10%）。
- **在地取材**：道具材质须与产品母体同源（海蚀原石、退役船木、渔网麻绳）。
- **陈列高度**：核心商品置于 80cm~140cm 黄金陈列带；重器物置于视线以下强化"沉稳"暗示。

### 4. 展陈照明工程 (Lighting Engineering)

- **显色性**：重点照明采用高显色光源 Ra > 95，保证釉色与金属氧化色真实还原。
- **色温**：暖白 3000K~3500K 匹配陶木质感；冷白慎用。
- **照度与反差**：环境漫反射光约 200 Lux，展台中心重点光约 800 Lux，形成约 4:1 的视觉引力反差。
- **防眩光**：射灯偏角 30° 打向台面，避免直射顾客视线与器物高光过曝。

### 5. 空间效果图 Prompt 工程 (Spatial Render Prompt)

```markdown
**Midjourney v6.0 Prompt**:
Architectural interior photograph of a 1-square-meter curated coffee merchandise display corner inside a minimalist coastal cafe. In the center, a rough-textured coastal boulder pedestal displays an open luxury coffee gift set and a handcrafted coarse pottery tumbler. A glass cold drip coffee apparatus stands nearby, alongside small petri dishes with sea salt crystals and roasted coffee beans. Weathered timber tabletop, soft warm 3000K spotlighting, high contrast ratio, tactile shadows, clean spatial composition, shot on Leica SL2, 8k resolution, photorealistic --ar 3:4 --style raw --v 6.0
```

## 产出与交付规范

1. **【展陈点位规划图】**：天花照明层、VP 焦点、PP 场景、IP 单品的分层布局。
2. **【道具 CMF 矩阵表】**：基座、台面、看板的材质配比与在地来源。
3. **【照明系统参数表】**：色温、显色指数 Ra、环境照度与重点照度、反差比、投射角度。
4. **【动线与触碰体验设计】**：减速过渡区、视线引导、试握位与防拥堵规范。
5. **【空间效果图生图 Prompt】**：结构化 Prompt（含相机、光线与参数）。

## 知识库依托

见 `knowledge/04-空间展陈与场景化设计.md`

## 参考案例

- `cases/02-海盐冷萃咖啡豆与粗陶随行杯礼盒.md`（模块四）
