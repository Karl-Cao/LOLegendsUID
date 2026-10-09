# 公共机器人维护分支

分支：`codex/public-bot-server`

上游基准：`ff47c07e52e78bcef5cf494399543c0e5e965e0a`

保留查询者队伍始终在上、对方在下的布局，以及参考 LeagueAkari 的单场表现估算（不是 Elo）。渲染辅助模块和 MIT 许可已收入 utils/public_bot，独立安装也能加载；用户自己的 WeGame 授权、自动绑定和 QQ 路由由 zzz-queue-obs 的 public_lol_bridge 与接入端负责。

主项目：[zzz-queue-obs](https://github.com/Karl-Cao/zzz-queue-obs)。配置、用户数据库、Cookie、Stoken、机器人密钥、日志和下载的资源目录未作为本次修改提交。此分支归档已部署补丁；fork 本身不会自动切换线上服务，上游默认分支保留供同步。
