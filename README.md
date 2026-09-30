# SOUNDROOM 1.0.4

切り取って、重ねて、自分の音に。

SOUNDROOMは、Windows向けの無料音楽編集アプリです。音声や動画を取り込み、波形を見ながらトリミングや音の重ね合わせ、音質調整を行えます。音声の編集・保存はPC内で行い、アカウント登録は不要です。

[SOUNDROOM 1.0.4をダウンロード](https://github.com/usapico/SOUNDROOM/releases/tag/v1.0.4) / [公式紹介ページ](https://usapico.com/works/soundroom)

## 主な機能

- 動画からの音声抽出、音声ファイルの読み込み
- 波形を見ながらトリミング・分割・複製
- 最大64トラックの重ね合わせ、音量・左右の定位、ミュート・ソロ
- 再生速度、フェード、EQ、リバーブの調整
- PCで再生している音を録音し、トラックに追加
- 波形の縦倍率とトラックの高さの調整
- WAV・MP3・FLACへの書き出し、トラック別の一括書き出し
- 編集プロジェクトの保存・読み込み

PCの録音はWindowsの標準の出力先の音を取り込みます。マイクは使わず、通知音なども含まれます。AIによる音源分離、自動作曲、MIDI編集には対応していません。

## 対象環境・使いはじめ方

Windows 10 22H2 / Windows 11（x64・64bit）向けです。

1. Releaseの `SOUNDROOM-1.0.4-windows-x64.zip` をダウンロードし、すべて展開します。
2. 展開した `SOUNDROOM-win32-x64` フォルダーの `LICENSE.txt` を確認し、`SOUNDROOM.exe` を起動します。
3. 音声や動画を追加して編集します。付属デモ音源でも操作を試せます。

インストールは不要です。実行ファイルだけを取り出さず、付属のファイルとフォルダーも一緒に保管してください。編集プロジェクトには音源本体を埋め込まないため、元の音源ファイルも同じ場所に保管してください。詳しい操作方法はZIP内の `README.md` を参照してください。

## 利用条件

個人・法人を問わず、私的利用・業務利用・営利利用・非営利利用が無料でできます。作者はSOUNDROOMで作成・編集した成果物について権利を主張しません。素材の著作権等の権利処理は利用者の責任で行ってください。

SOUNDROOM本体の無断再配布・販売および改変版の配布は禁止します。解析・逆コンパイル等は、法令上認められる場合を除き禁止します。本体のソースコードは公開していません。無保証・責任制限を含む利用条件の全文は、配布ZIP内の `LICENSE.txt` を確認してください。

第三者コンポーネントのライセンスで認められた権利は制限しません。FFmpeg・Electron・Chromium等には各コンポーネントのライセンスが優先して適用されます。

## FFmpegと第三者ライセンス

SOUNDROOMは音声処理にFFmpegを使用しています。独立したWindows x64版 `ffmpeg.exe` / `ffprobe.exe`（**LGPL-3.0-or-later**）を同梱しています。

[対応ソース・ライセンス全文・ビルド手順をダウンロード](https://github.com/usapico/SOUNDROOM/releases/download/ffmpeg-lgpl-20260930/SOUNDROOM-FFmpeg-LGPL-source-20260930.zip) / [ソース配布ページ](https://github.com/usapico/SOUNDROOM/releases/tag/ffmpeg-lgpl-20260930)

対応ソースにはFFmpeg・LAME・zlib、静的ランタイムのソースとパッチ、ビルド設定・手順・通知文を収録しています。利用コンポーネントの詳細は、配布ZIP内の `THIRD-PARTY-NOTICES.txt`、`FFmpeg-SOURCE-INFO.txt`、`LICENSE.electron.txt`、`LICENSES.chromium.html` 等を参照してください。Electron付属の `ffmpeg.dll` は独立したFFmpeg実行ファイルとは別のコンポーネントです。

専用ゲーム音楽・トラッカー形式（GME／OpenMPT）とDASH／IMFマニフェストは対象外です。

Copyright (c) 2026 usapico
