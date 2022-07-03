# apwのディレクトリ構成、デプロイ先など
➀apw のディレクトリ構成

・nginx(web-server1)

・apache(web-server2)

・mysql(web-db)



➁nginx(web-server1)とapache(web-server2)では、

・Dockerfile

 ・docker-comopose.yml
 
 ・index.html
 
 
 ・上記の3ファイルを同階層で構成


➂web-db(mysql)

　・Dockerfile
 
　・docker-compose.yml
 
  ・上記の2ファイルを同階層で構成



〇AWSのEC2にはweb-server1のみをデプロイし、index.htmlをブラウザ表示できるようにしてあります。

・http://54.168.217.58/index.html



〇今後の発展
・index.html表示から言語を使ったCRUDの実装。

・Ansible等の自動構成ツールの導入

・AWSサービスのECSやEKSなどのDockerと併用されるAWSサービスをCloudFormatioやTerraformなどのIaC化を行なう。
