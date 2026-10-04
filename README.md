# g2-models

Even G2 スマートグラス用アプリ(セキュマネ一問一答 for G2)の音声操作で使う、音声認識のデータ置き場です。
GitHub Pages で公開しています。

| ファイル | 内容 |
|---|---|
| [vosk-model-small-ja-0.22.tar.gz](https://ehoannet-dev.github.io/g2-models/vosk-model-small-ja-0.22.tar.gz) | Vosk の日本語小型モデル(49653498 バイト、SHA-256 `bf60ec48e3955c7d7fe1345001e2db2b42e41b8265a4be276512f2518fc83352`) |

- アプリは初回起動時にこのファイルを1回だけダウンロードし、スマホの中に保存して使います(2回目からはダウンロードしません)
- 音声の認識はスマホの中だけで行います。声をこのサイトや外部に送ることはありません

## 出典とライセンス

- 元のデータ: [vosk-model-small-ja-0.22](https://alphacephei.com/vosk/models)(Alpha Cephei Inc. / Vosk)
- ライセンス: Apache License 2.0(全文は [LICENSE](LICENSE))
- 変更点: 公式の zip を、ブラウザ版 Vosk(vosk-browser)で読み込める tar.gz 形式に詰め直しただけで、中身は変えていません
