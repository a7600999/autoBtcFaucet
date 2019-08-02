# autoBtcFaucet
在 Telegram 上的 BTC Faucet 频道自动点击获取BTC的小工具。

## 使用方法
下载预编译好的软件包，解压到一个目录下，运行 `btcFaucet` 或 `getChats` 即可，注意 `Windows` 系统下文件名后缀是 `.exe`，并且 `Windows` 系统下需要保证那些 `.dll` 后缀的文件与执行文件在同一个目录，执行程序会在当前目录下生成 **db** 和 **files** 数据目录，作为保存 **电报** 客户端的会话。只要输入手机号、验证码、密码登录成功后，只要不删除数据目录，登录信息会一直保存，下次运行不需要再次登录。

`btcFaucet` 是自动点击程序，`getChats` 命令可以查看当前登录账号有哪些聊天会话，重点查看是否存在 `会话标题：BTC Faucet，会话 ID：848714900` 会话，如果没有加入 `BTC Faucet` 会话，是无法获取到**BTC**的。

输入命令后面加上 `--help`、`-help`、`-h` 参数可以查看命令帮助，通过添加命令参数可以支持 *http*、*socks5*、*Mtproto* 代理，并且可以调整每次点击的间隔时间。
