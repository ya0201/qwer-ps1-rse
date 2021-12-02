# qwer-ps1-rse (Randomized Shinobi Execution)
You can exec shinobi in your zsh prompt randomly!

## install
```shell
qwer-ps1 plugin add rse https://github.com/ya0201/qwer-ps1-rse.git
```

## usage
```shell
# in your .zshrc
if qwer-ps1 plugin is-installed rse; then
  PROMPT=${PROMPT}'$(qwer-ps1 show-current rse)'
fi
```

## customize
You can modify probability for shinobi execution.

```shell
# 0~100 %
export QWER_PS1_RSE_PROBABILITY=50
```
