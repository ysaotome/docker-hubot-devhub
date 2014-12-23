# docker-hubot-devhub

## devhub
> プログラマの為の開発支援コミュニケーションツール。作業中メモをリアルタイム共有する。
> http://dev-hub.herokuapp.com/

## hubot-devhub
> an DevHub adapter for Hubot

## How to use

- ex) run DevHub is http://192.168.0.1:3000/

```bash
$ docker run -d -p 10022:22 --env HUBOT_DEVHUB_URL="http://192.168.0.1:3000/" --name hubot-devhub ysaotome/hubot-devhub
```

## Add/Edit Hubot Script

- login container

```bash
$ ssh -p 10022 hubot@localhost
hubot@localhost's password: hubot
```

- Add/Edit

- hubot restart

```bash
$ supervisorctl restart hubot 
```

## References

- https://github.com/hashrock/hubot-devhub 
- https://github.com/volpe28v/DevHub

