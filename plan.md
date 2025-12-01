# Plan

## Goals
- HTML/CSS/JSのみでGiga Wing風縦スクロールシューティング試作
- 反射シールドや敵ウェーブなど要求仕様の実装
- 単一HTMLでブラウザ即実行可能な状態にする

## Steps
1. ボス撃破演出仕様整理とフロー設計
2. 演出ロジック・アニメーション実装
3. UI (GAME CLEAR) 追加と静的確認

- Pixel Grid: [■■][■■][■■][■■] (100%)
- Condition: Normal

## Risks / Notes
- 反射シールドのタイミング処理と弾変換のバグ
- 60FPS維持のためオブジェクト数に注意

## Alternative Angle
- パフォーマンス問題が出たら敵数を減らし、反射弾生成を制限
