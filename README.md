# Hey-KPU
kaishi-LABの機材を説明するチャットボット

## 参考にした記事
[Next.js環境開発にdocker composeを使い倒した話](https://zenn.dev/k_hojo/articles/318d18e0e5b9ac#5.-docker-compose-up)

## 環境構築

> [!WARNING]
> Dockerやnodeが正しく動作する前提

> [!WARNING]
> 3・４のコマンド実行した際にエラー出るかもしれなけど、正しく検証してないから、一度最後まで実行してみて

1. 
```
git clone https://github.com/Ta2shi/Hey-KPU.git
```

3.
```
cd hey-KPU
```

3.
```
docker compose -f docker-compose.base.yml run --rm base
```

4.
```
docker compose -f docker-compose.base.yml run --rm installer
```

5.
```
docker compose up -d
```

> [!NOTE]
> http://localhost:3000/
