# ASCENDA — Concept Design Demo

> **CONCEPT DESIGN DEMO** — これはCVR最適化を目的としたランディングページ（LP）デザインのコンセプトデモです。
> 「ASCENDA」は**架空のブランド**であり、実在の企業・商品・人物・サービスとは一切関係ありません。
> 掲載の実績数値・お客様事例・比較表・FAQはすべて**サンプル文言**で、画像はAI（gpt-image-2）により生成された架空のビジュアルです。

BtoBマーケティング支援サービスを想定した、コンバージョン（CVR）最適化済みランディングページのデザインデモです。

🔗 **Live Demo** → https://suzuki-commits.github.io/ascenda-marketing-demo/

---

## ✨ 特徴 / Features

- **2026年のLPトレンドを反映** — 単一突出スタッツのHero、大型タイポグラフィ、Bentoグリッド、グラスモーフィズム
- **CVR導線設計** — 追従ヘッダー＋モバイル追従CTA、現状→改善のBefore/Afterセクション、6軸スキル図（ヘキサゴンSVG）、誠実なFinal CTA
- **高速表示** — 全画像をAVIF / WebP / PNG の3段フォールバック（`<picture>` ＋ `image-set()`）。PNG 19MB → AVIF 約456KB（**-97.6%**）
- **レスポンシブ ＋ 軽量アニメーション** — スクロールフェードイン、FAQアコーディオン、依存ライブラリなし

## 🛠 技術 / Built With

| 領域 | 使用技術 |
|---|---|
| フロントエンド | HTML / CSS / Vanilla JavaScript（単一ファイル・依存なし） |
| 画像生成 | Codex CLI ＋ gpt-image-2 |
| 画像最適化 | FFmpeg（libsvtav1 / libwebp） |
| オーケストレーション | Claude Code |

## 📁 構成 / Structure

```
.
├── index.html               # LP本体（単一ファイル）
└── images/everybeyond/      # AI生成画像（PNG / AVIF / WebP 各11枚）
```

## ⚠️ Disclaimer

本リポジトリはデザインのコンセプトデモであり、特定の実在企業の公式サイトではありません。
掲載内容・数値・事例・画像はすべてサンプルおよびAI生成です。

---

Built with **Claude Code** ＋ Codex CLI (gpt-image-2).
