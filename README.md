# README

## 1. 環境

- ruby-3.2.2
- rails (7.0.6)
- postgres 12.0

## 2. 環境構築手順

### 2.1. リポジトリのクローン

```zsh
  git clone git@github.com:rocky-engineer7/rails-docker.git
  cd rails-docker
```

### 2.2 docker-compose

```
  docker-compose build
```

```
  docker-compose run web rails db:create
```

```
  docker-compose up
```

http://localhost:3000/ にアクセス

上記のコマンドを上から順番に実行していただくと、http://localhost:3000/で Tasks が表示されます。
