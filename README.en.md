# yuPad43 ZMK driver

[日本語](README.md) | English

A ZMK module for the IQS9151-based yuPad43 touchpad (10 RX × 9 TX), targeting ZMK v0.3.0.

[Connection guide](https://github.com/yuchamichami/yuPad43/blob/main/README.en.md) · [ZMK setup](https://github.com/yuchamichami/yuPad43/blob/main/docs/zmk.md) (Japanese) · [XIAO configuration example](https://github.com/yuchamichami/yuPad43/tree/main/firmware/xiao-example)

## Operation

Use one finger to move the pointer and two fingers to scroll vertically or horizontally. The example uses **scroll level 0 (standard)**, with pointer and scroll inertia disabled.

The electrode configuration is specific to yuPad43. The calibration target is 400, touch and release thresholds are 30 and 26, and Finger Split Factor is 0. Operation has been checked with a 1 mm PLA cover and a XIAO nRF52840 connected over USB.

## License

Based on ShiniNet / zmk-driver-iqs9151 (MIT License), with changes to the electrode configuration, initialization settings, and ATI communication for yuPad43.

Copyright (c) 2026 ShiniNet. See [LICENSE](LICENSE) for the full license text.
