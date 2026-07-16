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
- **減量 (7/16〜8/31)**: 89kg/27% → 83-84kg/22-23% — [食事管理プラン](diet_plan.md)

## Weekly Schedule (減量期: 7/16〜8/31)

| Day | Theme | Key Exercises |
|-----|-------|---------------|
| **Mon** | 胸 + 三頭 | Bench 5x5, Incline DB, Dips |
| **Tue** | 背中 + 二頭 | Deadlift 5x5, Lat Pull, Row |
| **Wed** | 脚 | Squat 5x5, Leg Press, RDL |
| **Thu** | 肩 + 腹 | OHP, Side Raise, Hanging Leg Raise |
| **Fri** | 胸 + 背中 (Vol軽め) | Bench 3x8, Row 3x8, Pull-ups |
| **Sat** | 脚 or 弱点部位 | Front Squat, Bulgarian Split Squat |
| **Sun** | **完全休養** | — |

**毎回最後に傾斜MAXウォーク 25-30min** (心拍130-140目安)

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
