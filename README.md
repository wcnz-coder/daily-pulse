# daily-pulse

每天一次自动提交，用来保持 GitHub 贡献图连续。

- 触发：`.github/workflows/daily-pulse.yml`，每天 UTC 03:17（北京时间 11:17），也可手动 Run workflow
- 内容：往 `log/YYYY-MM.md` 追加一行日期时间
- 提交者固定为仓库所有者本人，才会算进 contributions

> 只想临时补几天：Actions → daily-pulse → Run workflow。
