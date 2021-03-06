<!-- 
# Getting started
 -->
# はじめに
<!-- 
**Gutenberg** is a codename for a whole new paradigm in WordPress site building and publishing, that aims to revolutionize the entire publishing experience as much as Gutenberg did the printed word. The project is right now in the second phase of a four-phase process that will touch every piece of WordPress -- Editing, **Customization** (which includes Full Site Editing, Block Patterns, Block Directory and Block based themes), Collaboration, and Multilingual -- and is focused on a new editing experience, the block editor (which is the topic of the current documentation).
 -->
**Gutenberg** は WordPress サイト構築およびパブリッシングにおけるまったく新しいパラダイムのコードネームです。Gutenberg プロジェクトは、グーテンベルクが印刷業界への影響と同じように、パブリッシング体験全体の革新を目的とします。プロジェクトは現在、WordPress のあらゆる部分を対象とする4つのフェーズ、「編集」「**カスタマイゼーション**」(これにはフルサイト編集、ブロックパターン、ブロックディレクトリ、ブロックベーステーマが含まれます)「コラボレーション」「マルチリンガル」のうち2番めのフェーズにあり、新しい編集体験、「ブロックエディター」にフォーカスしています。

<!-- 
![Quick view of the block editor](https://make.wordpress.org/core/files/2021/01/quick-view-of-the-block-editor.png)

**Legend :**
1. Block Inserter
2. Block editor content area
3. Settings Sidebar
 -->
![ブロックエディターのクイックビュー](https://make.wordpress.org/core/files/2021/01/quick-view-of-the-block-editor.png)

**凡例 :**
1. ブロックインスペクター
2. ブロックエディターコンテンツ領域
3. 設定サイドバー

<!--
Using a system of Blocks to compose and format content, the new block-based editor is designed to create rich, flexible layouts for websites and digital products. Content is created in the unit of blocks instead of freeform text with inserted media, embeds and Shortcodes (there's a Shortcode block though).
-->
新しいブロックエディターは「ブロック」システムを採用し、コンテンツを組み合わせて整形していきます。ブロックエディターは、Web サイトやデジタル製品用にリッチでフレキシブルなレイアウトを作成できるようデザインされています。コンテンツはブロックのユニットとして作成し、これまでのフリーフォームテキストにメディアやオブジェクトやショートコードを埋め込む方法とは異なります(念のため伝えておくと「ショートコード」ブロックがあります)。

<!--
Blocks treat Paragraphs, Headings, Media, and Embeds all as components that, when strung together, make up the content stored in the WordPress database, replacing the traditional concept of freeform text with embedded media and shortcodes. The new editor is designed with progressive enhancement, meaning that it is back-compatible with all legacy content, and it also offers a process to try to convert and split a Classic block into equivalent blocks using client-side parsing. Finally, the blocks offer enhanced editing and format controls.
-->
ブロックは、段落、見出し、メディア、埋め込みオブジェクトなどすべてをコンポーネントとして扱い、互いを接続してコンテンツを作成し、WordPress データベース内に保存します。従来のフリーテキストにメディアやショートコードを埋め込むコンセプトは置き換えられした。新しいエディターは漸進的な拡張で設計されていて、すべてのレガシーなコンテンツに対して後方互換性があり、さらにクライアントサイドのパーシングを使用して単純に移行し Classic ブロックに対して、同等のブロックに変換、分割するプロセスを提供します。

<!--
The Editor offers rich new value to users with visual, drag-and-drop creation tools and powerful developer enhancements with modern vendor packages, reusable components, rich APIs and hooks to modify and extend the editor through Custom Blocks, Custom Block Styles and Plugins.
-->
ブロックエディターはユーザーにリッチで新しい価値を届けます。ブロックエディターの機能としては、ビジュアルでドラッグアンドドロップ対応の作成ツール、最新のベンダーパッケージを使用したパワフルな開発拡張、再利用可能コンポーネント、カスタムブロックやカスタムブロックスタイル、プラグインを通じたエディターの変更、拡張が可能なリッチな API とフックがあります。

<!-- 
## Quick links
 -->
## クイックリンク

<!-- 
### [Create a Block Tutorial](/docs/designers-developers/developers/tutorials/create-block/readme.md)
Learn how to create your first block for the WordPress block editor. From setting up your development environment, tools, and getting comfortable with the new development model, this tutorial covers all what you need to know to get started with the block editor.
 -->
### [ブロックの作成 チュートリアル](https://ja.wordpress.org/team/handbook/block-editor/tutorials/create-block/)
WordPress ブロックエディターにおける初めてのブロックの作成方法を学習します。開発環境の構築から、ツール、新しい開発モデルの説明まで、このチュートリアルはブロックエディターでの開発に必要なすべてをカバーします。

<!-- 
### [Develop for the block editor](https://developer.wordpress.org/block-editor/developers/)
Whether you want to extend the functionality of the block editor, or create a plugin based on it, you will find here all the information about the basic concepts you need to get started, the block editor APIs and its architecture.
 -->
### [ブロックエディターでの開発](https://ja.wordpress.org/team/handbook/block-editor/developers/)
ブロックエディターの機能の拡張やプラグインの開発で必要となる基本コンセプト、ブロック API とアーキテクチャを説明します。

<!-- 
- [Gutenberg Architecture](/docs/architecture/readme.md)
- [Block Style Variations](/docs/designers-developers/developers/filters/block-filters.md#block-style-variations)
- [Creating Block Patterns](/docs/designers-developers/developers/block-api/block-patterns.md)
- [Theming for the Block Editor](/docs/designers-developers/developers/themes/readme.md)
- [Block API Reference](/docs/designers-developers/developers/block-api/readme.md)
- [Block Editor Accessibility](/docs/designers-developers/developers/accessibility.md)
- [Internationalization](/docs/designers-developers/developers/internationalization.md)
 -->
- [Gutenberg アーキテクチャ](https://ja.wordpress.org/team/handbook/block-editor/architecture/)
- [ブロックスタイルバリエーション](https://developer.wordpress.org/block-editor/developers/filters/block-filters/#block-style-variations)
- [ブロックパターンの作成](https://ja.wordpress.org/team/handbook/block-editor/developers/block-api/block-patterns/)
- [ブロックエディター対応のテーマ](https://ja.wordpress.org/team/handbook/block-editor/developers/themes/)
- [ブロック API リファレンス](https://ja.wordpress.org/team/handbook/block-editor/developers/block-api/)
- [ブロックエディターのアクセシビリティ](https://ja.wordpress.org/team/handbook/block-editor/developers/accessibility/)
- [国際化](https://ja.wordpress.org/team/handbook/block-editor/developers/internationalization/)

<!-- 
### [Contribute to the block editor](/docs/contributors/readme.md)
Everything you need to know to start contributing to the block editor. Whether you are interested in the design, code, triage, documentation, support or internationalization of the block editor, you will find here guides to help you.
 -->
### [ブロックエディターへの貢献](https://ja.wordpress.org/team/handbook/block-editor/contributors/)
ブロックエディターへの貢献を始める場合に必要な情報です。ブロックエディターのデザイン、コード、トリアージュ、ドキュメント、サポート、国際化のどれに興味があっても必要なガイドを入手できます。

## 問い合わせ先
ブロックエディターハンドブックへのコメントは [Gutenberg GitHub リポジトリ](https://github.com/WordPress/gutenberg) へお願いします。

日本語訳については [日本語版リポジトリ](https://github.com/jawordpressorg/gutenberg)、または [WordPress の 日本語 Slack](https://ja.wordpress.org/support/article/slack/) 内の #docs チャンネルへお願いします。

## 参照
- [英語版ブロックエディターハンドブック](https://developer.wordpress.org/block-editor/)
- [英語版リポジトリ](https://github.com/WordPress/gutenberg)
- [日本語版リポジトリ](https://github.com/jawordpressorg/gutenberg)

## ブロックエディターハンドブック日本語版翻訳者

| GitHub Username | WordPress.org Username|
| --------------- | --------------------- |
| @naokomc | @nao |
| @ryo-utsunomiya | |
| @mypacecreator | @mypacecreator |
| @atachibana | @atachibana |
| @miminari | @mimitips |
| @shizumi | @Shizumi |
| @arm-band | @armband |

[原文](https://github.com/WordPress/gutenberg/tree/HEAD/docs/readme.md)

