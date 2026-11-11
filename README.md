# yuPad43 ZMK driver

IQS9151搭載のyuPad43（10 RX × 9 TX）向けZMKモジュールです。

[接続・導入ガイド](https://github.com/yuchamichami/yuPad43/blob/main/docs/README.md#zmk) · [XIAO用設定例](https://github.com/yuchamichami/yuPad43/tree/main/firmware/xiao-example)

基準はZMK v0.3.0、2026-10-30のATI通信修正版です。校正品質・BLE・異常時の復旧は未検証または調整が残っています。旧13 × 12版、2枚重ね版、CoreX用パッドには適用できません。

## ライセンス

ShiniNet / zmk-driver-iqs9151（MIT License）を基に、yuPad43向けの電極設定・初期化設定・ATI通信処理を変更しています。

Copyright (c) 2026 ShiniNet。全文は [LICENSE](LICENSE) を参照してください。
