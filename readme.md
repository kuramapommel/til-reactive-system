# Write-Model 構築手順

※ この README 作成時のバージョン情報で記載  

下記コマンドを実行、[Giter8 テンプレート](https://github.com/akka/akka-http-quickstart-scala.g8) を使用してプロジェクトの雛形を構築

```
sbt new akka/akka-http-quickstart-scala.g8
```

インタラクティブモードで scala_version など色々聞かれるので、下記内容を参考に入力

```
name [My Akka HTTP Project]: write-model # 自分で決める
scala_version [2.13.12]: 2.12.18
akka_http_version [10.6.2]: 10.0.15
akka_version [2.9.2]: 2.5.32
sbt_version [1.9.9]: # デフォルトのままで良いため何も入力せずに ENTER
organization [com.example]: com.kuramapommel # 自分で決める
package [com.kuramapommel]: # 自分で決める
```
