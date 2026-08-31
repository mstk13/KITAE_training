# KITAE Training

**減量 × 筋力維持/向上** を両立するトレーニング管理アプリ。

**アプリを開く → https://mstk13.github.io/KITAE_training/**

## Current Records / Goals

| Lift | Current | Target |
|------|---------|--------|
| Squat | 130kg | 維持〜微増 |
| Bench Press | 100kg | 維持〜微増 |
| Deadlift | 120kg | 維持〜微増 |
| Snatch | 60kg | 維持〜微増 |
| **Body Weight** | **87kg** | **81-82kg (2ヶ月)** |

## Weekly Schedule (減量×筋力向上 最終版)

| Day | Theme | Key Exercises |
|-----|-------|---------------|
| **Mon** | C': 軽スナッチ+可動域 | 可動域ドリル, スナッチ(テクニック) 5×2 |
| **Tue** | A: 下半身(尻・ハム) | バックスクワット 4×5, ヒップスラスト, RDL, スイング |
| **Wed** | D: 上半身+体幹 | ベンチプレス 4×5, ワンハンドロー, アブローラー |
| **Thu** | C: スナッチ+パワー | スナッチ高重量, バックオフ, プッシュプレス |
| **Fri** | A': デッドリフト+下半身 | デッドリフト 4×4-5, グルートブリッジ, ステップアップ |
| **Sat** | D': ベンチ重量日+上半身 | ベンチプレス 3×3 @90kg, ショルダープレス, ラットプルダウン |
| **Sun** | R: 回復日 | モビリティ, 軽い瞬発系 |

**毎日: 傾斜15%ウォーキング 20-30min** (4.5-5.5km/h) で締め

## Features

- **Today**: 当日メニュー表示 + チェックで完了管理 + ワークアウト記録
- **Body Weight**: 毎日の体重記録 + 14日履歴 + 週平均表示
- **Weekly Completion**: 月〜日の達成状況を一覧グリッドで可視化
- **Menu**: 全種目の一覧管理(Weight / Plyo / Cardio)
- **Log**: 過去の記録一覧(Weight/Cardio フィルター)
- **Progress**: 種目別の重量・ボリューム推移グラフ + 体重チャート(7日移動平均)
- **Schedule**: 週間スケジュール表示・編集

## 進行ルール

1. 規定セット×レップを全てこなせたら翌週 +2.5kg
2. 4週目はデロード: メイン種目70%・セット半分
3. 8週ごとに3RMテストで筋力確認(減量中1RM挑戦はしない)
4. 疲労サイン(2週連続低下 / 慢性疲労 / 体重急落)→ 木or土を休養に差替え

## 栄養

- カロリー: 2,000-2,200 kcal/日
- タンパク質: 130-150g/日(体重×1.5-1.7g)
- トレーニング前後に糖質を寄せる
- 睡眠7時間・毎朝同条件で体重記録(週平均で判断)
- 詳細 → [食事管理プラン](diet_plan.md)

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
