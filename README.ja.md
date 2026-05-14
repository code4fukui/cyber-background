# cyber-background

WebGL 2.0のトランスフォームフィードバック（Transform Feedback）機能を活用した、サイバーテーマのパーティクルエフェクトのサンプルプロジェクトです。本プロジェクトは、ICS MEDIAの[170706_webgl2_feature/transform_feedback](https://github.com/ics-creative/170706_webgl2_feature)リポジトリをフォークしたものです。

## プレビュー

このプロジェクトでは、10万個のパーティクルによる動的なシステムをレンダリングします。パーティクルはカールノイズとパーリンノイズによって流体のような渦巻き運動を描き、常に変化し続けるビジュアルを生み出します。色は鮮やかなネオンカラーのパレットを循環し、独特のサイバーパンクな美しさを表現しています。カメラはインタラクティブに操作可能で、マウスやタッチ操作でパーティクルクラウドの周囲を旋回（オービット）させることができます。

![Cyber Background Demo](https://raw.githubusercontent.com/ics-creative/170706_webgl2_feature/master/article/img/screenshot.gif)

## 特徴

- **WebGL 2.0 トランスフォームフィードバック:** パーティクルの物理シミュレーションと更新をすべてGPU上で効率的に実行します。
- **動的パーティクルシステム:** 10万個のパーティクルを管理し、毎フレーム位置と速度を計算します。
- **高度なノイズアルゴリズム:** パーリンノイズとカールノイズを使用し、複雑で有機的な流体の動きを生成します。
- **鮮やかなシェーディング:** HSVからRGBへ変換するシェーダーを実装し、滑らかに循環するネオンカラーを実現します。
- **インタラクティブな3Dカメラ:** オービットコントローラーにより、マウス、タッチ、キーボードでシーンを簡単にナビゲーションできます。

## はじめに

### 前提条件

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node.jsに同梱)

### インストールと実行

1. リポジトリをクローンします:
    ```bash
    git clone https://github.com/your-username/cyber-background.git
    cd cyber-background
    ```

2. 依存関係をインストールします:
    ```bash
    npm install
    ```

3. 開発サーバーを起動します:
    ```bash
    npm run start
    ```
    起動すると、デフォルトのブラウザでデモが開きます。

## 技術スタック

- **レンダリング:** WebGL 2.0
- **言語:** TypeScript
- **数学ライブラリ:** gl-matrix
- **ビルドツール:** Gulp、Webpack、BrowserSync

## 参考資料

- [サンプルで理解するWebGL 2.0 - ChromeとFirefoxが対応したWebGL 2.0の利点 - ICS MEDIA](https://ics.media/entry/16060/)
- [CSSでテキストやボタン、ボーダーにネオンライト効果を実装する方法 | COLISS](https://coliss.com/articles/build-websites/operation/css/css-neon-sign-effects.html)

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) を参照してください。
