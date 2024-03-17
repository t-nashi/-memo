
## 知っておくと便利なnpmコマンド一覧
| コマンド                     | 内容                                                                                                 | 
| :--------------------------- | :--------------------------------------------------------------------------------------------------- | 
| npm root -g                  | グローバルのルート（node_modules）を調べる                                                           | 
| npm root                     | プロジェクトのルート（node_modules）を調べる                                                         | 
| npm ls -g --depth=0          | グローバルにインストールされているパッケージを確認                                                   | 
| npm ls --depth=0             | プロジェクトにインストールされているパッケージを確認                                                 | 
| npm -v                       | npmのバージョンを表示                                                                                | 
| npm run                      | package.json - scriptに記載した一覧が見れる                                                          | 
| npm show                     | package.jsonを表示                                                                                   | 
| npm init -y                  | package.jsonをプロジェクトに生成（オプション「-y」が全てyes回答のショートカット）                    | 
| npm install xxxxx --save<br>npm i xxxxx -s     | 【package.json/dependencies】プロジェクトにパッケージをインストール           | 
| npm install xxxxx --save-dev<br>npm i xxxxx -D | 【package.json/devDependencies※開発用】プロジェクトにパッケージをインストール | 
| npm ci                       | package-lock.json から依存関係をインストール（既に node_modules フォルダの中身があっても一旦削除）| 
| npm remove -g xxxxx          | グローバルのパッケージをアンインストール                                                             | 
| npm remove xxxxx             | プロジェクトのパッケージをアンインストール                                                           | 
| npm outdated                 | npm installでインストールしたパッケージ(package.json)の現状と最新のバージョン確認                     | 
| npm update -g xxxxx          | グローバルにインストールされている特定のパッケージをアップデート                     | 
| npm update xxxxx             | プロジェクトにインストールされている特定のパッケージをアップデート                     | 
| npm update                   | プロジェクトにインストールされている全てのパッケージをアップデート                     | 









