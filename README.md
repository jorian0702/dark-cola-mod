# Dark Cola MOD — ARK: Survival Ascended

ARK: Survival Ascended 用のカスタム炭酸飲料MOD。

## 概要

**Dark Cola** はクラフト可能な消費アイテムで、ARKの世界における炭酸エナジードリンク。飲むと以下の効果が得られる:

- **スタミナ回復** (+40 スタミナ / 時間経過で回復)
- **移動速度バフ** (15%アップ / 60秒間)
- **水分回復** (+25 水分)
- 飲むモーション付き、炭酸のシュワシュワ音と泡エフェクト

## フォルダ構成

```
dark-cola-mod/
└── Source/
    ├── Blueprints/      # アイテムBP (PrimalItemConsumable_DarkCola)
    ├── Buffs/           # 速度バフ (Buff_DarkCola)
    ├── Icons/           # アイテムアイコン
    ├── Sounds/          # 炭酸効果音、飲む音
    ├── VFX/             # 泡パーティクル
    └── Engrams/         # エングラムエントリ (クラフト解放)
```

## クラフトレシピ

| 素材 | 個数 |
|------|------|
| 水入り容器 (水袋/水瓶/水筒) | 1 |
| スティムベリー | 10 |
| アズルベリー | 5 |
| ナルコベリー | 2 |
| 火薬粉 (Sparkpowder) | 1 |

製作場所: **調理鍋** または **工業用調理器具**

## 導入方法

1. MODファイルをサブスクライブ
2. サーバーまたはシングルプレイでMODを有効化
3. レベル25でエングラムを習得
4. 調理鍋で素材を入れてクラフト

## 開発環境

- ARK DevKit (Unreal Engine 5.5.4)
- Python (Unreal Editor Python Scripting)

## ライセンス

MIT License
