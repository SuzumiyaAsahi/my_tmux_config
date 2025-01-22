# my_tmux_config

Ctrl + b + [  => 进入 copy mode

Ctrl + b + d  => 退出 tmux

Ctrl + b + w => 选择不同的 session

Ctrl + b + c => 创建新的 Window

Ctrl + b + , => rename session

tmux ls => 列出 session 列表

tmux kill-session -t 11 => 删除指定序号的 session

- 启动 tmux 使用 -s 命令指定会话名称，使用 -n 命令指定窗口名称

```bash
tmux new -s sessionName 
tmux new -n window
```

- 激活对应的 session

```bash
tmux attach -t Mao
```
