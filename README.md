Sandbox
=======

これは、Eclipse上でTomcatプロジェクトが実行できることを確認するためのものです。

前提
----

以下をインストールします。

- Java11: [AdoptOpenJDK](https://adoptopenjdk.net/releases.html)など
- [Apache Tomcat 10](https://tomcat.apache.org/download-10.cgi)
- [Eclipse](https://www.eclipse.org/downloads/)

Eclipse Marketplaceで、以下をインストールします。

- Eclipse Tomcat Plugin 9.1.4

EclipseのPreferencesで、以下を設定します。

- Execution Environments: JavaSE-11
- Tomcat: Tomcat バージョン、Tomcat ホーム、コンテキスト宣言モード=Server.xml


実行方法
--------

1. Tomcat PluginでTomcatを起動します。
2. ブラウザから[サイトURL](http://localhost:8080/Sandbox/)を閲覧します。
