# 3D Model Viewer

任意の glb/gltf をブラウザでぐりぐり回せる簡易ビューワー（Google `<model-viewer>` 使用）。

- **公開**: GitHub Pages（`nattsu628878/model-viewer`）
- **操作**: ドラッグで回転 / ホイールでズーム / 右ドラッグで平行移動
- **モデル**: ヘッダの `model` から同梱glbを選択、または `glbを開く`／画面へドラッグ&ドロップでローカルglbを表示
- **同梱glbの追加**: `models/` に置き、`index.html` の `MODELS` 配列に1行足す

## 由来
`dev/experiments/pixel-render-test`（Blender→Godotドット絵）で作った minilogue の glb を、
ドット絵ではなく**素の3D**でインタラクティブに確認するための道具。ドット絵の一覧は別途
[pixel-render-gallery](https://nattsu628878.github.io/pixel-render-gallery/minilogue.html)。
