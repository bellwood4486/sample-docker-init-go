# Sample of `docker init` for Go Server Application

`docker init`コマンドでGoのサーバーアプリケーション用ファイルをアップロードしただけのリポジトリです。

2024/07/26現在のDockerfileの推奨(している可能性の高い)書き方がつかめるかと思います。

## 環境

```shell
docker init

Client:
 Version:           27.0.3
 API version:       1.46
 Go version:        go1.21.11
 Git commit:        7d4bcd8
 Built:             Fri Jun 28 23:59:41 2024
 OS/Arch:           darwin/arm64
 Context:           desktop-linux

Server: Docker Desktop 4.32.0 (157355)
 Engine:
  Version:          27.0.3
  API version:      1.46 (minimum version 1.24)
  Go version:       go1.21.11
  Git commit:       662f78c
  Built:            Sat Jun 29 00:02:44 2024
  OS/Arch:          linux/arm64
  Experimental:     false
 containerd:
  Version:          1.7.18
  GitCommit:        ae71819c4f5e67bb4d5ae76a6b735f29cc25774e
 runc:
  Version:          1.7.18
  GitCommit:        v1.1.13-0-g58aa920
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0

```

## `docker init`の設定
```shell
docker init

? What application platform does your project use?  [Use arrows to move, type to filter]
> Go - (detected) suitable for a Go server application
  Python - suitable for a Python server application
  Node - suitable for a Node server application
  Rust - suitable for a Rust server application
  ASP.NET Core - suitable for an ASP.NET Core application
  PHP with Apache - suitable for a PHP web application
  Java - suitable for a Java application that uses Maven and packages as an uber jar
  Other - general purpose starting point for containerizing your application
  Don't see something you need? Let us know!
  Quit

? What application platform does your project use? Go
? What version of Go do you want to use? 1.22.4
? What's the relative directory (with a leading .) of your main package? .
? What port does your server listen on? 8080
```
