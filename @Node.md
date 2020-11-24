
## 知っておくと便利なnpmコマンド一覧
| コマンド                     | 内容                                                                                                 | 
| :--------------------------- | :--------------------------------------------------------------------------------------------------- | 
| npm root -g                  | グローバルのルート（node_modules）を調べる                                                           | 
| npm root                     | プロジェクトのルート（node_modules）を調べる                                                         | 
| npm ls -g --depth=0          | グローバルにインストールされているパッケージを確認                                                   | 
| npm ls --depth=0             | プロジェクトにインストールされているパッケージを確認                                                 | 
| npm init -y                  | package.jsonをプロジェクトに生成（オプション「-y」が全てyes回答のショートカット）                    | 
| npm install xxxxx --save     | プロジェクトにパッケージをインストールし、情報を「package.json」に書き込む（dependencies）           | 
| npm i xxxxx -s               | 上記のショートカットバージョン                                                                       | 
| npm install xxxxx --save-dev | プロジェクトにパッケージをインストールし、情報を「package.json」に書き込む（devDependencies-開発用） | 
| npm i xxxxx -D               | 上記のショートカットバージョン                                                                       | 
| npm -v                       | npmのバージョンを表示                                                                                | 
| npm run                      | package.json - scriptに記載した一覧が見れる                                                          | 
| npm show                     | package.jsonを表示                                                                                   | 
| npm remove -g xxxxx          | グローバルのパッケージをアンインストール                                                             | 
| npm remove xxxxx             | プロジェクトのパッケージをアンインストール                                                           | 
| npm outdated                 | npm installでインストールしたパッケージ(package.json)の現状と最新のバージョン確認                     | 









