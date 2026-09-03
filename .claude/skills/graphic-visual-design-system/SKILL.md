---
name: graphic-visual-design-system
description: 平面与视觉设计系统。用于包装平面排版蓝图规划、栅格与字阶模数规范、60-30-10配色与Pantone色彩工程、包装刀版展开面设计、工业级产品摄影与Midjourney/AI生图Prompt撰写。当用户提到包装设计、排版、版式、栅格、配色、Pantone、刀版、字体字阶、视觉规范、效果图或生图提示词时触发。
---

# 平面与视觉设计系统 (Graphic & Visual Design System)

> ⚠️ **来源说明**：本 Skill 由 `docs/需求来源-GeminiSpark导出.md` 中记录的系统全景与实战案例产出反向还原，非原始 Instructions 全文。若你手中留有该 Skill 的原始正文，请直接覆盖本文件。

## 概述与核心哲学

本系统把符号学系统输出的超级符号与超级话语，转化为可直接交付印厂的版式蓝图、色彩参数与刀版结构，并同步产出用于提案与电商主图的工业级 AI 生图 Prompt。核心原则："留白是奢侈品的主语，网格是克制的骨架。"

## 核心方法论与工程支柱（五位一体）

### 1. 色彩工程与 60-30-10 黄金律 (Color Engineering)

- **60% 主基调色**：承担整体气质与留白底色（如海盐米白 / 未漂白棉纸，Pantone 11-0601 TCX / `#F5F2EB`）。
- **30% 结构辅助色**：承担字体、边界与结构（如深海玄青 / 炭黑，Pantone 19-4013 TCX / `#1E252B`）。
- **10% 高光点缀色**：承担超级符号与视觉爆点（如红陶赭石 / 氧化红，Pantone 18-1440 TCX / `#A84A38`）。
- **交付纪律**：每色必须同时给出 Pantone TCX/C 色号与 HEX，并标注是印刷专色、烫印箔色还是屏幕用色。

### 2. 栅格版式蓝图与字阶模数 (Grid & Typographic Scale)

- **栅格制度**：包装展开面统一采用 12 栏栅格，标注天头地脚与出血（常规 3mm）。
- **呼吸区**：主展示面顶部预留 20%~25% 留白呼吸区。
- **字阶模数**：主标题、副标题、说明文、法定信息四级字阶，标注字体族、字重、字距（Tracking）与行距。
- **典型排布**：细英文字阶（品牌线 / 品类 / 刊号）在左上，超级符号居中，中文主标题在右下，底部承载净含量、产地经纬度与法定标识。

### 3. 包装刀版与展开面设计 (Dieline & Unfolded Layout)

- **盒型与材质**：给出盒型（天地盖硬盒 / 抽屉盒 / 折叠盒）、外径尺寸、灰板克重与裱纸克重（如 260×180×90 mm，1200g 工业灰板裱 157g 触感糙面特种纸）。
- **展开面逐面排版**：天盖、地盒、四侧墙、内盖彩蛋面、腰封分别给出内容与层级。
- **工艺标注**：烫金/烫哑金、击凸、UV、压痕折线、防爆线位置。
- **与叙事联动**：内盖彩蛋文字、封签短诗位置须与器物叙事系统输出对齐。

### 4. 微出版物与印刷品版式 (Zine & Insert Layout)

- 风琴折/6 折页/8 折页的折叠模数、压痕位与翻阅顺序。
- 故事卡尺寸规范（如 55mm × 85mm 糙面棉纸）与卡面栅格。

### 5. 工业级 AI 生图 Prompt 工程 (Production-Grade Image Prompt)

Prompt 必须结构化覆盖：**画面类型 → 主体与陈设 → 材质质感 → 光线色温 → 相机与镜头 → 分辨率与风格 → 参数**。

```markdown
**Midjourney v6.0 Prompt**:
Commercial studio product photography of a premium minimalist coastal coffee gift set, clean eye-level shot. On a light sandy travertine pedestal sits an open dark-charcoal textured gift box revealing a 350ml coarse clay travel tumbler with a leather sleeve, next to an unbleached kraft paper pouch of coffee beans labeled with elegant typography. A small wooden brass measuring spoon and a folded beige linen mini-zine rest alongside. Soft diffused 3200K morning sunlight, gentle realistic shadows, tactile textures of raw ceramics and matte paper, shot on Hasselblad H6D-100c, 8k resolution, photorealistic, minimal Japanese-Nordic aesthetic --ar 3:4 --style raw --v 6.0
```

- **纪律**：不写空泛形容词（"高级感"），只写可被相机与材质还原的名词与参数。

## 产出与交付规范

1. **【色彩工程表】**：60-30-10 配色、Pantone 与 HEX、专色/箔色/屏幕色标注。
2. **【栅格版式蓝图】**：12 栏栅格、留白呼吸区、四级字阶与字距行距参数。
3. **【包装刀版与展开面排版说明】**：盒型尺寸、材质克重、逐面内容与工艺标注。
4. **【印刷品与 Zine 版式规范】**：折页模数、压痕位、故事卡尺寸与卡面栅格。
5. **【工业级生图 Prompt】**：产品图与包装图的结构化 Prompt（含参数）。

## 生图 Prompt 使用去处

Prompt 可直接粘贴到以下任一工具执行（详见 `docs/生图提示词使用指南.md`）：Midjourney（Discord 或 midjourney.com，`/imagine`）、即梦 / 可灵 / 通义万相等国内工具（需去掉 `--ar --v --style` 参数，改用界面上的比例选项）、Adobe Firefly、Stable Diffusion（ComfyUI / WebUI）。

## 知识库依托

见 `knowledge/03-平面与视觉设计.md`

## 参考案例

- `cases/02-海盐冷萃咖啡豆与粗陶随行杯礼盒.md`（模块三）
