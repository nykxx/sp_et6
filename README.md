# SP ET6

**SP**lit  **E**ncoder **T**rackball **6**column  な3D形状のキーボードです。

<img src="https://github.com/user-attachments/assets/bea6841d-d3b0-4b6b-88e2-39a4ee5a1158" width=800>

bulblubさんのPMW3610 ブレイクアウトボード SEIBOKU（青墨）の使用を想定しています。

https://bulblub.booth.pm/items/6363907

PCBなしのハンドワイヤリングですが、ホットスワップにも対応しています。  
組み立てにはある程度の慣れ、あるいは根性が必要です。

## BOM

|品名                    |   数量 |
|------------------------|-------|
|Kailh MX hotswap socket |   45  |
|1N4148 Diode            |   66  |
|EC11 Rotary Encoder     |   1   |
|PMW3610 ブレイクアウトボード SEIBOKU（青墨）| 1 |
|3mm セラミックボール      | 3    |
|M3 ヒートインサートナット |   20  |
|M3 皿ネジ                |  20  |
|M2 ヒートインサートナット |   4  |
|M2 皿ネジ                |  4  |
|リポバッテリー            | 2   |
|スライドスイッチ          |  2  |
|MXキースイッチ            |  45 |
|MXキーキャップ（1u）      | 45  |
|エナメル線など            | 適量 |

親指キーにはいくつか1.25uも付けることができます。全部は無理ですが。

## Kicad回路図について

参考までにといった内容です。なんせPCBがなくハンドワイヤリングなので。

私が組み立てるときに確認するために作成したメモのようなものなので、回路図として完全には成立していません。

が、CharliePlexingのハンドワイヤリングにおいてはこれがあると随分助かります。

## FWについて

マトリクスの組み方、部品配置などが完全に一致しないと動作しないため、こちらも参考までに。

xiao seeed bleでCharliePlexingしてピン配置を合わせ、キーの位置も合わせれば使用可能ではあります。

また、FWにはt-oguraさんの [Prospector Scanner](https://github.com/t-ogura/zmk-config-prospector) を組み込んでいます。

本家と違ってドングルではないのでProspector本体がなくてもキーボードとして動作する素晴らしいアイディアです。大感謝。

## センサー基板について

[bulblubさんのPMW3610 ブレイクアウトボード SEIBOKU（青墨）](https://bulblub.booth.pm/items/6363907) の使用を想定したケースになっています。

その他のセンサを使用する場合はケースデータを修正するか、根性でフィッティングする必要があります。

一応、Fusion360で編集可能なf3dデータも含めています。

## ライセンス

本プロジェクトは **CC-BY-NC** とします。クレジット表記さえあれば非営利の範囲内での改変や配布が許可されます。

[Prospector Scanner](https://github.com/t-ogura/zmk-config-prospector)はt-oguraさんが[MITライセンス](https://opensource.org/license/mit) で公開してくださっています。

それと、ZMK FirmwareもMITライセンスです。

