# hydro-profile-lock

Hydro OJ 插件：用于锁定用户个人信息字段，并提供一键重置功能。

本插件基于 AI 辅助开发。

## 安装

```bash
hydrooj addon add "/path/hydro-profile-lock"
pm2 restart hydrooj
```

安装完成后请重启 Hydro。

## 使用

1. 进入管理后台，找到“个人信息锁定”。
2. 访问管理页：`/manage/profile-lock`。
3. 开启/关闭禁止修改、日志记录，查看锁定字段列表。
4. 需要时可执行“重置所有用户个人信息”。

## 配置项（可选）

- `profile-lock.enabled`: 是否启用（默认 `true`）
- `profile-lock.log`: 是否记录日志（默认 `true`）
- `profile-lock.fields`: 锁定字段列表
- `profile-lock.reset.backgroundImage`: 重置背景图

## 说明

- 本插件为 Hydro OJ 插件，Hydro 仓库：https://github.com/hydro-dev/Hydro

## 许可证

AGPL-3.0-only（与 Hydro 主仓库一致）。
