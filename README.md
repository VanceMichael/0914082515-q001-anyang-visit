# 殷墟参访证据服务

记录遗址开放版本、访客预约与一次性参访凭证，数据仅保存于 SQLite。

## 运行

`go run ./cmd/migrate` 初始化数据库，`go run ./cmd/server` 启动接口，`go test ./...` 执行测试。
