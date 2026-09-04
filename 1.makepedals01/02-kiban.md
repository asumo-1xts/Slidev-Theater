---
layout: image-right
image: ./assets/my_2nd.jpg
hideInToc: true
---

<div class="text-right">私の人生２作目 →</div>

<br>

# まずは基板から

<br>

---
layout: two-cols
title: 基板の種類
---

::left::

## ユニバーサル基板

古き良き愛すべきもの

<div style="display: flex; align-items: center;">
	<img src="./assets/univ_design.jpg" width="45%" />
</div>


いま絶対こんなことできない、若かった…↓

<div style="display: flex; align-items: center;">
	<img src="./assets/univ_crazy.jpg" width="90%" />
</div>

::right::

## PCB基板

配線パターンが予め敷かれているので、<br>部品を取り付けるだけでよい

<div style="display: flex; align-items: center;">
	<img src="./assets/PCB_schematic.png" width="90%" />
</div>

<div style="display: flex; align-items: center;">
	<img src="./assets/PCB_2D.png" width="45%" />
	<img src="./assets/PCB_3D.png" width="45%" />
</div>

設計・発注の流れについては、<br>エフェクター作ろ概論Ⅱを受講してください

---
layout: two-cols
title: 登場人物紹介
---

::left::

## 抵抗 🤜🤛

<img src="https://akizukidenshi.com/img/goods/L/127908.jpg" width="30%" />

- 単位はオーム \[$\mathrm{Ω}$\]
- 基板上での表記：`〇〇 R` / `〇〇 k` / `〇〇 M`

## コンデンサ 🔋

<div style="display: flex; align-items: center;">
	<img src="https://akizukidenshi.com/img/goods/L/110147.jpg" width="30%" />
	<img src="https://akizukidenshi.com/img/goods/L/105332.jpg" width="30%" />
	<img src="https://akizukidenshi.com/img/goods/L/117897.jpg" width="30%" />
</div>

- 単位はファラド \[$\mathrm{F}$\]
- 基板上での表記：数字3桁（`104`とか） / `〇〇u`
- いくつか種類がある
  - 向きが決まっているものもある！

::right::

## ダイオード ⛔

<div style="display: flex; align-items: center;">
  <img src="https://akizukidenshi.com/img/goods/L/126040.jpg" width="30%" />
  <img src="https://akizukidenshi.com/img/goods/L/126037.jpg" width="30%" />
  <img src="https://akizukidenshi.com/img/goods/L/111577.jpg" width="30%" />
</div>

- 電流を一方向にしか流さない
- 基板上での表記：なんかこんな感じ `-[|  ]-`

## トランジスタ / FET/ IC 🪨

<div style="display: flex; align-items: center;">
	<img src="https://akizukidenshi.com/img/goods/L/126144.jpg" width="30%" />
	<img src="https://akizukidenshi.com/img/goods/L/109723.jpg" width="30%" />
	<img src="https://akizukidenshi.com/img/goods/L/111236.jpg" width="30%" />
</div>

- 電気信号を増幅する
- アクティブ（能動）素子

<br>

<div class="text-right">画像：<a href="https://akizukidenshi.com/">秋月電子通商HP</a>より</div>

---
layout: two-cols
title: 知っておこう
---

::left::

## 信号はいかにデカくなる？

<br>

### ✖ 入ってきた信号が<br>そのままデカくなって出ていく

<br>

### ⭕ 供給されたデカい電力が<br>入ってきた信号を真似て出ていく

<br>

<img src="./assets/zofuku.png" width="90%" />

::right::

## 基板を作るときのコツ

<br>

- 背の低い部品から実装する
	- 抵抗やダイオードが先、コンデンサは後
- ICやトランジスタはソケットを使う
	- 熱に弱いので壊しやすい

<div style="display: flex; align-items: center;">
	<img src="https://akizukidenshi.com/img/goods/L/100035.jpg" width="30%" />
	<img src="https://akizukidenshi.com/img/goods/L/100241.jpg" width="30%" />
</div>

<br>

- （余裕があれば）見た目のきれいさを意識する

<br>

<v-click>

### レッツゴー

#### 分かんなくなったら訊いてください

</v-click>