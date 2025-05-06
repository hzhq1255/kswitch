# Kubectl Swtich Config Tool


## Require
oh-my-zsh
fzf kubectx kubens kube-ps1

## Install



clone repository
```shell
mkdir -p ~/.oh-my-zsh/custom/plugins
git clone https://github.com/hzhq1255/kswtich.git ~/.oh-my-zsh/custom/plugins/kswitch 
```

## Configure

edit ~/.zshrc
```text
plugins=(
    kswitch
)

```


## Usage


ssh root@host "cat ~/.kube/config" > ~/.kube/config-prd


kswitch prd
