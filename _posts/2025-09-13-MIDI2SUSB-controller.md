---
layout: post
title:  "MIDI 2.0 USB コントローラの作成"
date:   2025-09-13 21:09:10 +0900
categories: MIDI2
---
ねや楽器さんが[MIDI2_USB_Dev](https://github.com/kb-showhey/MIDI2_USB_Dev)というMIDI 1.0 - MIDI 2.0変換器を作っていたので、これを参考にRaspberry Pi Pico(RP2040)でMIDI 2.0 USB コントローラの作成を試みていた。ある程度動くようになったので、GitHubに置いておく。  
→ [MIDI2_USB_Toy](https://github.com/YuuichiAkagawa/MIDI2_USB_Toy)

開発途中の試行錯誤はXにポストしていたが、ある程度まとめておかないとわからなくなるので同リポジトリの[wiki](https://github.com/YuuichiAkagawa/MIDI2_USB_Toy/wiki)に整理している。

単体でメジャーOSに接続してMIDI 2.0として認識できるものを目指したもので、実用性はなくテストに使うものの位置付け。現時点ではまだ手軽にMIDI 2.0機器が入手出来る状況にないので、
個人的にはマイコンでホスト側を開発する際のテストデバイスとして使用する予定。

きちんとしたものが欲しい方はコレット楽器さんの[MIDI2USB CONVERTER](https://collet-inst.com/midi2usb-converter/)をご利用ください。

