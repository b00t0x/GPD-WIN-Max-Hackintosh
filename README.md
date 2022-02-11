# GPD WIN Max Hackintosh
## 導入
https://b00tb00k.blogspot.com/2021/02/gpd-win-maxhackintosh_11.html

## 動作確認済み
### OS
* macOS 12.2.1 Monterey
* macOS 11.6.3 Big Sur
* macOS 10.15.7 Catalina

### 機能
* GPU アクセラレーション
* 内蔵サウンド
* キーボード
  * 輝度・音量調整ホットキー
* トラックパッド
* タッチパネル
* ゲームパッド
  * マウスモード
  * パッドモード ( 要 [360Controller](https://github.com/360Controller/360Controller) )
* 有線 LAN
* 無線 LAN
* ThunderBolt 3 映像出力
  * USB-C to DP 4K/60Hz
  * USB-C to HDMI 4K/60Hz
* バッテリー残量表示
  * 残量に 5% ほどズレがあるため [coconutBattery](https://coconut-flavour.com/coconutbattery/) の利用を推奨
* スリープ・復帰

## 動作しないもの・問題点
* ThunderBolt 3 ポートからの音声出力
* HDMI 映像・音声出力
* 無線 LAN の安定性
  * [itlwm](https://github.com/OpenIntelWireless/itlwm) の開発に依存

## 謝辞
* [@kingo132](https://github.com/kingo132/GPD-Win-Max-Hackintosh) : トラックパッドおよびタッチパネル設定、GPU設定
  * VoodooI2CGoodix.kext, SSDT-TPD0, SSDT-TPL1
  * `igfxfw=2`
* [@HMR](https://www.youtube.com/watch?v=WiP-NJGIKOs) : GPD WIN Max 用 mod BIOS
* [@RehabMan](https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/#post-1308261) : バッテリー SSDT 作成チュートリアル
