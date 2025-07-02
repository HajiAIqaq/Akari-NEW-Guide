# segatools カードリーダー接続設定（AimeIO）

aimeioを amdaemon.exe と同じディレクトリにコピーし、ゲームフォルダ内の segatools.ini を開いて、以下の設定を行ってください。

1. `[aime]`項目を探し、enableを`1`に設定します。

```ini
[aime]
enable=1
```
2. `[aimeio]`項目を探し（見つからない場合はファイルの末尾に手動で追加）、以下のように設定します。

```ini
[aimeio]
path=AkariIO.dll
```

**aimeioファイルは、本ドキュメントのGitHub Releaseからダウンロードしてください。出所不明のDLLは、絶対に使用しないでください。**

中国のユーザーで、SEIKANまたはStavonaのQQグループに参加されている方は、グループファイルからもダウンロード可能です。
