---
title: "★初めてのMac★インストールしてよかったもの★"
emoji: "📷"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["mac", "windows", "shiftit", "HomeBrew"]
published: true
---

初の転職を成功させた主人公は、MacBookProを支給された。晴れてMacUserとなった彼が最初に思ったことは何だったのか。聞いてみた。

# どこで閉じるん？（操作）

彼が初めて開いたウィンドウ、それはSafari。しかし、右上のバッテンが見当たらない。

そうなのだ、Macは左上にある小さな赤丸なのだ。これはつらい。なんて閉じにくいのだ。Windowsなら

`alt + F4`

で閉じることができるのだがMacではどうするのか。

`command + Q`

彼には信じがたい光景だっただろう。なんせWindowsマークがないのだから。OSが変わるだけでキーボードの世界まで変わるとは驚きだった。

## 強制終了（操作）

しかし簡単にとじらせてくれないのがMac。強制的にとじるには

`option + command + esc`

で強制的に閉じる選択形式だ。ちなみにこれはWindwosのタスクマネージャーのプロセス強制終了と同じ効果があるようだ。

# 画面分割メンドー（shiftit）

Windowsではアクティブなウィンドウを画面分割で表示させたい場合は

`Windows + ←`

で左半分に画面が自動で分割できた。ちなみに4分割したい場合は

`Windwos + ←` したのち `Windows + ↑` とすれば、画面が左上にいき簡単に4分割することができた。

Macでは左上にある緑丸で最大2分割しかできない。もう一度言おう。Macでは2分割までしかできない。

崩れ去る主人公。しかし、そんな世の中に手を差し伸べてくれるのがIT界。ググれば[Shiftlt](https://github.com/fikovnik/ShiftIt/releases)というのが見つかったようだ。

これでWindwosみたいに簡単に
`Control + Option + ←`などで分割できるようになった。ちなみに、コマンドは編集可能なため、好きなコマンドが指定できるようだ。

# パッケージ管理しますか（HomeBrew）

とりあえず使用するのをひたすらインストールしていたWindows。しかし、どうもMacではインストールにひとクセありそうだ。

そこで先輩に教えてもらったのが[HomeBrew](https://brew.sh/index_ja)だ。ググった先にインストールshellが準備してあるため、`terminal`を起動して必殺コピペおじさんで簡単インスト。

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# 開発するならさ、Git必須じゃん

さ、いきなり`HomeBrew`の出番。

```shell
brew install git
```

これだけでgitのインストが完了。
三擦り半ですね。

# 他にもいろいろあるよね

こっからは地味にググってインストの繰り返し。

* VSCode
* Google Chrome
* Slack

# VSCodeの拡張機能って

こりゃまたたくさんあるけど、日本人なので日本語化しときますか。

* Japanese Language Pack

# 最後に

他にもたくさんあるけど、随時更新していくよ♪

