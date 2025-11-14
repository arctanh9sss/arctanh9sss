## はじめまして、李 宗翊（Tsung-Yi Lee）です

東京在住の台湾出身、情報工学専攻の大学院生です。  
主に Deep Learning、Computer Vision、Unity、C++ を中心に研究・開発を行っています。

現在の研究テーマは、小物体検出モデル（YOLO 系）を用いた PCB 欠陥検出です。  
また、Unity を活用した物理インタラクションの実装や 3D プロトタイプ開発にも取り組んでいます。

---

## Unity Demo – Black Hole Effect
Unity の Rigidbody 制御とパーティクル処理を組み合わせ、  
ブラックホールによる吸引効果を再現したデモです。

<img src="./image4.gif" width="600">

### 技術概要
- `Physics.OverlapSphere` による範囲内オブジェクト検出  
- 中心方向ベクトル `(center - position)` の算出  
- 距離に応じた減衰付き吸引力  
  `force = strength * (1 - distance/radius)^2`  
- `AddForce(..., ForceMode.Acceleration)` を用いた継続的吸引  
- コルーチンによる一定時間の引力処理  
- 最終的な速度リセットによる挙動安定化  

ブラックホール風の「徐々に中心へ吸い寄せられる」物理的挙動を実現しています。

---

## 研究・プロジェクト

### PCB 欠陥検出（Deep Learning / YOLO）
- DeepPCB データセットを用いた欠陥位置推定  
- YOLOv5 / YOLOv7 / YOLOv8 の性能比較  
- 小物体検出における YOLO 系モデルの挙動分析  
- SAHI（Slicing Aided Hyper Inference）の適用調査  
- Python、PyTorch、OpenCV を用いた再現実験とモデル評価  

---

### Unity – 物理インタラクション開発
- Black Hole 引力エフェクト（上記デモ）  
- キャラクター移動（歩行、ジャンプ、スプリント、スライド）  
- 壁面判定によるクライミング処理  
- Raycast / Collision / Rigidbody を用いた物理制御  
- Shader Graph を使用した簡易エフェクト生成  

※ 過去のプロトタイプは整理後、順次公開予定です。

---

## スキルセット
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white">
</p>

---

## GitHub Stats
![Stats](https://github-readme-stats.vercel.app/api?username=arctanh9sss&show_icons=true&hide=issues,contribs,prs,stars&theme=tokyonight)

---

## Contact
- Email: ian84421@gmail.com  
- 現在地: 東京  
- 出身: 台湾
