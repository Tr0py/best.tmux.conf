# "Best" `tmux.conf` ever.

Convenient and portable tmux configuration file.

## Why this one?

There are awesome tmux configurations like [oh-my-tmux](https://github.com/gpakosz/.tmux), yet it does not fit my needs: portable and universal.

* **Portable**: I should be able to configure the tmux with simple commands & dependences. But oh-my-tmux relies on `Powerline`, which has to be configured manually.
* **Universal**: The shortcuts should be common, otherwise my habbit has to change as I connect to different servers. Eg. the server in the other side of ssh does not have silimiar key bindings. 

Therefore, here comes the simple, portable version of tmux conf.

## How to use 

**Backup your tmux config file.**

```shell
cp ~/.tmux.conf ~/.tmux.conf.bak
```

**Download this repo.**

```shell
git clone https://github.com/Tr0py/best.tmux.conf
```

**Copy the config file to your folder.**

```shell
cp .tmux.conf ~/.tmux.conf
tmux source-file ~/.tmux.conf
```

Enjoy!

`prefix`+

## Motivation

1. Easy-to-use, Portable and Universal tmux configuration.
2. The current [best tmux conf](https://gist.github.com/spicycode/1229612) is out of date. 

> /Users/tropping/.tmux.conf:13: invalid option: mode-mouse
> /Users/tropping/.tmux.conf:60: invalid option: window-status-current-bg
> /Users/tropping/.tmux.conf:61: invalid option: window-status-current-fg
> /Users/tropping/.tmux.conf:62: invalid option: window-status-current-attr

## 
