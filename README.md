### sakuraeditor
- https://github.com/sakura-editor/sakura
    - https://github.com/sakura-editor/sakura.git
    - https://github.com/sakura-editor 

- CI-build topic
    - hisotry
        - https://ci.appveyor.com/project/sakuraeditor/sakura/history
    - Offical md link
        - https://github.com/sakura-editor/sakura#ci-build-appveyor
    - topic / [topic, build list's](./README.topic.md)
        1. https://ci.appveyor.com/project/sakuraeditor/sakura/builds/38317744
           - build.rev.1.0.3572 ... 指摘対応(ソースの文字列長も考慮する)

- adding command.
    1. streams/ Windows Sysinternals
        - https://docs.microsoft.com/ja-jp/previous-versions/bb897440(v=msdn.10)?redirectedfrom=MSDN
        - article.
            - https://www.atmarkit.co.jp/ait/articles/1001/14/news112.html
    1. build & exec
        - PUSHD %ClonePath%\Downloads
        - %LocalAppData%\Tools\Streams\streams64 -s -d *
        - %UserProfile:C:=D:%\Downloads\Streams\streams64 -s -d *
    1. work
        - ./tmp
    1. memo
        - ./readme.memo.md

- etc.
    - Windows Task Bar Path
        - "%AppData%\Microsoft\Internet Explorer\Quick Launch\User Pinned\TaskBar"
            - cf . https://www.pasoble.jp/windows/10/pindome-basyo.html
