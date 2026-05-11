# Dark Cola MOD — ARK: Survival Ascended

ARK: Survival Ascended 用のカスタム炭酸飲料MOD。

## 概要

**Dark Cola** はARKの世界で飲める炭酸エナジードリンク。飲むと以下の効果が得られる:

- **カフェインラッシュ** — 移動速度 +15% (60秒間)
- **スタミナ回復** (+40 / 時間経過で回復)
- **水分回復** (+25 / 即時)
- 炭酸飲料アイコン表示

## フォルダ構成

```
dark-cola-mod/
├── DarkCola.uplugin          # MODプラグイン定義
└── Source/
    ├── Blueprints/
    │   └── PrimalItemConsumable_DarkCola_v3.uasset  # アイテム本体
    ├── Buffs/
    │   └── Buff_DarkCola.uasset     # カフェインラッシュ (速度+15%, 60秒)
    ├── Engrams/
    │   └── EngramEntry_DarkCola.uasset  # エングラム登録
    ├── ModDataAsset_BlankMod.uasset     # MODデータアセット
    └── PrimalGameData_BP_BlankMod.uasset  # MOD中核BP
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
