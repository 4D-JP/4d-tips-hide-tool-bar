# 4d-tips-hide-tool-bar

#### 問題

アプリケーションをカスタムモードで開始すると，スプラッシュ画面とメニューバーの間に隙間ができます。

4Dを起動すると，まず最初に**ユーザーモードのツールバーが表示されるため**です。

![n47zr-6yyzd](https://user-images.githubusercontent.com/10509075/87101493-380ef080-c28a-11ea-9140-5989866cd26e.gif)

#### 回避策

[**ビルド**](https://doc.4d.com/4Dv15/4D/15.6/Building-a-4D-Application.300-3818453.ja.html)を実行し，シングルユーザーアプリケーションを**ファイナライズ**すれば，ユーザーモードのツールバーは表示されないので，メニューバーのすぐ下にスプラッシュ画面が表示されるようになります。

![bfbda-adrg0](https://user-images.githubusercontent.com/10509075/87100862-64c20880-c288-11ea-8294-7bb50f69b0bc.gif)
