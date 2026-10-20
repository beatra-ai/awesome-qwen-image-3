# Awesome Qwen Image 3.0

[English](./README.md) | [简体中文](./README.zh-CN.md) | 日本語

> 👉 こちらもどうぞ [Awesome Wan 3.0 Video](https://github.com/beatra-ai/awesome-wan-3-video)

Qwen Image 3.0 の実例です。各カードに完全なプロンプトがあり、エージェントで再現できます。

以下の事例はすべてこのモデルで Beatra 上で実際に生成したもので、プロンプトはそのまま掲載し、各カードにタスク ID を記載しています。

エージェントでそのまま再現: `npx skills add beatra-ai/ai-image-generator-skill` · [beatra.ai](https://beatra.ai/?utm_source=github&utm_medium=cases_list&utm_campaign=awesome-qwen-image-3)

## 目次

- [文字とポスター](#typography-posters)
- [商品写真と場面](#ecommerce)
- [部分編集と背景の差し替え](#editing)
- [複数の参照から一枚](#multi-reference)
- [イラストと画風](#illustration)
- [架空の肖像](#portraits)
- [図解とチャート](#infographics)

<a id="typography-posters"></a>

## 文字とポスター

### 1. Brightmoss のアイコンと文字

平面の Brightmoss ワードマークで、Qwen Image 3.0 Pro が短い英語名をロゴの中に収めています。

<p align="center"><img src="assets/q01.webp" width="800" alt="暖色のクリーム色の平面に、緑のアイコンと Brightmoss の文字。Beatra AI で生成。"></p>

*暖色のクリーム色の平面に、緑のアイコンと Brightmoss の文字。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 Pro で、暖色のクリーム色の平面ボードを作って。深緑の角丸アイコンに豆と葉の記号、その横に Brightmoss。2色だけ、他の文字はなし。
```

プロンプト：

```text
Refine this accepted Brightmoss logo into a two-part brand presentation on one flat warm cream background (#F4EEE2). Left: an app icon, a solid rounded square in deep forest green (#1F4D3A) with the same coffee-bean-and-leaf symbol from the image centered inside in cream, generous padding, no text in the icon. Right: a horizontal lockup, the same green bean-and-leaf symbol placed to the left of the exact word "Brightmoss" in the same bold humanist sans-serif lettering, forest green, vertically centered with the symbol. Keep the symbol shape and the wordmark letterforms identical to the source. Flat vector, maximum two colors, no gradients, no shadows, no mockup, no tagline, no other text.
```

Qwen Image 3.0 Pro · テキストから画像 · 1280×723

Beatra で生成 · タスク task_mcp_33b755587a76a7bcb1bc5874324c2a4c9738a6fc

### 2. Northglass のフェリーポスター

クリーム色のフェリーポスターで、Qwen Image 3.0 が英語と中国語を所定の位置に置いています。

<p align="center"><img src="assets/q02.webp" width="800" alt="クリーム色のポスターに暗い青緑のフェリーと NORTHGLASS、FERRY、北璃渡轮。Beatra AI で生成。"></p>

*クリーム色のポスターに暗い青緑のフェリーと NORTHGLASS、FERRY、北璃渡轮。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で縦長のクリーム色のフェリーポスターを作って。暗い青緑の船。上に NORTHGLASS と FERRY、船の下に北璃渡轮。他の文字はなし。
```

プロンプト：

```text
Vertical printed travel poster, cream paper, a simple flat illustration of a dark teal ferry on pale grey water under a wheat-colored sun, generous empty margin. Exact text only, perfectly spelled, no extra letters anywhere: NORTHGLASS in large bold black sans-serif at the top, FERRY directly under it in the same typeface, and the four Chinese characters 北璃渡轮 centered under the boat in a clean black serif. No dates, no logos, no watermark, no people.
```

Qwen Image 3.0 · テキストから画像 · 2K · 3:4

Beatra で生成 · タスク task_mcp_3ae36b5a0a40614b79dc862d0bb0f47c7d703480

### 3. Hearthlane のマーケットポスター

横長のマーケットのポスターで、Qwen Image 3.0 が英語の名と中国語の一行を描いています。

<p align="center"><img src="assets/q03.webp" width="800" alt="横長のクリーム色のポスターに果物の屋台、HEARTHLANE、周末市集。Beatra AI で生成。"></p>

*横長のクリーム色のポスターに果物の屋台、HEARTHLANE、周末市集。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で横長のクリーム色のマーケットポスターを作って。小さな果物の屋台、上に HEARTHLANE、下に周末市集。他の語はなし。
```

プロンプト：

```text
Wide market poster, warm cream background, a small centered illustration of a wooden stall with green pears and a rust-striped awning, lots of empty space. Exact text only, perfectly spelled: HEARTHLANE in large dark-green serif across the top, and the four Chinese characters 周末市集 centered at the bottom in the same dark green. No other words, numbers, logos, or watermarks.
```

Qwen Image 3.0 · テキストから画像 · 2K · 16:9

Beatra で生成 · タスク task_mcp_ed1fe7fb9bb09b117ebce535beb68127861fa116

### 4. Lumen Orchard の提灯ポスター

紺の演奏会ポスターで、Qwen Image 3.0 が一つの提灯の周りに二言語の題名を置いています。

<p align="center"><img src="assets/q04.webp" width="800" alt="紺のポスターに琥珀色の提灯一つと、LUMEN ORCHARD、灯园乐队。Beatra AI で生成。"></p>

*紺のポスターに琥珀色の提灯一つと、LUMEN ORCHARD、灯园乐队。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で紺の演奏会ポスターを作って。中央に琥珀色の紙提灯。上の方に LUMEN ORCHARD、提灯の下に灯园乐队。日付も他の文字もなし。
```

プロンプト：

```text
Minimal concert poster, deep navy background, one round paper lantern glowing amber in the center. Exact text only, perfectly spelled: LUMEN ORCHARD in cream serif capitals near the top, and the four Chinese characters 灯园乐队 in cream under the lantern. No dates, no other letters, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 2K · 3:4

Beatra で生成 · タスク task_mcp_430d142962b0c29b18cb70ac2a6fa3f4a458317b

### 5. Paper Finch の書展ポスター

書展のポスターで、Qwen Image 3.0 が線画の周りに三行の二言語タイトルを綴っています。

<p align="center"><img src="assets/q05.webp" width="800" alt="正方形のポスターに開いた本の線画と、PAPER FINCH、PRESS、纸雀书展。Beatra AI で生成。"></p>

*正方形のポスターに開いた本の線画と、PAPER FINCH、PRESS、纸雀书展。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で正方形のオフホワイトのポスターを作って。開いた本の線画。文字は PAPER FINCH、PRESS、纸雀书展の三行だけ。
```

プロンプト：

```text
Square book-fair poster, off-white paper, a single black line drawing of an open blank book, lots of margin. Exactly three lines of text, perfectly spelled, and no other letters anywhere. Top line: PAPER FINCH in bold black sans-serif. Middle line, directly under it: PRESS, spelled P-R-E-S-S, the first letter is P. Bottom line: the four Chinese characters 纸雀书展. Do not write DRESS. No logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 2K · 1:1

Beatra で生成 · タスク task_mcp_fde63ad38a445a53a0722db22d76c2c373a98e7c

<a id="ecommerce"></a>

## 商品写真と場面

### 6. 冬の夜のハンドドリップ

冬の夜のハンドドリップの静物で、Qwen Image 3.0 が商品写真の季節を変えています。

<p align="center"><img src="assets/q06.webp" width="800" alt="同じハンドドリップの器具が、今は窓辺の雪の夜にあります。入力写真も Beatra AI で生成しています。"></p>

*同じハンドドリップの器具が、今は窓辺の雪の夜にあります。入力写真も Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 でこのハンドドリップの写真を編集して。セージグリーンの器具はそのまま、場面を雪の冬の夜に変えて。
```

プロンプト：

```text
[edit] Change the season and time of day to a cozy winter evening. Keep the ceramic pour-over coffee set exactly as it is: the sage-green dripper with its paper filter and handle on the glass carafe of coffee, the sage-green mug, the speckled cream sugar bowl, the coffee beans, the oak table, and the camera angle and positions of every object. Outside the window it is now dusk with snow falling, snow-covered branches and a deep blue evening sky; a little snow rests on the window frame. Replace the summer sunlight with warm indoor lamplight from the right and soft candlelight, gentle warm glow on the ceramics, a thin wisp of steam rising from the mug, and swap the green leaves in the glass jar for a few bare winter twigs with small red berries. Warm amber and deep blue color contrast, photoreal lifestyle photography. No people, no text, no logos.
```

Qwen Image 3.0 · 画像編集 · 616×458

Beatra で生成 · タスク task_mcp_9e6bd9541f728564e941e08748f6a7da4ef5dacc

### 7. Siltjar のホットソース瓶

ソース瓶の撮影で、Qwen Image 3.0 が架空の商品と一語だけのラベルを描いています。

<p align="center"><img src="assets/q07.webp" width="800" alt="テラコッタ色の瓶、黒いキャップ、クリーム色のラベルに SILTJAR。Beatra AI で生成。"></p>

*テラコッタ色の瓶、黒いキャップ、クリーム色のラベルに SILTJAR。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で、石灰岩の板の上に架空のホットソース瓶を一つ。クリーム色のラベルは SILTJAR だけ。
```

プロンプト：

```text
Photoreal studio product photo of one fictional hot-sauce bottle on a pale limestone slab. The bottle is short, matte clay-red ceramic with a black screw cap and a plain cream label. The label carries only the exact word SILTJAR in black serif, perfectly spelled, once. Soft window light from the left, a few dried chili peppers beside the bottle, shallow depth of field, no hands, no other text, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 1:1

Beatra で生成 · タスク task_mcp_311c592f739e31aa31e2d5bed3b42850b7a6ad4b

### 8. オートミール色のスニーカー

カタログ風のスニーカー写真で、Qwen Image 3.0 がロゴのない商品写真を作っています。

<p align="center"><img src="assets/q08.webp" width="800" alt="暖色の灰色を背景に、オートミール色のローカットとガムソールが一足。Beatra AI で生成。"></p>

*暖色の灰色を背景に、オートミール色のローカットとガムソールが一足。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で架空のローカットを一足。オートミール色のキャンバスにガムソール、暖色の灰色背景。ロゴも文字もなし。
```

プロンプト：

```text
Photoreal product photo of one fictional low-top sneaker, three-quarter view, on a seamless warm-grey cyclorama. The shoe is oatmeal canvas with a gum rubber sole, cream laces, and a small blank heel tab. No wordmark, no logo, no text anywhere. Soft overhead daylight, crisp but gentle shadow, commercial catalog lighting. No people, no hands, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 1:1

Beatra で生成 · タスク task_mcp_41fa7eafe76d178f9fdac8d5420e62dd78587068

### 9. オークテーブルの真鍮キャンドル缶

卓上のキャンドル静物で、Qwen Image 3.0 がラベルのない単純な商品の形を保っています。

<p align="center"><img src="assets/q09.webp" width="800" alt="暗いオークの上に低い真鍮の缶、中はクリーム色の蝋、横にローズマリー。Beatra AI で生成。"></p>

*暗いオークの上に低い真鍮の缶、中はクリーム色の蝋、横にローズマリー。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で卓上写真を作って。暗いオークの上に架空の真鍮キャンドル、芯は火がついていない。ローズマリーを一枝。ラベルも文字もなし。
```

プロンプト：

```text
Photoreal tabletop photo of a fictional candle: a low brass tin of cream soy wax with one unlit cotton wick, sitting on dark oak. Beside it, a sprig of dried rosemary. The tin has no label and no letters. Warm side light, shallow depth of field, catalog still life. No people, no hands, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 4:3

Beatra で生成 · タスク task_mcp_341f4873b3d3cb190bc4a82588df5b1db8bc2312

### 10. オートミール色のリネントートと洋梨

生活場面のトートで、Qwen Image 3.0 が一つの商品を静かな部屋に置いています。

<p align="center"><img src="assets/q10.webp" width="800" alt="未染色のリネントートが淡いテラゾーの上に立ち、横に青梨。Beatra AI で生成。"></p>

*未染色のリネントートが淡いテラゾーの上に立ち、横に青梨。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で生活写真を作って。架空のオートミール色リネントートを白い壁の前の淡いテラゾーに立て、横に青梨を一つ。プリントも文字もなし。
```

プロンプト：

```text
Photoreal lifestyle product photo of a fictional heavy linen tote bag standing upright on a pale terrazzo floor against a white wall. The bag is undyed oat linen with two short cotton handles and a small rectangular patch pocket. No print, no letters, no logo. Morning light from the left, a single green pear on the floor beside the bag. No people, no hands, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 3:4

Beatra で生成 · タスク task_mcp_62d074025fb6e065bd7b0dd4d9aa80f40e72ca97

<a id="editing"></a>

## 部分編集と背景の差し替え

### 11. Siltjar の瓶、台を差し替え

前後の比較で、Qwen Image 3.0 が瓶の台を替え、SILTJAR のラベルを残しています。

<p align="center"><img src="assets/q11.webp" width="800" alt="左は石灰岩の上の瓶です。右は同じ瓶が、暗い緑のタイルの上にあります。入力写真も Beatra AI で生成しています。"></p>

*左は石灰岩の上の瓶です。右は同じ瓶が、暗い緑のタイルの上にあります。入力写真も Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で Siltjar の瓶の写真を編集して。瓶、キャップ、唐辛子、SILTJAR のラベルはそのまま。台を暗い緑のタイルに替えて。
```

プロンプト：

```text
Keep the clay-red ceramic bottle, its black cap, the dried chilies, and the cream label exactly as they are. The label must still read SILTJAR, spelled S-I-L-T-J-A-R, and no other letters. Replace the limestone slab and the beige wall with a dark green glazed-tile counter and a softly blurred kitchen. Do not change the bottle shape. No extra text, no logos, no watermark.
```

Qwen Image 3.0 · 画像編集 · 1K · 1:1

Beatra で生成 · タスク task_mcp_311c592f739e31aa31e2d5bed3b42850b7a6ad4b, task_mcp_f727724c879a642a71c11f8101a5ad523d00618d

### 12. アッパーを藍色に変更

前後の比較で、Qwen Image 3.0 がスニーカーのアッパーだけを塗り替えています。

<p align="center"><img src="assets/q12.webp" width="800" alt="左はオートミール色のスニーカーです。右は同じ靴で、アッパーが深い藍です。入力写真も Beatra AI で生成しています。"></p>

*左はオートミール色のスニーカーです。右は同じ靴で、アッパーが深い藍です。入力写真も Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 でこのオートミール色のスニーカーを編集して。角度、ガムソール、靴ひも、空白のヒールタブはそのまま。キャンバスのアッパーだけを深い藍に。
```

プロンプト：

```text
Keep the same low-top sneaker, the same three-quarter angle, the gum rubber sole, the cream laces, and the blank heel tab. Change only the canvas upper from oatmeal to deep indigo. Do not add text, a logo, a wordmark, or a watermark. No people, no hands.
```

Qwen Image 3.0 · 画像編集 · 1K · 1:1

Beatra で生成 · タスク task_mcp_41fa7eafe76d178f9fdac8d5420e62dd78587068, task_mcp_bb1110e3cbe7370acc461410a3b7c9274a011e13

### 13. トートを雨の入口へ

前後の比較で、Qwen Image 3.0 が同じトートを白い部屋から雨の入口へ移しています。

<p align="center"><img src="assets/q13.webp" width="800" alt="左は白い部屋のトートです。右は同じトートと洋梨が、雨の入口にあります。入力写真も Beatra AI で生成しています。"></p>

*左は白い部屋のトートです。右は同じトートと洋梨が、雨の入口にあります。入力写真も Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 でこのオートミール色のトート写真を編集して。袋、ポケット、持ち手、洋梨はそのまま。雨の店先へ移し、後ろは暗い緑のドア。
```

プロンプト：

```text
Keep the undyed oat linen tote, its patch pocket, its two short handles, and the green pear. Replace the white wall and the terrazzo floor with a rainy shop doorway: wet grey stone under the bag and a dark green wooden door behind it. Overcast daylight. No text, no logo, no watermark, no people, no hands.
```

Qwen Image 3.0 · 画像編集 · 1K · 3:4

Beatra で生成 · タスク task_mcp_62d074025fb6e065bd7b0dd4d9aa80f40e72ca97, task_mcp_1cf17a60d29c226d916229738e6b7dff99576ed7

<a id="multi-reference"></a>

## 複数の参照から一枚

### 14. ソース瓶とキャンドルを並べる

一枚の静物で、Qwen Image 3.0 が二枚の参照写真のソース瓶とキャンドルを一つにしています。

<p align="center"><img src="assets/q14.webp" width="800" alt="テラコッタ色の瓶と真鍮のキャンドルが、一つのオークの卓にあります。Beatra AI で生成しています。"></p>

*テラコッタ色の瓶と真鍮のキャンドルが、一つのオークの卓にあります。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 に Siltjar の瓶の写真と真鍮キャンドルの写真を渡して。両方を暗いオークの卓に置き、SILTJAR のラベルはそのまま。
```

プロンプト：

```text
One catalog still life on a dark oak table in warm side light. Place the hot-sauce bottle from the first image beside the brass candle tin from the second image. Keep the bottle's clay-red body, black cap, and the label spelling SILTJAR exactly. Keep the candle's low brass tin and single unlit wick. No other text, no logos, no watermark, no hands.
```

Qwen Image 3.0 · 画像から画像 · 1K · 4:3

Beatra で生成 · タスク task_mcp_0fefd99194c4683cedb0377d60ab5d3d3d473b03

### 15. ベーカリー前のレインコートの狐

一枚の挿絵で、Qwen Image 3.0 がレインコートの狐を、二枚目の参照にあるベーカリーの前に置いています。

<p align="center"><img src="assets/q15.webp" width="800" alt="黄色いレインコートの赤狐が、黄色いひさしのベーカリーの前に立っています。Beatra AI で生成しています。"></p>

*黄色いレインコートの赤狐が、黄色いひさしのベーカリーの前に立っています。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 にレインコートの狐の絵とベーカリーの絵を渡して。狐をその店の前の歩道に置き、黄色いひさしと自転車は残して。
```

プロンプト：

```text
A flat editorial illustration. Place the red fox in the yellow raincoat and green boots from the first image on the sidewalk in front of the bakery from the second image. Keep the fox's coat, boots, and face recognizable. Keep the bakery's butter-yellow awning, round window of loaves, and the bicycle. No text, no letters, no logos, no watermark.
```

Qwen Image 3.0 · 画像から画像 · 1K · 16:9

Beatra で生成 · タスク task_mcp_7957b46f4d4f13057b8c97786dd8a3382aeab804

### 16. スニーカーとトートを同じ部屋に

一枚のカタログ写真で、Qwen Image 3.0 が二枚の参照の靴と袋を同じ場面に入れています。

<p align="center"><img src="assets/q16.webp" width="800" alt="オートミール色のスニーカーとリネントートが、淡いテラゾーの上に一緒にあります。Beatra AI で生成しています。"></p>

*オートミール色のスニーカーとリネントートが、淡いテラゾーの上に一緒にあります。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 にオートミール色のスニーカーとリネントートの写真を渡して。白い壁の前の淡いテラゾーに両方を置いて。
```

プロンプト：

```text
A lifestyle catalog photo on a pale terrazzo floor against a plain white wall, morning light from the left. Place the oatmeal sneaker from the first image next to the oat linen tote from the second image. Keep the shoe's gum sole, cream laces, and blank heel tab. Keep the tote's patch pocket and two handles. No text, no logos, no watermark, no people, no hands.
```

Qwen Image 3.0 · 画像から画像 · 1K · 1:1

Beatra で生成 · タスク task_mcp_d02521534c3ce35bd12feb25516421ec17716239

<a id="illustration"></a>

## イラストと画風

### 17. 平面の在宅ワーク挿絵

平面の机の挿絵で、Qwen Image 3.0 Pro が文字のない単純な場面を描いています。

<p align="center"><img src="assets/q17.webp" width="800" alt="平面の挿絵です。自宅の机に人がいて、マグカップと植物と猫があります。Beatra AI で生成しています。"></p>

*平面の挿絵です。自宅の机に人がいて、マグカップと植物と猫があります。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 Pro で平面の挿絵を描いて。窓辺の自宅の机で働く人、マグカップ、モンステラ、眠る猫。文字はなし。
```

プロンプト：

```text
[panel 2] Flat vector illustration for a blog header about remote work. A cozy home workspace seen from a slight side angle: a person with short dark hair sits at a wooden desk by a large window, working on a laptop, a mug of coffee beside it, a leafy potted monstera, a sleeping cat curled on a cushion nearby, and a small video-call window with two simple abstract avatars floating above the laptop. Through the window, soft rolling hills and a morning sun. Clean geometric shapes, flat colors with subtle grain texture, limited palette of warm coral, mustard yellow, teal and cream, no gradients, no outlines on the background, modern editorial illustration style, balanced composition with calm negative space. No text, no letters, no logos.
```

Qwen Image 3.0 Pro · テキストから画像 · 358×421

Beatra で生成 · タスク task_mcp_38f1a34bf6fc493f7b65440ecef6925365d29b83

### 18. 嵐の灯台、人物なし

灯台のコンセプト画面で、Qwen Image 3.0 Pro が人物のない映画のような風景を描いています。

<p align="center"><img src="assets/q18.webp" width="800" alt="岩場の白い灯台。波しぶきと、雨を通る光。Beatra AI で生成。"></p>

*岩場の白い灯台。波しぶきと、雨を通る光。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 Pro で、黄昏の嵐の岩場に白い灯台を一つ。雨の中に金色の光。人物も船も文字もなし。
```

プロンプト：

```text
[panel 3] Cinematic concept art film still: a lone white stone lighthouse on a jagged rocky headland at dusk during a violent storm. Huge dark waves crash against the rocks and burst into white spray, the lighthouse beam cuts a bright golden shaft through slanting rain and low churning clouds. Deep teal and slate-blue storm sky with a thin band of burning orange sunset light on the horizon, a single warm lit window at the lighthouse base. Low wide-angle camera, dramatic scale, volumetric light, atmospheric haze, high dynamic range, anamorphic film look, rich contrast, highly detailed. No people, no boats, no text.
```

Qwen Image 3.0 Pro · テキストから画像 · 421×421

Beatra で生成 · タスク task_mcp_af531ac21ea594fd04515e5c14f314ba434cf716

### 19. 平面のベーカリー外観

平面のベーカリーで、Qwen Image 3.0 が限られた色数の、文字のない挿絵を描いています。

<p align="center"><img src="assets/q19.webp" width="800" alt="黄色いひさしの小さなベーカリー、自転車、鳩が一羽。Beatra AI で生成。"></p>

*黄色いひさしの小さなベーカリー、自転車、鳩が一羽。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で平面のベーカリー外観を描いて。バター色のひさし、丸窓のパン、自転車、鳩が一羽。文字はなし。
```

プロンプト：

```text
Flat editorial illustration of a tiny fictional bakery storefront on a quiet street at morning. Butter-yellow awning, a round window full of plain loaves, a bicycle with a basket of bread, one pigeon. Limited palette of butter, terracotta, sage, and cream. Clean shapes, no outlines on the sky, no text, no letters, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 16:9

Beatra で生成 · タスク task_mcp_5b98f2ff025529cf8e05e8c226daa12afbfce7a7

### 20. ガッシュの夜行列車

ガッシュの夜行列車で、Qwen Image 3.0 が風景を絵の具で描いています。

<p align="center"><img src="assets/q20.webp" width="800" alt="木の架橋の上の短い夜行列車です。暖かい窓が一つ灯っています。Beatra AI で生成しています。"></p>

*木の架橋の上の短い夜行列車です。暖かい窓が一つ灯っています。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 でガッシュを描いて。木の架橋を渡る夜行列車、灯る窓が一つ、藍の丘、細い月。人物も文字もなし。
```

プロンプト：

```text
Gouache illustration of a short fictional night train crossing a wooden trestle, one warm square window lit, deep indigo hills and a thin moon. Visible paper texture, soft brush edges, no people visible, no text, no letters, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 16:9

Beatra で生成 · タスク task_mcp_352beec571cea8b1cdb58f6633f0acb9a6418ff8

### 21. 色鉛筆のレインコートの狐

色鉛筆のレインコートの狐で、Qwen Image 3.0 がオリジナルのキャラクターを描いています。

<p align="center"><img src="assets/q21.webp" width="800" alt="黄色いレインコートと緑の長靴の赤狐が、キノコの下に立っています。Beatra AI で生成しています。"></p>

*黄色いレインコートと緑の長靴の赤狐が、キノコの下に立っています。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で色鉛筆の絵を描いて。オリジナルの赤狐、無地の黄色いレインコートと緑の長靴、キノコが一枚。文字はなし。
```

プロンプト：

```text
Children's book illustration, soft colored pencil, of an original red fox wearing a plain yellow raincoat and green boots, standing under a single mushroom in light rain. White paper background, no text, no letters, no logos, no watermark. The fox is not a known character.
```

Qwen Image 3.0 · テキストから画像 · 1K · 1:1

Beatra で生成 · タスク task_mcp_733218bdb6a7c5919f298dc0a4dba9650e049834

<a id="portraits"></a>

## 架空の肖像

### 22. 架空のプレゼンター、バストアップ

スタジオのバストアップで、Qwen Image 3.0 Pro が架空のプレゼンターを、自然な顔立ちで描いています。

<p align="center"><img src="assets/q22.webp" width="800" alt="セージグリーンのセーターを着た架空の女性のバストアップ。Beatra AI で生成。"></p>

*セージグリーンのセーターを着た架空の女性のバストアップ。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 Pro で架空の女性のバストアップを。30代半ば、セージグリーンのセーター、カメラを見て口を閉じた微笑。薄い灰色の背景。文字はなし。
```

プロンプト：

```text
Photorealistic head-and-shoulders portrait of a friendly product educator, a woman in her mid-30s, looking directly into the camera with a warm, relaxed closed-mouth smile, as if about to start speaking to viewers. Shoulder-length dark brown hair, natural makeup, a simple sage-green crew-neck knit sweater with no logos or text. Centered framing from mid-chest up with comfortable headroom, both shoulders visible, arms and hands out of frame. Plain seamless warm light-grey studio backdrop with a gentle soft falloff. Soft large key light from the front-left, subtle fill, clean catchlights in both eyes, natural skin texture, symmetric well-formed eyes and ears, sharp focus on the face, shallow depth of field. Shot on an 85mm lens, true-to-life color, calm and trustworthy presenter look. No text, no watermark, no jewelry, no microphone.
```

Qwen Image 3.0 Pro · テキストから画像 · 616×829

Beatra で生成 · タスク task_mcp_181a7bf4c51b51ae1271bc4d433b8d1fa0b8df4a

### 23. 編集後のカフェの肖像

近景の肖像で、Qwen Image 3.0 の編集が架空の顔からプラスチックのような見た目を取り除いています。

<p align="center"><img src="assets/q24.webp" width="800" alt="カフェにいる架空の女性の近景です。クリーム色のタートルネックです。入力写真も Beatra AI で生成しています。"></p>

*カフェにいる架空の女性の近景です。クリーム色のタートルネックです。入力写真も Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で、カフェにいる架空の女性の肖像を編集して。顔、栗色の髪、クリーム色のタートルネックはそのまま。肌の質感を普通の写真に戻して。
```

プロンプト：

```text
[after] Reduce the plastic, airbrushed AI look across this portrait so it reads like a real camera photograph. Restore natural skin texture with fine visible pores, subtle fine lines and slight natural unevenness in skin tone; replace the two round orange blush patches with a faint natural flush; tone down the over-saturated orange-pink glow, bloom haze and over-bright rim light to realistic warm cafe lighting with natural color; make the catchlights in the eyes small and natural. Preserve the same woman's identity and facial features, expression and closed-mouth smile, eye color, wavy chestnut hairstyle, cream knit turtleneck sweater, pose, framing, crop, cafe background and lighting direction. Do not add makeup, text or logos.
```

Qwen Image 3.0 · 画像編集 · 618×824

Beatra で生成 · タスク task_mcp_36cb6399c5ce443a72f54b7af67ccdb44f0a8509

### 24. 架空のパン職人、バストアップ

パン屋の肖像で、Qwen Image 3.0 が架空の男性の顔、目、耳を描いています。

<p align="center"><img src="assets/q25.webp" width="800" alt="灰色の口ひげと粉の付いたエプロンの架空の男性です。パン屋の厨房です。Beatra AI で生成しています。"></p>

*灰色の口ひげと粉の付いたエプロンの架空の男性です。パン屋の厨房です。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で架空の男性のバストアップを。50代前半、灰色の口ひげ、粉の付いたエプロン、パン屋の厨房。手はフレーム外。文字はなし。
```

プロンプト：

```text
Photoreal head-and-shoulders portrait of a fictional man in his early fifties, short salt-and-pepper hair, a neat grey mustache, warm brown eyes, light crow's feet, wearing a flour-dusted oatmeal linen apron over a faded blue shirt. He looks just off camera with a small closed-mouth smile. Bakery kitchen background softly blurred, morning side light, natural skin texture, both eyes well formed, ears symmetric. Hands out of frame. No text, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 3:4

Beatra で生成 · タスク task_mcp_8de96b9bab4a153e27256b13bbd85807db73f963

### 25. 砂利道の架空の自転車乗り

道の肖像で、Qwen Image 3.0 が架空の自転車乗りと、ハンドルを握る手を描いています。

<p align="center"><img src="assets/q26.webp" width="800" alt="錆色の帽子と緑のジャージの架空の女性が、砂利道で自転車のハンドルを握っています。Beatra AI で生成しています。"></p>

*錆色の帽子と緑のジャージの架空の女性が、砂利道で自転車のハンドルを握っています。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で架空の女性の斜め写真を。錆色のサイクルキャップ、苔色のジャージ、片手は自転車のハンドル、砂利道。ロゴも文字もなし。
```

プロンプト：

```text
Photoreal three-quarter portrait of a fictional woman in her late twenties with a short black crop, a small scar through the left eyebrow, wearing a rust-colored cycling cap and a moss-green wool jersey with no logos. She holds the bicycle handlebar with one hand, five natural fingers, and smiles with teeth unseen. Overcast daylight on a gravel path, pine trees blurred behind. Natural skin, correct eyes and ears. No text, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 1K · 3:4

Beatra で生成 · タスク task_mcp_b71e0d1eaf675f21f1d281f69271be4c381d85ce

<a id="infographics"></a>

## 図解とチャート

### 26. お茶の4ステップカード

四ステップのお茶カードで、Qwen Image 3.0 が二言語のラベルと四つのアイコンを一列に置いています。

<p align="center"><img src="assets/q27.webp" width="800" alt="横長のカードです。題は TEA STEPS です。番号付きのアイコンが四つ、一列です。Beatra AI で生成しています。"></p>

*横長のカードです。題は TEA STEPS です。番号付きのアイコンが四つ、一列です。Beatra AI で生成しています。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で横長の図解を作って。題は TEA STEPS、その下に泡茶四步。四つのラベルは KETTLE、LEAVES、WAIT、POUR。他の文字はなし。
```

プロンプト：

```text
Clean flat infographic on white, wide layout, lots of margin. Title exactly TEA STEPS in black sans-serif. Under it the Chinese line 泡茶四步 exactly. Four circles in a row containing only the digits 1 2 3 4, with the labels KETTLE, LEAVES, WAIT, POUR under them, each label one word, perfectly spelled. Simple line icons of a kettle, a leaf, a clock, and a cup. No other text, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 2K · 16:9

Beatra で生成 · タスク task_mcp_1f837487611da4da304c2d0a851e9b023a23562e

### 27. 一週間の杯数の棒グラフ

五本の棒の図で、Qwen Image 3.0 が決まった数値と曜日のラベルを置いています。

<p align="center"><img src="assets/q28.webp" width="800" alt="テラコッタ色の棒が五本。MON から FRI、値は 12、18、15、21、16。Beatra AI で生成。"></p>

*テラコッタ色の棒が五本。MON から FRI、値は 12、18、15、21、16。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で単純な棒グラフを作って。題は WEEKLY CUPS、副題は一周杯数。MON から FRI の棒の値は 12、18、15、21、16。他の文字はなし。
```

プロンプト：

```text
Simple bar chart on warm white. Title exactly WEEKLY CUPS in dark brown sans-serif. Subtitle exactly 一周杯数. Five vertical terracotta bars on a thin baseline, labeled under the axis exactly MON TUE WED THU FRI. Printed above the bars, the exact values 12 18 15 21 16 in that order. No grid, no legend, no other text, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 2K · 16:9

Beatra で生成 · タスク task_mcp_63bf1dc9e44ba4061c53a28af507bb91cf582c27

### 28. シダの世話の3列カード

三列の世話カードで、Qwen Image 3.0 がラベルだけを残し、他は空白にしています。

<p align="center"><img src="assets/q29.webp" width="800" alt="淡いカード。題は FERN CARE。三列のラベルは LIGHT、WATER、SOIL。Beatra AI で生成。"></p>

*淡いカード。題は FERN CARE。三列のラベルは LIGHT、WATER、SOIL。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で三列のカードを作って。文字は FERN CARE、蕨类养护、LIGHT、WATER、SOIL だけ。各列に単純なアイコン一つ、その下は空白。
```

プロンプト：

```text
Clean three-column care card on pale sage paper, wide layout, lots of empty margin. The only text in the whole image is these five strings, each perfectly spelled, and nothing else: the title FERN CARE, the Chinese line 蕨类养护 directly under the title, and the three column labels LIGHT, WATER, and SOIL. Under LIGHT draw only a simple sun icon. Under WATER draw only a simple drop icon. Under SOIL draw only a simple pot icon. The area under every icon is blank paper. Do not write sentences, captions, descriptions, small print, or placeholder words. No numbers, no logos, no watermark.
```

Qwen Image 3.0 · テキストから画像 · 2K · 16:9

Beatra で生成 · タスク task_mcp_f2655d171c89420621e41849d0a73120a4d51468

### 29. Pollen Trail の模式図

小道の模式図で、Qwen Image 3.0 がラベル付きの道を描き、余分な語を入れていません。

<p align="center"><img src="assets/q30.webp" width="800" alt="クリーム色の図。点線が GATE から RIDGE へ、途中に SPRING。Beatra AI で生成。"></p>

*クリーム色の図。点線が GATE から RIDGE へ、途中に SPRING。Beatra AI で生成。*

エージェントへの依頼例：

```text
Qwen Image 3.0 で単純な道の図を描いて。題は POLLEN TRAIL、その下に花粉径。点線が GATE から RIDGE へ、途中が SPRING。語はこれだけ。
```

プロンプト：

```text
Simple schematic trail map on cream paper, not a real place. A single dotted path from a square labeled GATE to a triangle labeled RIDGE, with a small circle labeled SPRING halfway. Title at the top exactly POLLEN TRAIL and the Chinese line 花粉径 under the title. Those five words and the Chinese line are the only text. Flat ink drawing, no logos, no watermark, no compass rose text.
```

Qwen Image 3.0 · テキストから画像 · 2K · 4:3

Beatra で生成 · タスク task_mcp_f35abee38d9a42f2f62840d1ba7f616e04937ac6

## Beatra で動かす理由

- このリストで使ったモデル：Qwen Image 3.0 Pro、Qwen Image 3.0。
- インストールは無料。生成のたびに Beatra アカウントのクレジットを消費しますが、課金されるのは、その生成を明示的に依頼したとき、または確認カードを承認したときだけです。
- 対応エージェント：Claude Code、Cursor、Codex、Windsurf、Cline、OpenClaw。

## コントリビュート

追加してほしい事例は issue でどうぞ。第三者の作品は受け付けていません。

## ライセンス

このリストのプロンプトと素材は CC BY 4.0 です。転載にはクレジットとリンクが必要です。

## 関連リンク

- [Awesome Wan 3.0 Video](https://github.com/beatra-ai/awesome-wan-3-video)
- [AI Image Generator Skill](https://github.com/beatra-ai/ai-image-generator-skill)
- [Beatra Skills](https://github.com/beatra-ai/beatra-skills)
- [beatra.ai](https://beatra.ai/?utm_source=github&utm_medium=cases_list&utm_campaign=awesome-qwen-image-3)
