
## コマンド一覧

<table>
 <tr>
  <td>
   <b>
    $ docker version<br>
    $ docker -v
   </b>
  </td>
  <td>Docker のバージョン確認</td>
 </tr>
 <tr>
  <td>
   <b>
    $ docker-compose version<br>
    $ docker-compose -v
   </b>
  </td>
  <td>docker-compose のバージョン確認</td>
 </tr>
 <tr>
  <td>
   <b>
    $ docker-machine version<br>
    $ docker-machine -v
   </b>
  </td>
  <td>docker-machine のバージョン確認</td>
</tr>
</table>  
<br>




<table>
<tr>
  <td><b>$ docker-compose up -d</b></td>
  <td>コンテナの作成と開始</td>
 </tr>
 <tr>
  <td><b>$ docker-compose ps</b></td>
  <td>起動中のコンテナ一覧表示（docker-compose）</td>
 </tr>
 <tr>
  <td><b>$ docker ps</b></td>
  <td>起動中のコンテナ一覧表示（docker）</td>
 </tr>
 <tr>
  <td><b>$ docker ps -a</b></td>
  <td>起動してないものも含む全てのコンテナ一覧表示 （docker）</td>
 </tr>
 <tr>
  <td><b>$ docker rm xxxxx</b></td>
  <td>コンテナの削除 （docker）</td>
 </tr>
</table>  
<br>



<table>
<tr>
  <td><b>$ docker images</b></td>
  <td>イメージ一覧 （docker）</td>
 </tr>
 <tr>
  <td><b>$ docker rmi xxxxx</b></td>
  <td>イメージの削除 （docker）</td>
 </tr>
 <tr>
  <td><b>$ docker rmi xxxxx -f</b></td>
  <td>強制的なイメージの削除 （docker）</td>
 </tr>
</table>  
<br>


<table>
<tr>
  <td><b>$ docker volume ls</b></td>
  <td>ボリューム一覧</td>
 </tr>
 <tr>
  <td><b>$ docker volume rm xxxxx</b></td>
  <td>ボリュームの削除</td>
 </tr>
</table>  
<br>


<table>
<tr>
  <td><b>$ docker stop</b></td>
  <td>サービスの停止</td>
 </tr>
 <tr>
  <td><b>$ docker down</b></td>
  <td>コンテナの停止</td>
 </tr>
</table>  
<br>


<table>
<tr>
  <td><b>docker-compose ps –service</b></td>
  <td>docker-composeで起動中のサービス名を表示する</td>
</tr>
<tr>
  <td><b>docker-compose exec db bash</b></td>
  <td>docker-composeで起動中の「DB」へアクセスする</td>
</tr>
<tr>
  <td><b>mysql -u docker_user -p</b></td>
  <td>mysqlに「docker_user」としてログインする （このあとDBのパスワードを求められる）</td>
</tr>
<tr>
  <td><b>use docker_db</b></td>
  <td>「docker_db」へアクセス</td>
</tr>
<tr>
  <td><b>show tables;</b></td>
  <td>DB内のテーブルを参照</td>
</tr>
<tr>
  <td><b>exit</b></td>
  <td>mysqlやexecの処理を抜ける</td>
</tr>
</table>  
<br>


<table>
<tr>
  <td><b>docker ps</b></td>
  <td>xxxxxxxxxx</td>
</tr>
<tr>
  <td><b>docker stop $CONTAINER_ID</b></td>
  <td>xxxxxxxxxx</td>
</tr>
<tr>
  <td><b>docker kill $CONTAINER_ID</b></td>
  <td>xxxxxxxxxx</td>
</tr>
</table>  
<br>

<br><br>


## wordpress関連参考
https://github.com/t-nashi/Docker-wordpress/blob/master/README.md	
<br><br>


## windows（2020/04/04sat）

<b>$ docker -v</b><br>
Docker version 19.03.1, build 74b1e89

<b>$ docker-compose -v</b><br>
docker-compose version 1.24.1, build 4667896b

<b>$ docker-machine -v</b><br>
docker-machine version 0.16.1, build cce350d7
<br><br><br>







