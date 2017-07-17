# atomPackages

ATOMで使ってるパッケージを公開。
こんなのを使ってるという覚書（自分用メモ）

#### パッケージ情報の保存
```
apm list --installed --bare > atom-packages.txt
```
#### パッケージのリストア
```
apm install --packages-file atom-packages.txt
```
