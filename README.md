# Minecraft用

[![](https://jitpack.io/v/xyz.mlserver/APIManager.svg)](https://jitpack.io/#xyz.mlserver/APIManager)
[![Twitter](https://badgen.net/twitter/follow/monster_2408?icon=twitter)](https://twitter.com/monster_2408)
[![Discord](https://discord.com/api/guilds/556844677115150366/widget.png)](https://discord.mlserver.xyz)
[Website](https://monster2408.com)

[Java Docs](https://docs.mlserver.jp/APIManager/)

```xml
<project>
    <repositories>
        <repository>
            <id>jitpack.io</id>
            <url>https://jitpack.io</url>
        </repository>
    </repositories>
    
    <dependencies>
        <dependency>
            <groupId>xyz.mlserver</groupId>
            <artifactId>APIManager</artifactId>
            <version>VERSION</version>
        </dependency>
    </dependencies>
</project>
```
# JavaDocの生成
JavaバージョンとJavadocバージョンの違いでエラーが出たため標準の機能でなく`mvn`を使用することになったため以下コマンドを使用すること
```shell
mvn javadoc:javadoc
```

## 
```html
<head>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="https://use.fontawesome.com/releases/v6.0.0/css/all.css" rel="stylesheet">
<script src="https://kit.fontawesome.com/159d32b7b7.js" crossorigin="anonymous"></script>
<!-- アイコン -->
<link rel="icon" href="https://docs.mlserver.jp/img/favicon.ico">
<link rel="apple-touch-icon" href="https://docs.mlserver.jp/img/apple-touch-icon.png" sizes="180x180">
<link rel="icon" type="image/png" href="https://docs.mlserver.jp/img/android-touch-icon.png" sizes="192x192">
</head>
```