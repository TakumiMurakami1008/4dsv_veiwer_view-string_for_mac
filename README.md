<<<<<<< HEAD
4dsv_viewer_macが実行できない場合
=======
# 4dsv_viewer_unity

4次元ストリートビューのバレットタイム可視化のビューア
mac用

unityで作成

## 4dsv_viewer_macが実行できない場合
>>>>>>> ab37e8ff90288704244c500886999ab32af89fa4

・以下のコマンドを打つ

　chmod a+x 4dsv_viewer_mac.app/Contents/MacOS/*

<<<<<<< HEAD
　xattr -d com.apple.quarantine 4dsv_viewer_mac.app
=======
　xattr -d com.apple.quarantine 4dsv_viewer_mac.app

## 操作方法

キーボードで操作可能

```

A：視線を左方向に回転
D：視線を右方向に回転
W：視線を上方向に回転
S：視線を下方向に回転
Q：視線を反時計回りに回転
E：視線を時計回りに回転

            Space：動画を再生・停止
            Enter：動画を1フレーム進める
BackSpace, Delete：動画を1フレーム戻す

      I：曲線の前方に移動
Shift+I：曲線の後方に移動
      J：次の曲線に移動
Shift+J：前の曲線に移動
      K：次の可視化手法に変更
Shift+K：前の可視化手法に変更

```
マウス操作でカメラの回転が可能

スライドバーで動画のフレーム移動が可能
>>>>>>> ab37e8ff90288704244c500886999ab32af89fa4
