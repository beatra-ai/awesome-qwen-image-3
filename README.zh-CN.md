# Awesome Qwen Image 3.0

[English](./README.md) | 简体中文 | [日本語](./README.ja.md)

> 👉 也看看 [Awesome Wan 3.0 Video](https://github.com/beatra-ai/awesome-wan-3-video)

Qwen Image 3.0 的真实案例，每条都附完整提示词，可以在 Agent 里复现。

下面每条案例都在 Beatra 上用这个模型实际生成，提示词逐字照录，每张卡片都附任务号。

在你的 Agent 里直接复现: `npx skills add beatra-ai/ai-image-generator-skill` · [beatra.ai](https://beatra.ai/?utm_source=github&utm_medium=cases_list&utm_campaign=awesome-qwen-image-3)

## 目录

- [文字排版与海报](#typography-posters)
- [商品图与场景](#ecommerce)
- [局部编辑与换背景](#editing)
- [多张参考合成](#multi-reference)
- [插画与风格](#illustration)
- [虚构人像](#portraits)
- [信息图与图表](#infographics)

<a id="typography-posters"></a>

## 文字排版与海报

### 1. Brightmoss 图标与字标

一张平面的 Brightmoss 字标，展示 Qwen Image 3.0 Pro 把短英文名放在干净的标志里。

<p align="center"><img src="assets/q01.webp" width="800" alt="暖米色平面板上有一枚绿色图标和 Brightmoss 字标。由 Beatra AI 生成。"></p>

*暖米色平面板上有一枚绿色图标和 Brightmoss 字标。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 Pro 做一张暖米色的平面品牌板：深绿圆角图标里放豆与叶的符号，旁边是 Brightmoss 字标。只用两色，不要其他字。
```

提示词：

```text
Refine this accepted Brightmoss logo into a two-part brand presentation on one flat warm cream background (#F4EEE2). Left: an app icon, a solid rounded square in deep forest green (#1F4D3A) with the same coffee-bean-and-leaf symbol from the image centered inside in cream, generous padding, no text in the icon. Right: a horizontal lockup, the same green bean-and-leaf symbol placed to the left of the exact word "Brightmoss" in the same bold humanist sans-serif lettering, forest green, vertically centered with the symbol. Keep the symbol shape and the wordmark letterforms identical to the source. Flat vector, maximum two colors, no gradients, no shadows, no mockup, no tagline, no other text.
```

Qwen Image 3.0 Pro · 文生图 · 1280×723

在 Beatra 上生成 · 任务 task_mcp_33b755587a76a7bcb1bc5874324c2a4c9738a6fc

### 2. 北璃渡轮海报

一张奶油色渡轮海报，展示 Qwen Image 3.0 把英文和中文放在对应的位置。

<p align="center"><img src="assets/q02.webp" width="800" alt="奶油色海报上有一艘深青色渡轮，以及 NORTHGLASS、FERRY 和北璃渡轮。由 Beatra AI 生成。"></p>

*奶油色海报上有一艘深青色渡轮，以及 NORTHGLASS、FERRY 和北璃渡轮。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一张竖版奶油色渡轮海报：深青色的船，上方写 NORTHGLASS 和 FERRY，船下面写北璃渡轮。不要其他字。
```

提示词：

```text
Vertical printed travel poster, cream paper, a simple flat illustration of a dark teal ferry on pale grey water under a wheat-colored sun, generous empty margin. Exact text only, perfectly spelled, no extra letters anywhere: NORTHGLASS in large bold black sans-serif at the top, FERRY directly under it in the same typeface, and the four Chinese characters 北璃渡轮 centered under the boat in a clean black serif. No dates, no logos, no watermark, no people.
```

Qwen Image 3.0 · 文生图 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_3ae36b5a0a40614b79dc862d0bb0f47c7d703480

### 3. Hearthlane 市集海报

一张横版市集海报，展示 Qwen Image 3.0 画出一个英文名和一行中文。

<p align="center"><img src="assets/q03.webp" width="800" alt="宽幅奶油色海报上有一个水果摊、HEARTHLANE 和周末市集。由 Beatra AI 生成。"></p>

*宽幅奶油色海报上有一个水果摊、HEARTHLANE 和周末市集。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一张宽幅奶油色市集海报：中间一个小水果摊，上方写 HEARTHLANE，底部写周末市集。不要其他词。
```

提示词：

```text
Wide market poster, warm cream background, a small centered illustration of a wooden stall with green pears and a rust-striped awning, lots of empty space. Exact text only, perfectly spelled: HEARTHLANE in large dark-green serif across the top, and the four Chinese characters 周末市集 centered at the bottom in the same dark green. No other words, numbers, logos, or watermarks.
```

Qwen Image 3.0 · 文生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_ed1fe7fb9bb09b117ebce535beb68127861fa116

### 4. 灯园乐队海报

一张海军蓝音乐会海报，展示 Qwen Image 3.0 把双语标题放在一盏灯笼周围。

<p align="center"><img src="assets/q04.webp" width="800" alt="海军蓝海报上有一盏琥珀色灯笼，以及 LUMEN ORCHARD 和灯园乐队。由 Beatra AI 生成。"></p>

*海军蓝海报上有一盏琥珀色灯笼，以及 LUMEN ORCHARD 和灯园乐队。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一张海军蓝音乐会海报：中间一盏琥珀色纸灯笼，上方写 LUMEN ORCHARD，灯笼下面写灯园乐队。不要日期，也不要其他字母。
```

提示词：

```text
Minimal concert poster, deep navy background, one round paper lantern glowing amber in the center. Exact text only, perfectly spelled: LUMEN ORCHARD in cream serif capitals near the top, and the four Chinese characters 灯园乐队 in cream under the lantern. No dates, no other letters, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_430d142962b0c29b18cb70ac2a6fa3f4a458317b

### 5. 纸雀书展海报

一张书展海报，展示 Qwen Image 3.0 在线描周围放上三行中英标题。

<p align="center"><img src="assets/q05.webp" width="800" alt="方形海报上有一本打开的书的线描，以及 PAPER FINCH、PRESS 和纸雀书展。由 Beatra AI 生成。"></p>

*方形海报上有一本打开的书的线描，以及 PAPER FINCH、PRESS 和纸雀书展。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一张方形米白海报，上面是一本打开的书的线描。字只有三行：PAPER FINCH、PRESS 和纸雀书展。
```

提示词：

```text
Square book-fair poster, off-white paper, a single black line drawing of an open blank book, lots of margin. Exactly three lines of text, perfectly spelled, and no other letters anywhere. Top line: PAPER FINCH in bold black sans-serif. Middle line, directly under it: PRESS, spelled P-R-E-S-S, the first letter is P. Bottom line: the four Chinese characters 纸雀书展. Do not write DRESS. No logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 1:1

在 Beatra 上生成 · 任务 task_mcp_fde63ad38a445a53a0722db22d76c2c373a98e7c

### 6. 苇岸茶饮价目板

一块咖啡馆价目板，展示 Qwen Image 3.0 用三种字号放上中文和英文。

<p align="center"><img src="assets/q31.webp" width="800" alt="胡桃木框里的暗绿色价目板，字是苇岸茶饮价目、REEDBANK、云雾 CLOUD、桂花 OSMANTHUS 和焙茶 HOJICHA。由 Beatra AI 生成。"></p>

*胡桃木框里的暗绿色价目板，字是苇岸茶饮价目、REEDBANK、云雾 CLOUD、桂花 OSMANTHUS 和焙茶 HOJICHA。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 做一块竖的咖啡馆价目板，胡桃木框。字只有苇岸茶饮价目、REEDBANK、云雾 CLOUD、桂花 OSMANTHUS 和焙茶 HOJICHA。
```

提示词：

```text
Photoreal wooden cafe menu board, dark walnut frame, cream painted lettering on a slate-green board, photographed straight-on, even shop light. Exact text only, perfectly spelled, no extra letters, no prices, no logos, no watermark: large cream serif at the top 苇岸茶饮价目, directly under it in smaller cream sans-serif capitals REEDBANK, then three drink lines in a smaller size with Chinese then English on the same line, 云雾 CLOUD, 桂花 OSMANTHUS, 焙茶 HOJICHA. No other words or numbers.
```

Qwen Image 3.0 · 文生图 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_c927b4b70919f32fb511070101565a7937dd38bc

### 7. 河灯夜集票根

一张竖票根，展示 Qwen Image 3.0 把中文标题、英文副标题和日期叠在一起。

<p align="center"><img src="assets/q32.webp" width="800" alt="一张奶油色票根，上面有纸灯笼线描，以及河灯夜集、RIVER LANTERN 和 08 OCT。由 Beatra AI 生成。"></p>

*一张奶油色票根，上面有纸灯笼线描，以及河灯夜集、RIVER LANTERN 和 08 OCT。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 做一张竖的奶油色票根，上面一盏纸灯笼线描。字只有河灯夜集、RIVER LANTERN 和 08 OCT。
```

提示词：

```text
Vertical event ticket stub, cream paper, perforated top edge, a small simple drawing of one paper lantern, lots of empty margin. Exact text only, perfectly spelled, no extra letters: large bold black serif at the top 河灯夜集, subtitle under it in smaller sans-serif RIVER LANTERN, date at the bottom in small tracking 08 OCT. No other words, numbers, logos, or watermarks.
```

Qwen Image 3.0 · 文生图 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_132e3a0b9aad13a093b2f34af8e4fb2127317a70

<a id="ecommerce"></a>

## 商品图与场景

### 8. 冬夜的手冲咖啡

一张冬夜手冲静物，展示 Qwen Image 3.0 把商品照片的季节改成冬夜。

<p align="center"><img src="assets/q06.webp" width="800" alt="同一套手冲器具，现在在窗边的雪夜里。输入的照片也是由 Beatra AI 生成。"></p>

*同一套手冲器具，现在在窗边的雪夜里。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张手冲咖啡照片：鼠尾草绿的咖啡器具保持原样，把场景改成下雪的冬夜。
```

提示词：

```text
[edit] Change the season and time of day to a cozy winter evening. Keep the ceramic pour-over coffee set exactly as it is: the sage-green dripper with its paper filter and handle on the glass carafe of coffee, the sage-green mug, the speckled cream sugar bowl, the coffee beans, the oak table, and the camera angle and positions of every object. Outside the window it is now dusk with snow falling, snow-covered branches and a deep blue evening sky; a little snow rests on the window frame. Replace the summer sunlight with warm indoor lamplight from the right and soft candlelight, gentle warm glow on the ceramics, a thin wisp of steam rising from the mug, and swap the green leaves in the glass jar for a few bare winter twigs with small red berries. Warm amber and deep blue color contrast, photoreal lifestyle photography. No people, no text, no logos.
```

Qwen Image 3.0 · 图片编辑 · 616×458

在 Beatra 上生成 · 任务 task_mcp_9e6bd9541f728564e941e08748f6a7da4ef5dacc

### 9. Siltjar 辣椒酱瓶

一张酱瓶的商品照片，展示 Qwen Image 3.0 画出虚构商品和只有一个词的标签。

<p align="center"><img src="assets/q07.webp" width="800" alt="一只陶红色瓶子，黑盖，奶油色标签上写着 SILTJAR。由 Beatra AI 生成。"></p>

*一只陶红色瓶子，黑盖，奶油色标签上写着 SILTJAR。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一张虚构辣椒酱瓶的商品图，放在石灰石板上。奶油色标签上只有 SILTJAR。
```

提示词：

```text
Photoreal studio product photo of one fictional hot-sauce bottle on a pale limestone slab. The bottle is short, matte clay-red ceramic with a black screw cap and a plain cream label. The label carries only the exact word SILTJAR in black serif, perfectly spelled, once. Soft window light from the left, a few dried chili peppers beside the bottle, shallow depth of field, no hands, no other text, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 1:1

在 Beatra 上生成 · 任务 task_mcp_311c592f739e31aa31e2d5bed3b42850b7a6ad4b

### 10. 燕麦色帆布鞋

一张目录式的帆布鞋照片，展示 Qwen Image 3.0 做没有标志的商品图。

<p align="center"><img src="assets/q08.webp" width="800" alt="暖灰色背景上有一只燕麦色低帮鞋，生胶大底。由 Beatra AI 生成。"></p>

*暖灰色背景上有一只燕麦色低帮鞋，生胶大底。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一张虚构低帮帆布鞋，燕麦色鞋面、生胶大底，暖灰色背景。不要标志，也不要字。
```

提示词：

```text
Photoreal product photo of one fictional low-top sneaker, three-quarter view, on a seamless warm-grey cyclorama. The shoe is oatmeal canvas with a gum rubber sole, cream laces, and a small blank heel tab. No wordmark, no logo, no text anywhere. Soft overhead daylight, crisp but gentle shadow, commercial catalog lighting. No people, no hands, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 1:1

在 Beatra 上生成 · 任务 task_mcp_41fa7eafe76d178f9fdac8d5420e62dd78587068

### 11. 橡木桌上的黄铜蜡烛罐

一张桌面蜡烛静物，展示 Qwen Image 3.0 画出一个没有标签的简单商品外形。

<p align="center"><img src="assets/q09.webp" width="800" alt="深色橡木上有一只矮黄铜罐，里面是奶油色的蜡，旁边一枝迷迭香。由 Beatra AI 生成。"></p>

*深色橡木上有一只矮黄铜罐，里面是奶油色的蜡，旁边一枝迷迭香。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一张桌面照片：深色橡木上有一只虚构的黄铜蜡烛罐，烛芯未点燃，旁边一枝迷迭香。不要标签，也不要字母。
```

提示词：

```text
Photoreal tabletop photo of a fictional candle: a low brass tin of cream soy wax with one unlit cotton wick, sitting on dark oak. Beside it, a sprig of dried rosemary. The tin has no label and no letters. Warm side light, shallow depth of field, catalog still life. No people, no hands, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 4:3

在 Beatra 上生成 · 任务 task_mcp_341f4873b3d3cb190bc4a82588df5b1db8bc2312

### 12. 燕麦色亚麻包和一只梨

一张生活场景里的托特包，展示 Qwen Image 3.0 把一件商品放进安静的房间。

<p align="center"><img src="assets/q10.webp" width="800" alt="一只未染色的亚麻托特包立在浅色水磨石上，旁边一只青梨。由 Beatra AI 生成。"></p>

*一只未染色的亚麻托特包立在浅色水磨石上，旁边一只青梨。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一张生活场景：一只虚构的燕麦色亚麻托特包立在浅色水磨石上，靠着白墙，旁边一只青梨。不要图案，也不要字。
```

提示词：

```text
Photoreal lifestyle product photo of a fictional heavy linen tote bag standing upright on a pale terrazzo floor against a white wall. The bag is undyed oat linen with two short cotton handles and a small rectangular patch pocket. No print, no letters, no logo. Morning light from the left, a single green pear on the floor beside the bag. No people, no hands, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 3:4

在 Beatra 上生成 · 任务 task_mcp_62d074025fb6e065bd7b0dd4d9aa80f40e72ca97

### 13. 湿石上的 SOLUM 精华瓶

湿石上的一只精华瓶，展示 Qwen Image 3.0 画出一个虚构商品，标签是 SOLUM。

<p align="center"><img src="assets/q33.webp" width="800" alt="一只磨砂玻璃精华瓶，白色泵头，标签是 SOLUM，立在湿的深色石头上。由 Beatra AI 生成。"></p>

*一只磨砂玻璃精华瓶，白色泵头，标签是 SOLUM，立在湿的深色石头上。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一只虚构的磨砂玻璃精华瓶，白色泵头，立在深色湿石头的浅水里。标签只有 SOLUM，不要连字符。
```

提示词：

```text
Photoreal commercial studio product photo of one fictional frosted-glass serum bottle, square shoulders, white pump, standing in a shallow pool of clear water on dark wet stone, gentle circular ripples around the base, soft high-key beauty lighting, generous empty margin on all four sides, subject centered. A small cream square label on the bottle shows only the single word SOLUM in black sans-serif capitals as five letters together, no hyphen, no space, no extra marks, and no other letters. No extra bottles, no hands, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_747899488daf1c608e01a3103a86f767cebd0a01

### 14. 石灰石上的鼠尾草绿耳机

一张鼠尾草绿耳机的目录照片，展示 Qwen Image 3.0 做出没有标志的商品图。

<p align="center"><img src="assets/q34.webp" width="800" alt="鼠尾草绿的头戴式耳机，钢质头带，燕麦色绒面耳垫，放在一块石灰石上。由 Beatra AI 生成。"></p>

*鼠尾草绿的头戴式耳机，钢质头带，燕麦色绒面耳垫，放在一块石灰石上。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一副虚构的鼠尾草绿头戴式耳机，钢质头带，燕麦色绒面耳垫，放在浅色石灰石上。不要标志，也不要文字。
```

提示词：

```text
Photoreal catalog photo of one fictional pair of closed-back over-ear headphones, matte sage ear cups, a thin brushed-steel headband, oat suede ear pads, no logo and no text anywhere on the product. Three-quarter view, centered on a pale limestone slab, soft studio light, generous empty margin on all four sides. No people, no hands, no extra objects, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_30b180b44416554aedc800ae7ea54ded5091b344

<a id="editing"></a>

## 局部编辑与换背景

### 15. Siltjar 瓶子换了台面

一张前后对比，展示 Qwen Image 3.0 换掉瓶子的台面，并留下 SILTJAR 标签。

<p align="center"><img src="assets/q11.webp" width="800" alt="左边是石灰石台上的瓶子，右边是同一只瓶子放在深绿色瓷砖台上。输入的照片也是由 Beatra AI 生成。"></p>

*左边是石灰石台上的瓶子，右边是同一只瓶子放在深绿色瓷砖台上。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张 Siltjar 酱瓶照片：瓶子、瓶盖、干辣椒和 SILTJAR 标签保持不变，把台面换成深绿色瓷砖。
```

提示词：

```text
Keep the clay-red ceramic bottle, its black cap, the dried chilies, and the cream label exactly as they are. The label must still read SILTJAR, spelled S-I-L-T-J-A-R, and no other letters. Replace the limestone slab and the beige wall with a dark green glazed-tile counter and a softly blurred kitchen. Do not change the bottle shape. No extra text, no logos, no watermark.
```

Qwen Image 3.0 · 图片编辑 · 1K · 1:1

在 Beatra 上生成 · 任务 task_mcp_311c592f739e31aa31e2d5bed3b42850b7a6ad4b, task_mcp_f727724c879a642a71c11f8101a5ad523d00618d

### 16. 鞋面改成了靛蓝色

一张前后对比，展示 Qwen Image 3.0 只给帆布鞋的鞋面重新上色。

<p align="center"><img src="assets/q12.webp" width="800" alt="左边是燕麦色帆布鞋，右边是同一只鞋，鞋面变成了深靛蓝。输入的照片也是由 Beatra AI 生成。"></p>

*左边是燕麦色帆布鞋，右边是同一只鞋，鞋面变成了深靛蓝。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张燕麦色帆布鞋照片：角度、生胶底、鞋带和空白后跟标保持不变，只把帆布鞋面改成深靛蓝。
```

提示词：

```text
Keep the same low-top sneaker, the same three-quarter angle, the gum rubber sole, the cream laces, and the blank heel tab. Change only the canvas upper from oatmeal to deep indigo. Do not add text, a logo, a wordmark, or a watermark. No people, no hands.
```

Qwen Image 3.0 · 图片编辑 · 1K · 1:1

在 Beatra 上生成 · 任务 task_mcp_41fa7eafe76d178f9fdac8d5420e62dd78587068, task_mcp_bb1110e3cbe7370acc461410a3b7c9274a011e13

### 17. 托特包换到雨中的门口

一张前后对比，展示 Qwen Image 3.0 把同一只托特包从白房间挪到下雨的门口。

<p align="center"><img src="assets/q13.webp" width="800" alt="左边是白房间里的托特包，右边是同一只包和那只梨，在下雨的门口。输入的照片也是由 Beatra AI 生成。"></p>

*左边是白房间里的托特包，右边是同一只包和那只梨，在下雨的门口。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张燕麦色亚麻包照片：包、贴袋、提手和梨都保留，把它们挪到下雨的店门口，后面是一扇深绿色的门。
```

提示词：

```text
Keep the undyed oat linen tote, its patch pocket, its two short handles, and the green pear. Replace the white wall and the terrazzo floor with a rainy shop doorway: wet grey stone under the bag and a dark green wooden door behind it. Overcast daylight. No text, no logo, no watermark, no people, no hands.
```

Qwen Image 3.0 · 图片编辑 · 1K · 3:4

在 Beatra 上生成 · 任务 task_mcp_62d074025fb6e065bd7b0dd4d9aa80f40e72ca97, task_mcp_1cf17a60d29c226d916229738e6b7dff99576ed7

### 18. 桌上拿掉了茶杯和笔

一张前后对比，展示 Qwen Image 3.0 从桌面照片里去掉茶杯和笔。

<p align="center"><img src="assets/q35.webp" width="800" alt="左边的胡桃木桌上有打开的笔记本、黄铜剪刀、一只奶油色茶杯和两支黑笔。右边茶杯和笔没了，笔记本和剪刀还在。输入的照片也是由 Beatra AI 生成。"></p>

*左边的胡桃木桌上有打开的笔记本、黄铜剪刀、一只奶油色茶杯和两支黑笔。右边茶杯和笔没了，笔记本和剪刀还在。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张书桌照片：去掉奶油色茶杯和两支黑笔。胡桃木桌、打开的笔记本、黄铜剪刀和机位保持不变。
```

提示词：

```text
Keep the walnut desk, the open blank notebook, the brass scissors, the window light, and the same camera angle. Remove the cream ceramic cup and both black pens completely. Do not add new objects. No text, no logos, no watermark, no hands.
```

Qwen Image 3.0 · 图片编辑 · 2K · 4:3

在 Beatra 上生成 · 任务 task_mcp_2e17ff31a1137a5896558ca57a247d1bdabf6198, task_mcp_e8eff740f4302717e414d1361b4f3faa077dab56

### 19. 正午小巷改成傍晚薄雪

一张前后对比，展示 Qwen Image 3.0 把夏日小巷改成傍晚薄雪，建筑还在。

<p align="center"><img src="assets/q36.webp" width="800" alt="左边是明亮夏日正午的小巷。右边是同一条小巷的傍晚，路边和人行道有薄雪，窗户和路灯亮了，窗台花箱仍有绿叶。输入的照片也是由 Beatra AI 生成。"></p>

*左边是明亮夏日正午的小巷。右边是同一条小巷的傍晚，路边和人行道有薄雪，窗户和路灯亮了，窗台花箱仍有绿叶。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张小巷照片：建筑、木窗板、门、自行车和机位保持不变。改成傍晚，路边和人行道有薄雪，窗户和路灯亮着。
```

提示词：

```text
Keep the exact same cobblestone lane, the same plaster buildings, shutters, doors, bicycle, and camera position. Change only the season and time of day to a snowy evening: blue hour, warm window light, a light covering of snow on the street and ledges, falling snow. No people, no cars, no readable signs, no letters, no logos, no watermark.
```

Qwen Image 3.0 · 图片编辑 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_7b7da46f37b24ab2619dc76ac34abddffdd2abc7, task_mcp_a36f684023317a21916a2df525593b22e69b611c

### 20. 店招改成南窗纸店

一张前后对比，展示 Qwen Image 3.0 换掉店招上的四个字。

<p align="center"><img src="assets/q37.webp" width="800" alt="左边的挂牌是青石书屋。右边同一家店的挂牌改成了南窗纸店。门、窗和蕨类盆栽不变。输入的照片也是由 Beatra AI 生成。"></p>

*左边的挂牌是青石书屋。右边同一家店的挂牌改成了南窗纸店。门、窗和蕨类盆栽不变。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张店面：把挂牌上的四个字从青石书屋改成南窗纸店。门、窗、蕨类盆栽和机位保持不变。
```

提示词：

```text
Keep the dark green wooden storefront, the hanging wooden sign shape, the closed door, the potted fern, and the same camera. Change only the four cream characters on the sign from 青石书屋 to exactly 南窗纸店, perfectly spelled, and no other letters. No people, no logos, no watermark, no extra text.
```

Qwen Image 3.0 · 图片编辑 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_047d4b47b255ce306027120018abdd0150ad19af, task_mcp_f99ea4c0f8f6408eb3c78d66ec27e7afcc0174e9

<a id="multi-reference"></a>

## 多张参考合成

### 21. 酱瓶和蜡烛放在一起

一张静物，展示 Qwen Image 3.0 把两张参考图里的酱瓶和蜡烛合成到一起。

<p align="center"><img src="assets/q14.webp" width="800" alt="陶红色瓶子和黄铜蜡烛罐在同一张橡木桌上。由 Beatra AI 生成。"></p>

*陶红色瓶子和黄铜蜡烛罐在同一张橡木桌上。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0，拿 Siltjar 酱瓶照片和黄铜蜡烛照片，把两者放到深色橡木桌上，SILTJAR 标签保持原样。
```

提示词：

```text
One catalog still life on a dark oak table in warm side light. Place the hot-sauce bottle from the first image beside the brass candle tin from the second image. Keep the bottle's clay-red body, black cap, and the label spelling SILTJAR exactly. Keep the candle's low brass tin and single unlit wick. No other text, no logos, no watermark, no hands.
```

Qwen Image 3.0 · 图生图 · 1K · 4:3

在 Beatra 上生成 · 任务 task_mcp_0fefd99194c4683cedb0377d60ab5d3d3d473b03

### 22. 雨衣狐狸站在面包店前

一张插画，展示 Qwen Image 3.0 把雨衣狐狸放到第二张参考图里的面包店前。

<p align="center"><img src="assets/q15.webp" width="800" alt="一只穿黄色雨衣的赤狐站在有黄色遮阳篷的面包店前。由 Beatra AI 生成。"></p>

*一只穿黄色雨衣的赤狐站在有黄色遮阳篷的面包店前。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0，拿雨衣狐狸的画和面包店的画，把狐狸放在那家店门前的人行道上，保留黄色遮阳篷和自行车。
```

提示词：

```text
A flat editorial illustration. Place the red fox in the yellow raincoat and green boots from the first image on the sidewalk in front of the bakery from the second image. Keep the fox's coat, boots, and face recognizable. Keep the bakery's butter-yellow awning, round window of loaves, and the bicycle. No text, no letters, no logos, no watermark.
```

Qwen Image 3.0 · 图生图 · 1K · 16:9

在 Beatra 上生成 · 任务 task_mcp_7957b46f4d4f13057b8c97786dd8a3382aeab804

### 23. 帆布鞋和托特包同框

一张目录照片，展示 Qwen Image 3.0 把两张参考图里的鞋和包放进同一个场景。

<p align="center"><img src="assets/q16.webp" width="800" alt="一只燕麦色帆布鞋和一只燕麦色亚麻包一起放在浅色水磨石上。由 Beatra AI 生成。"></p>

*一只燕麦色帆布鞋和一只燕麦色亚麻包一起放在浅色水磨石上。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0，拿燕麦色帆布鞋照片和燕麦色亚麻包照片，把两者放在白墙前的浅色水磨石上。
```

提示词：

```text
A lifestyle catalog photo on a pale terrazzo floor against a plain white wall, morning light from the left. Place the oatmeal sneaker from the first image next to the oat linen tote from the second image. Keep the shoe's gum sole, cream laces, and blank heel tab. Keep the tote's patch pocket and two handles. No text, no logos, no watermark, no people, no hands.
```

Qwen Image 3.0 · 图生图 · 1K · 1:1

在 Beatra 上生成 · 任务 task_mcp_d02521534c3ce35bd12feb25516421ec17716239

### 24. 穿上锈红色大衣的女性

一张棚拍肖像，展示 Qwen Image 3.0 给第一张参考里的女性穿上第二张参考里的大衣。

<p align="center"><img src="assets/q38.webp" width="800" alt="短黑发、黑色高领的女性穿着那件锈红色羊毛大衣。参考图也是由 Beatra AI 生成。"></p>

*短黑发、黑色高领的女性穿着那件锈红色羊毛大衣。参考图也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0，拿人物照片和锈红色大衣的照片，让她穿着这件没扣上的大衣，保留她的脸、短黑发和黑色高领。
```

提示词：

```text
A photoreal studio portrait of the woman from the first image wearing the rust wool overcoat from the second image. Keep her face, short black hair, and black turtleneck recognizable. The coat is on her, unbuttoned, same rust color and lapels. Plain warm-grey studio, even soft light, three-quarter view, hands visible and anatomically correct. No text, no logos, no watermark.
```

Qwen Image 3.0 · 图生图 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_22573ba199b5621c53651ace43f0ccfef57b6ee1, task_mcp_c42d709ecb959be103adb8c75ecf40acccf04181, task_mcp_f7231ab9c8f991dfab2029c068d5a0d780610b0c

### 25. 厨房台面上的黑壶

一张厨房台面，展示 Qwen Image 3.0 把第一张参考里的壶放到第二张参考的台面上。

<p align="center"><img src="assets/q39.webp" width="800" alt="哑光黑鹅颈壶放在有阳光的白瓷砖台面上，旁边是木砧板。参考图也是由 Beatra AI 生成。"></p>

*哑光黑鹅颈壶放在有阳光的白瓷砖台面上，旁边是木砧板。参考图也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0，拿这把壶的照片和这间厨房的照片，把哑光黑鹅颈壶放到白瓷砖台面上，靠近木砧板。
```

提示词：

```text
Place the matte-black gooseneck kettle from the first image on the sunlit white-tile kitchen counter from the second image, near the wood cutting board. Keep the kettle's round body, long curved spout, and wood handle. Keep the window, sheer curtains, and morning light. No people, no logos, no readable text, no watermark.
```

Qwen Image 3.0 · 图生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_d362b0190e4253225116f164a93d479113c81f01, task_mcp_b9f89ed177cabe7341189d1e19edfee43a8536a0, task_mcp_1407f1dbee504b8160d8a0fb1f84bd15cea1101d

<a id="illustration"></a>

## 插画与风格

### 26. 平面风格的在家办公

一张平面书桌插画，展示 Qwen Image 3.0 Pro 画出一个没有文字的简单场景。

<p align="center"><img src="assets/q17.webp" width="800" alt="一张平面插画：一个人在家里的书桌前，旁边有杯子、植物和一只猫。由 Beatra AI 生成。"></p>

*一张平面插画：一个人在家里的书桌前，旁边有杯子、植物和一只猫。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 Pro 画一张平面插画：一个人在窗边的家里书桌上工作，旁边有杯子、龟背竹和一只睡着的猫。不要文字。
```

提示词：

```text
[panel 2] Flat vector illustration for a blog header about remote work. A cozy home workspace seen from a slight side angle: a person with short dark hair sits at a wooden desk by a large window, working on a laptop, a mug of coffee beside it, a leafy potted monstera, a sleeping cat curled on a cushion nearby, and a small video-call window with two simple abstract avatars floating above the laptop. Through the window, soft rolling hills and a morning sun. Clean geometric shapes, flat colors with subtle grain texture, limited palette of warm coral, mustard yellow, teal and cream, no gradients, no outlines on the background, modern editorial illustration style, balanced composition with calm negative space. No text, no letters, no logos.
```

Qwen Image 3.0 Pro · 文生图 · 358×421

在 Beatra 上生成 · 任务 task_mcp_38f1a34bf6fc493f7b65440ecef6925365d29b83

### 27. 暴风雨中的灯塔

一张灯塔概念画面，展示 Qwen Image 3.0 Pro 画一幅没有人的电影感风景。

<p align="center"><img src="assets/q18.webp" width="800" alt="岩石上有一座白色灯塔，浪花四溅，一道光穿过雨。由 Beatra AI 生成。"></p>

*岩石上有一座白色灯塔，浪花四溅，一道光穿过雨。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 Pro 画一座孤零零的白色灯塔，立在黄昏暴风雨的岩石上，一道金色光穿过雨。不要人，不要船，不要文字。
```

提示词：

```text
[panel 3] Cinematic concept art film still: a lone white stone lighthouse on a jagged rocky headland at dusk during a violent storm. Huge dark waves crash against the rocks and burst into white spray, the lighthouse beam cuts a bright golden shaft through slanting rain and low churning clouds. Deep teal and slate-blue storm sky with a thin band of burning orange sunset light on the horizon, a single warm lit window at the lighthouse base. Low wide-angle camera, dramatic scale, volumetric light, atmospheric haze, high dynamic range, anamorphic film look, rich contrast, highly detailed. No people, no boats, no text.
```

Qwen Image 3.0 Pro · 文生图 · 421×421

在 Beatra 上生成 · 任务 task_mcp_af531ac21ea594fd04515e5c14f314ba434cf716

### 28. 平面面包店门面

一家平面面包店，展示 Qwen Image 3.0 用有限的颜色画一张没有文字的插画。

<p align="center"><img src="assets/q19.webp" width="800" alt="一家小面包店，黄色遮阳篷，一辆自行车，一只鸽子。由 Beatra AI 生成。"></p>

*一家小面包店，黄色遮阳篷，一辆自行车，一只鸽子。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一家平面风格的面包店：黄油黄色的遮阳篷，圆窗里是面包，一辆自行车，一只鸽子。不要文字。
```

提示词：

```text
Flat editorial illustration of a tiny fictional bakery storefront on a quiet street at morning. Butter-yellow awning, a round window full of plain loaves, a bicycle with a basket of bread, one pigeon. Limited palette of butter, terracotta, sage, and cream. Clean shapes, no outlines on the sky, no text, no letters, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 16:9

在 Beatra 上生成 · 任务 task_mcp_5b98f2ff025529cf8e05e8c226daa12afbfce7a7

### 29. 水粉夜行列车

一列水粉夜车，展示 Qwen Image 3.0 用水粉画这片风景。

<p align="center"><img src="assets/q20.webp" width="800" alt="一列短短的夜车在木栈桥上，一扇窗发着暖光。由 Beatra AI 生成。"></p>

*一列短短的夜车在木栈桥上，一扇窗发着暖光。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一幅水粉：一列夜车驶过木栈桥，一扇窗亮着，靛蓝的山和一弯细月。不要人，也不要文字。
```

提示词：

```text
Gouache illustration of a short fictional night train crossing a wooden trestle, one warm square window lit, deep indigo hills and a thin moon. Visible paper texture, soft brush edges, no people visible, no text, no letters, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 16:9

在 Beatra 上生成 · 任务 task_mcp_352beec571cea8b1cdb58f6633f0acb9a6418ff8

### 30. 彩铅雨衣狐狸

一只彩铅雨衣狐狸，展示 Qwen Image 3.0 画一个原创角色。

<p align="center"><img src="assets/q21.webp" width="800" alt="一只赤狐穿着黄色雨衣和绿色靴子，站在一朵蘑菇下面。由 Beatra AI 生成。"></p>

*一只赤狐穿着黄色雨衣和绿色靴子，站在一朵蘑菇下面。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一张彩铅：一只原创的赤狐，穿着素色的黄色雨衣和绿色靴子，站在一朵蘑菇下面。不要文字。
```

提示词：

```text
Children's book illustration, soft colored pencil, of an original red fox wearing a plain yellow raincoat and green boots, standing under a single mushroom in light rain. White paper background, no text, no letters, no logos, no watermark. The fox is not a known character.
```

Qwen Image 3.0 · 文生图 · 1K · 1:1

在 Beatra 上生成 · 任务 task_mcp_733218bdb6a7c5919f298dc0a4dba9650e049834

### 31. 等距唱片店内景

一张等距唱片店，展示 Qwen Image 3.0 用有限的颜色画一个没有可读文字的内景。

<p align="center"><img src="assets/q40.webp" width="800" alt="等距的唱片店里有木柜台、黑胶箱、一盆植物和一扇天窗。封套是色块和简单几何形。由 Beatra AI 生成。"></p>

*等距的唱片店里有木柜台、黑胶箱、一盆植物和一扇天窗。封套是色块和简单几何形。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一家等距唱片店：木柜台、黑胶箱、一盆植物、一扇天窗。封套只用纯色或简单几何形。不要字母。
```

提示词：

```text
Isometric illustration of a tiny fictional record-shop interior, limited flat colors. One wooden counter, wooden vinyl crates, a potted plant, a skylight, no people. Every album sleeve is a solid color or a simple geometric shape with no letters, no numbers, no logos, and no readable marks of any kind. Clean vector-like isometric, generous margin.
```

Qwen Image 3.0 · 文生图 · 2K · 1:1

在 Beatra 上生成 · 任务 task_mcp_acaac2206d1b6265deae510ba885de52453ad466

<a id="portraits"></a>

## 虚构人像

### 32. 虚构讲解人的头肩照

一张棚拍半身像，展示 Qwen Image 3.0 Pro 画一位虚构讲解人，脸看起来自然。

<p align="center"><img src="assets/q22.webp" width="800" alt="一位虚构女性的头肩肖像，穿着鼠尾草绿毛衣。由 Beatra AI 生成。"></p>

*一位虚构女性的头肩肖像，穿着鼠尾草绿毛衣。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 Pro 拍一张虚构女性的头肩照，三十多岁，鼠尾草绿毛衣，看着镜头，闭嘴微笑。浅灰背景，不要文字。
```

提示词：

```text
Photorealistic head-and-shoulders portrait of a friendly product educator, a woman in her mid-30s, looking directly into the camera with a warm, relaxed closed-mouth smile, as if about to start speaking to viewers. Shoulder-length dark brown hair, natural makeup, a simple sage-green crew-neck knit sweater with no logos or text. Centered framing from mid-chest up with comfortable headroom, both shoulders visible, arms and hands out of frame. Plain seamless warm light-grey studio backdrop with a gentle soft falloff. Soft large key light from the front-left, subtle fill, clean catchlights in both eyes, natural skin texture, symmetric well-formed eyes and ears, sharp focus on the face, shallow depth of field. Shot on an 85mm lens, true-to-life color, calm and trustworthy presenter look. No text, no watermark, no jewelry, no microphone.
```

Qwen Image 3.0 Pro · 文生图 · 616×829

在 Beatra 上生成 · 任务 task_mcp_181a7bf4c51b51ae1271bc4d433b8d1fa0b8df4a

### 33. 编辑后的咖啡馆肖像

一张近景肖像，展示 Qwen Image 3.0 的编辑把虚构脸上的塑料感收掉。

<p align="center"><img src="assets/q24.webp" width="800" alt="咖啡馆里一位虚构女性的近景肖像，穿着奶油色高领毛衣。输入的照片也是由 Beatra AI 生成。"></p>

*咖啡馆里一位虚构女性的近景肖像，穿着奶油色高领毛衣。输入的照片也是由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 编辑这张咖啡馆里虚构女性的肖像：脸、栗色头发和奶油色高领毛衣保持不变，把皮肤纹理恢复成普通照片的样子。
```

提示词：

```text
[after] Reduce the plastic, airbrushed AI look across this portrait so it reads like a real camera photograph. Restore natural skin texture with fine visible pores, subtle fine lines and slight natural unevenness in skin tone; replace the two round orange blush patches with a faint natural flush; tone down the over-saturated orange-pink glow, bloom haze and over-bright rim light to realistic warm cafe lighting with natural color; make the catchlights in the eyes small and natural. Preserve the same woman's identity and facial features, expression and closed-mouth smile, eye color, wavy chestnut hairstyle, cream knit turtleneck sweater, pose, framing, crop, cafe background and lighting direction. Do not add makeup, text or logos.
```

Qwen Image 3.0 · 图片编辑 · 618×824

在 Beatra 上生成 · 任务 task_mcp_36cb6399c5ce443a72f54b7af67ccdb44f0a8509

### 34. 虚构面包师的头肩照

一张面包房肖像，展示 Qwen Image 3.0 画一位虚构男性的脸、眼睛和耳朵。

<p align="center"><img src="assets/q25.webp" width="800" alt="一位虚构男性，灰色胡子，围裙上有面粉，在面包房的厨房里。由 Beatra AI 生成。"></p>

*一位虚构男性，灰色胡子，围裙上有面粉，在面包房的厨房里。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一张虚构男性的头肩照，五十岁出头，灰色胡子，围裙上有面粉，背景是面包房的厨房。手不要入画，不要文字。
```

提示词：

```text
Photoreal head-and-shoulders portrait of a fictional man in his early fifties, short salt-and-pepper hair, a neat grey mustache, warm brown eyes, light crow's feet, wearing a flour-dusted oatmeal linen apron over a faded blue shirt. He looks just off camera with a small closed-mouth smile. Bakery kitchen background softly blurred, morning side light, natural skin texture, both eyes well formed, ears symmetric. Hands out of frame. No text, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 3:4

在 Beatra 上生成 · 任务 task_mcp_8de96b9bab4a153e27256b13bbd85807db73f963

### 35. 虚构骑行者站在路上

一张路上的肖像，展示 Qwen Image 3.0 画一位虚构骑行者和握把上的一只手。

<p align="center"><img src="assets/q26.webp" width="800" alt="一位虚构女性戴着锈红色帽子、穿着绿色骑行衫，在碎石路上握着自行车把。由 Beatra AI 生成。"></p>

*一位虚构女性戴着锈红色帽子、穿着绿色骑行衫，在碎石路上握着自行车把。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一张虚构女性的四分之三侧身照：锈红色骑行帽，苔绿色骑行衫，一只手握着自行车把，站在碎石路上。不要标志，也不要文字。
```

提示词：

```text
Photoreal three-quarter portrait of a fictional woman in her late twenties with a short black crop, a small scar through the left eyebrow, wearing a rust-colored cycling cap and a moss-green wool jersey with no logos. She holds the bicycle handlebar with one hand, five natural fingers, and smiles with teeth unseen. Overcast daylight on a gravel path, pine trees blurred behind. Natural skin, correct eyes and ears. No text, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 1K · 3:4

在 Beatra 上生成 · 任务 task_mcp_b71e0d1eaf675f21f1d281f69271be4c381d85ce

### 36. 窗边的虚构陶艺人

一张陶艺工作室肖像，展示 Qwen Image 3.0 画一位坐在窗边的虚构年长女性。

<p align="center"><img src="assets/q41.webp" width="800" alt="一位虚构的年长女性，银发，亚麻围裙，坐在陶艺工作室的陶轮旁边。由 Beatra AI 生成。"></p>

*一位虚构的年长女性，银发，亚麻围裙，坐在陶艺工作室的陶轮旁边。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 拍一位虚构的年长女性：银发盘起，炭灰衬衫外罩亚麻围裙，坐在工作室窗边的陶轮旁。不要文字。
```

提示词：

```text
Photoreal three-quarter portrait of a fictional woman in her early seventies, silver hair pinned up, clay-dusted linen apron over a charcoal shirt, sitting beside a pottery wheel near a north-facing studio window, pale daylight, lined natural skin, closed mouth, hands resting on her lap with clay under the nails, anatomically correct. Quiet pottery studio, shelves of unglazed bowls behind her, slightly out of focus. No text, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 3:4

在 Beatra 上生成 · 任务 task_mcp_9172f0aa9846821eda365d9ead249487c5c681ea

<a id="infographics"></a>

## 信息图与图表

### 37. 泡茶四步信息卡

一张四步泡茶卡，展示 Qwen Image 3.0 把双语标签和四个图标排成一行。

<p align="center"><img src="assets/q27.webp" width="800" alt="一张宽卡片，标题是 TEA STEPS，四个带数字的图标排成一行。由 Beatra AI 生成。"></p>

*一张宽卡片，标题是 TEA STEPS，四个带数字的图标排成一行。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 做一张宽幅信息图，标题是 TEA STEPS，下面是泡茶四步，四步的标签是 KETTLE、LEAVES、WAIT、POUR。不要其他文字。
```

提示词：

```text
Clean flat infographic on white, wide layout, lots of margin. Title exactly TEA STEPS in black sans-serif. Under it the Chinese line 泡茶四步 exactly. Four circles in a row containing only the digits 1 2 3 4, with the labels KETTLE, LEAVES, WAIT, POUR under them, each label one word, perfectly spelled. Simple line icons of a kettle, a leaf, a clock, and a cup. No other text, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_1f837487611da4da304c2d0a851e9b023a23562e

### 38. 一周杯数的柱状图

一张五根柱子的图，展示 Qwen Image 3.0 放上确定的数字和星期标签。

<p align="center"><img src="assets/q28.webp" width="800" alt="五根陶土色的柱子，标签是 MON、TUE、WED、THU、FRI，数值是 12、18、15、21、16。由 Beatra AI 生成。"></p>

*五根陶土色的柱子，标签是 MON、TUE、WED、THU、FRI，数值是 12、18、15、21、16。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 做一张简单柱状图，标题 WEEKLY CUPS，副标题一周杯数，五根柱子的标签是 MON、TUE、WED、THU、FRI，数值依次是 12、18、15、21、16。不要其他文字。
```

提示词：

```text
Simple bar chart on warm white. Title exactly WEEKLY CUPS in dark brown sans-serif. Subtitle exactly 一周杯数. Five vertical terracotta bars on a thin baseline, labeled under the axis exactly MON TUE WED THU FRI. Printed above the bars, the exact values 12 18 15 21 16 in that order. No grid, no legend, no other text, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_63bf1dc9e44ba4061c53a28af507bb91cf582c27

### 39. 蕨类养护三栏卡

一张三栏养护卡，展示 Qwen Image 3.0 只留下标签，其余留白。

<p align="center"><img src="assets/q29.webp" width="800" alt="一张浅色卡片，标题是 FERN CARE，三栏分别是 LIGHT、WATER 和 SOIL。由 Beatra AI 生成。"></p>

*一张浅色卡片，标题是 FERN CARE，三栏分别是 LIGHT、WATER 和 SOIL。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 做一张三栏卡片。全文只有 FERN CARE、蕨类养护、LIGHT、WATER、SOIL，每栏一个简单图标，图标下面留白。
```

提示词：

```text
Clean three-column care card on pale sage paper, wide layout, lots of empty margin. The only text in the whole image is these five strings, each perfectly spelled, and nothing else: the title FERN CARE, the Chinese line 蕨类养护 directly under the title, and the three column labels LIGHT, WATER, and SOIL. Under LIGHT draw only a simple sun icon. Under WATER draw only a simple drop icon. Under SOIL draw only a simple pot icon. The area under every icon is blank paper. Do not write sentences, captions, descriptions, small print, or placeholder words. No numbers, no logos, no watermark.
```

Qwen Image 3.0 · 文生图 · 2K · 16:9

在 Beatra 上生成 · 任务 task_mcp_f2655d171c89420621e41849d0a73120a4d51468

### 40. 花粉径示意图

一张小路示意图，展示 Qwen Image 3.0 画一条带标签的路径，没有多余的字。

<p align="center"><img src="assets/q30.webp" width="800" alt="一张奶油色示意图，虚线从 GATE 到 RIDGE，中途标着 SPRING。由 Beatra AI 生成。"></p>

*一张奶油色示意图，虚线从 GATE 到 RIDGE，中途标着 SPRING。由 Beatra AI 生成。*

在你的 Agent 里这样说：

```text
用 Qwen Image 3.0 画一张简单的路线图，标题 POLLEN TRAIL，下面是花粉径。一条虚线从 GATE 到 RIDGE，中途是 SPRING。只有这些字。
```

提示词：

```text
Simple schematic trail map on cream paper, not a real place. A single dotted path from a square labeled GATE to a triangle labeled RIDGE, with a small circle labeled SPRING halfway. Title at the top exactly POLLEN TRAIL and the Chinese line 花粉径 under the title. Those five words and the Chinese line are the only text. Flat ink drawing, no logos, no watermark, no compass rose text.
```

Qwen Image 3.0 · 文生图 · 2K · 4:3

在 Beatra 上生成 · 任务 task_mcp_f35abee38d9a42f2f62840d1ba7f616e04937ac6

## 为什么在 Beatra 上跑

- 本清单用到的模型：Qwen Image 3.0 Pro、Qwen Image 3.0。
- 安装免费。每次生成消耗 Beatra 账号积分，只有你明确要求这次生成或批准确认卡后才会付费。
- 支持的 Agent：Claude Code、Cursor、Codex、Windsurf、Cline、OpenClaw。

## 贡献

欢迎用 issue 提出想看的案例。本清单不收第三方作品。

## 许可

本清单的提示词与素材使用 CC BY 4.0。转载需要署名并带回链。

## 相关链接

- [Awesome Wan 3.0 Video](https://github.com/beatra-ai/awesome-wan-3-video)
- [AI Image Generator Skill](https://github.com/beatra-ai/ai-image-generator-skill)
- [Beatra Skills](https://github.com/beatra-ai/beatra-skills)
- [beatra.ai](https://beatra.ai/?utm_source=github&utm_medium=cases_list&utm_campaign=awesome-qwen-image-3)
