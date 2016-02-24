# jrubyのインストール
* rbenvは入っているものとする

```
$ rbenv install jruby-1.7.23
```

# bundlerのインストール

```
$ gem install bunlder
```

# Logstashのインストール

```
$ brew install logstash
```

# JDBC driverのインストール
* http://dev.mysql.com/downloads/connector/j/ からインストール

```
$ tar xzvf mysql-connector-java-5.1.38.tar.gz
$ cd mysql-connector-java-5.1.38
$ $ sudo mv mysql-connector-java-5.1.30-bin.jar /usr/share/java
```

# クラスパスの追加
* .zshrcに下記のCLASSPATHを追加し設定を反映させる

```
export CLASSPATH=$CLASSPATH:/usr/share/java/mysql-connector-java-5.1.30-bin.jar
```

```
$ source ~/.zshrc
```

