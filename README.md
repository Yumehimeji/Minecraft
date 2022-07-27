# はじめに
これら構造物は統合版で利用可能です。
## 構造物のインポート方法
以下のフォルダを開き、その中にmystructureという名でフォルダを作ります。

`C:\Users\[ユーザー名]\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\minecraftWorlds\[ワールドが保存されているフォルダ名]\behavior_packs`

作ったフォルダ内には構造物ファイル（.mcstructure）を保存しておくstructuresという名のフォルダと、manifest.jsonというファイルを作成します。
manifest.jsonには、次のようなコードを入力します。（チュートリアルビヘイビアーパックのところはあとで好きに書き換えられます）
```json:manifestjson
{
    "format_version": 1,
    "header": {
        "description": "チュートリアルビヘイビアーパック",
        "name": "チュートリアルビヘイビアーパック",
        "uuid": "e3c5a9be-1cfc-4a74-9f70-9213bab32090",
        "version": [0, 0, 1]
    },
    "modules": [
        {
            "description": "使われない",
            "type": "data",
            "uuid": "14d5fb6b-ef0a-47e5-8a98-d615709c1a03",
            "version": [0, 0, 1]
        }
    ],
    "dependencies": [
        {
            "uuid": "891f5751-bb0e-47c6-91f0-fdc4e76949ef",
            "version": [0, 0, 1]
        }
    ]
}
```
また、このファイルと同じところに画像ファイル（pack_icon.png）を作成します。（画像は何でもよい）これでマイクラ内のワールドの設定画面のビヘイビアパックに今作ったものが追加されるので有効にします。

参考サイトは[こちら](https://minecraft.fandom.com/ja/wiki/%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB/Bedrock_Edition/%E3%83%93%E3%83%98%E3%82%A4%E3%83%93%E3%82%A2%E3%83%BC%E3%83%91%E3%83%83%E3%82%AF%E3%81%AE%E4%BD%9C%E6%88%90)
#装置
## 骨粉製造機
### 最大効率
- 効率：毎分115個
- 大きさ：15×12×15(x×y×z)
[download](https://github.com/Yumehimeji/Minecraft/blob/main/%E6%9C%80%E5%BC%B7%E9%AA%A8%E7%B2%89%E8%A3%BD%E9%80%A0%E6%A9%9F.mcstructure)
<img src="https://github.com/Yumehimeji/Minecraft/blob/main/koppunhp.png" width=250>

### 高コストパフォーマンス
- 効率：毎分50個
- 大きさ：15××15(x×y×z)
[download](https://github.com/Yumehimeji/Minecraft/blob/main/%E9%AA%A8%E7%B2%89%E8%A3%BD%E9%80%A0%E6%A9%9F%EF%BC%88%E3%82%B3%E3%82%B9%E3%83%91%EF%BC%89.mcstructure)
<img src="https://github.com/Yumehimeji/Minecraft/blob/main/koppuncp.png" width=250>

### 低コスト

## ツツジ式原木製造機
### 1連
### 2連

- 大きさ：16××16(x×y×z)
[download](https://github.com/Yumehimeji/Minecraft/blob/main/2%E9%80%A3%E5%8E%9F%E6%9C%A8%E8%A3%BD%E9%80%A0%E6%A9%9F.mcstructure)
<img src="https://github.com/Yumehimeji/Minecraft/blob/main/gennboku2.png" width=250>

## 花増殖装置
