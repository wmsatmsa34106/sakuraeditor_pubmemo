1. [back](./README.md)
1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/38535704
   - build.rev.1.0.3635 ... メモリDCを利用しない場合はアンダーライン描画を行描画の直後に行う事でちらつきを抑える
1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/38317744
   - build.rev.1.0.3572 ... 指摘対応(ソースの文字列長も考慮する)
   - そのほか、前リビジョンとの間で興味深いコミット/ プルリク
       a. Pull request #1596 - バックアップで詳細$0～$9指定を使いMAX_PATH近いパスを保存しようとすると落ちる不具合を修正
            - https://github.com/sakura-editor/sakura/pull/1596
       a. Pull request #1583 - このファイルのパス名とカーソル位置をコピーでのバッファオーバーランの不具合対応
           - https://github.com/sakura-editor/sakura/pull/1583
       a. Pull request #1569 - x64ビルドでの警告を減らす為に TextOutW 関数の第5引数（int型)に渡す型がintになるように対策
           - https://github.com/sakura-editor/sakura/pull/1569
       a. "マウスホイールでのフォントサイズ変更"
           - Pull request #1536 - sakura.iniがない状態で起動した時にマウスホイールでフォントサイズが変更できない問題を修正
               - https://github.com/sakura-editor/sakura/pull/1536
           - Pull request #1513 - マウスホイールでのフォントサイズ変更をパーセンテージに基づいて行うようにする
               - https://github.com/sakura-editor/sakura/pull/1513
       a. Pull request #1560 - テストが異常終了する対策
           - https://github.com/sakura-editor/sakura/pull/1560
       a. 独自定義assertマクロを改良する/ rev.1.0.3475
           - https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37906497
       a. Pull request #1547 - CTextMetrics のコードを整理する
           - https://github.com/sakura-editor/sakura/pull/1547
       a. Pull request #1538 - WinMainTestを改良して効率的なテストを実現する
           - https://github.com/sakura-editor/sakura/pull/1538
       a. Pull request #1533 - COMエラー情報クラスを追加する
           - https://github.com/sakura-editor/sakura/pull/1533
       a. VS2017でのコンパイルエラー解消/ rev.1.0.3424
           - https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37612836
       a. MinGWエラー対策 必要なサイズ+1を確保して切り詰めるように修正/ rev.1.0.3406
           - https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37492316
           - PullRequest ; Pull request #1522 - 独自関数strprintfをC++風に使えるように拡張します。
               - https://github.com/sakura-editor/sakura/pull/1522
       a. help配下のShift_JISファイルのために.gitattributesを追加する/ rev.1.0.3396
           - https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37471242
1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37420094
   - build.rev.1.0.3380 ... tchar_printfを除去する
       a. 全体構成の見直し/ rev.1.0.3365
           - https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37412122
           - Pull request #1512 - exeと設定ファイルのパス取得関数をリファクタリングしてテストできるようにする
               - https://github.com/sakura-editor/sakura/pull/1512
1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/37407600
   - build.rev.1.0.3358 ... iniファイルパスの取得関数を追加
1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/36926303
   - build.rev.1.0.3309 ... ステータスバーにフォントサイズを表示する
1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/36578099
   - build.rev.1.0.3275 ... ファイル保存時の既定のファイル名を日時にする
1. a
1. a
1. a
