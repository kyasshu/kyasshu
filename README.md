# 小川慶介 / Keisuke Ogawa

材料科学の研究支援ツールと、ブラウザで動くインタラクティブ作品を制作しています。

## このGitHubの構成

公開作品は、中心リポジトリ **[nv-dft-viewer](https://github.com/kyasshu/nv-dft-viewer)** にまとめています。  
このリポジトリの中を、次の2つの入口に分けています。

```text
nv-dft-viewer
├─ 研究・可視化ツール
│  └─ NVセンターの構造、DFT / NEB計算用データ、解析手順
│
└─ ブラウザ・ミニゲーム集
   ├─ Asteroid Runner 3D
   ├─ ころころ工場
   ├─ 走る特訓
   ├─ ジャンプリズム
   ├─ 刹那の見切り
   └─ 四色記憶
```

## 初めて見る方へ

次の順番で見ると、全体を把握できます。

1. **[プロジェクトのトップページ](https://kyasshu.github.io/nv-dft-viewer/)**  
   研究テーマと、公開している機能の全体像を確認できます。

2. **[研究・可視化ツール](https://kyasshu.github.io/nv-dft-viewer/)**  
   ダイヤモンド中のNVセンター形成候補を、DFT / NEB計算へつなげるためのモデルと可視化を掲載しています。

3. **[ブラウザ・ミニゲーム集](https://kyasshu.github.io/nv-dft-viewer/pages/minigames.html)**  
   JavaScript、Canvas、Three.jsで制作した6作品を、選択画面からそのままプレイできます。

4. **[ソースコードとREADME](https://github.com/kyasshu/nv-dft-viewer)**  
   実装内容、ファイル構成、使用技術、実行方法を確認できます。

## それぞれの役割

| ページ | 内容 | 見てほしい点 |
| --- | --- | --- |
| プロジェクトトップ | 研究と制作物の総合入口 | 全体像とページ構成 |
| 研究・可視化ツール | NVセンター、DFT / NEB関連 | 研究内容をWeb上で整理・可視化する力 |
| ミニゲーム集 | 3D、Canvas、操作型コンテンツ | UI設計、ゲームロジック、タッチ対応 |
| GitHubリポジトリ | ソースコードと説明 | 実装方法、技術選定、制作過程 |

## 使用技術

- Web: HTML, CSS, JavaScript, Canvas API, Three.js, WebGL
- Programming: Python, JavaScript
- Scientific computing: DFT / NEB、Quantum ESPRESSO
- Delivery: GitHub Pages、静的Webアプリ
