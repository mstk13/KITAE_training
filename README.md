# KITAE Training

**筋力向上 + 爆発力(垂直飛び110cm) + 減量** を同時に追求するトレーニング管理アプリ。

**アプリを開く → https://mstk13.github.io/KITAE_training/**

## Current Records

| Lift | Weight |
|------|--------|
| Bench Press | 105kg |
| Squat | 140kg |
| Deadlift | 130kg |
| Snatch | 60kg |

## Goals

- BIG3 + Snatch の重量向上
- 垂直飛び 110cm
- 減量(毎日ウォーキング 20-30min)

## Weekly Schedule

| Day | Theme | Key Exercises |
|-----|-------|---------------|
| **Mon** | 下半身筋力 + 爆発力 | Squat 5x5@120kg, Front Squat, Box Jump, Depth Jump, Broad Jump |
| **Tue** | 上半身(押す) | Bench 5x5@90kg, Incline, OHP, Dips, Med Ball Slam/Chest Pass |
| **Wed** | 休息 + 連動維持 | Kettlebell Swing, Walking |
| **Thu** | 爆発力 + スナッチ | Power Clean, Snatch 5x3@50kg, Hang Clean, Jump Squat, Tuck Jump |
| **Fri** | 上半身(引く) + 下半身補助 | Deadlift 5x5@110kg, RDL, Row, Pull-ups, KB Swing |
| **Sat** | 休息 + 連動 | Broad Jump, Walking |
| **Sun** | 休息 + 連動 | Tuck Jump, Walking |

## Features

- **Today**: 当日のメニュー・目安重量の表示 + ワークアウト記録
- **Menu**: 全種目の一覧管理(追加/削除)
- **Log**: 過去の記録一覧(Weight/Cardio フィルター)
- **Progress**: 種目別の重量・ボリューム推移グラフ(Chart.js)
- **Schedule**: 週間スケジュール表示・編集(種目 | セットxレップ@重量)

## Usage

ブラウザで `index.html` を開く。

```bash
# WSL
explorer.exe "$(wslpath -w ~/KITAE_training/index.html)"

# macOS
open index.html

# Linux
xdg-open index.html
```

## Data

- **保存先**: ブラウザの localStorage(サーバ不要)
- **バックアップ**: Export ボタンで JSON ファイルにダウンロード
- **復元**: Import ボタンで JSON ファイルから読み込み
